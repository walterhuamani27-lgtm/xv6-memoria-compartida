# Memoria compartida (IPC) en xv6

Proyecto final del curso Sistemas Operativos (IS-380).

Universidad Nacional de San Cristóbal de Huamanga.

## Integrantes

- Andrés
- Félix

## Objetivo

Implementar un mecanismo de memoria compartida entre procesos
en el sistema operativo xv6-riscv.

## Funcionalidades previstas

- Llamadas al sistema shm_open() y shm_close().
- Asignación y mapeo de memoria compartida.
- Gestión de referencias y liberación de memoria.
- Comunicación entre procesos.
- Pruebas de funcionamiento y comparación con pipes.

## Estado del proyecto

En desarrollo. La versión inicial contiene el código base
de xv6, sin la extensión de memoria compartida implementada.

## Código original y atribución

Este proyecto utiliza como base xv6-riscv,
desarrollado por el Massachusetts Institute of Technology (MIT).

Repositorio original:
https://github.com/mit-pdos/xv6-riscv

Se conserva el archivo LICENSE original y sus condiciones.

Las modificaciones realizadas por los integrantes del equipo
se documentarán mediante commits y Pull Requests.

## Compilación y ejecución

Requiere Ubuntu, herramientas de compilación RISC-V y QEMU.

Ejecutar:

    make qemu

Para salir de QEMU: Ctrl+A, luego X.
