# Obligatorio de Sistemas Operativos

Trabajo obligatorio de la materia Sistemas Operativos, Ingeniería en Sistemas, Universidad ORT Uruguay (2025). Hecho en equipo de dos. Cuatro ejercicios independientes que cubren shell scripting, concurrencia y despliegue con contenedores.

## Ejercicios

### 1. Sistema de gestión en Bash (`ej1/`)
Aplicación de consola en Bash con login de usuarios, alta y venta de productos, filtros y generación de reportes. Persistencia en archivos de texto.

### 2. Concurrencia en C con hilos y semáforos (`ej2/`)
Simulación de un aeropuerto con `pthread`: pasajeros que compiten por un recurso compartido, sincronizados con semáforos POSIX. Compilar con `gcc aeropuerto.c -o aeropuerto -lpthread`.

### 3. Concurrencia en Ada (`ej3/`)
Simulación de vacunación y ordeñe de vacas con tareas de Ada y generadores aleatorios. Compilar con `gnatmake vacas.adb`.

### 4. Aplicación web balanceada con Docker (`ej4/`)
Gestor de tareas en Node.js desplegado con Docker Compose:

- 2 réplicas de la app web (Express)
- Redis como almacenamiento compartido entre réplicas
- nginx como reverse proxy y balanceador de carga (round-robin)

```
cd ej4/obligatorio_so_parte4-2
docker compose up --build
```

Acceso en `http://localhost:3000`. Documentación técnica y manual de usuario en `ej4/.../Documentación/`.

## Stack

Bash · C (pthreads, semáforos POSIX) · Ada · Node.js/Express · Redis · nginx · Docker Compose
