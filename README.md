# Proyecto de CCTV y almacenamiento en red con TrueNAS

## Enlace

[ProyectoTFG](TFG_RafaelNuñezVazquez.pdf)

## 📌 Descripción

Este proyecto forma parte del ciclo formativo de **Administración de Sistemas Informáticos en Red (ASIR)** y se divide en dos bloques principales: el estudio de los sistemas de videovigilancia CCTV y la instalación y configuración de un servidor NAS mediante TrueNAS CORE.

El objetivo es conocer los componentes necesarios para desplegar un sistema CCTV y poner en marcha una solución de almacenamiento centralizado que permita compartir archivos entre equipos de una red local.

## 🛠️ Tecnologías y herramientas

- **TrueNAS CORE:** sistema operativo para la gestión del almacenamiento en red.
- **Proxmox:** virtualización del servidor NAS.
- **ZFS:** sistema de archivos y gestión de pools de almacenamiento.
- **Samba (SMB):** compartición de archivos entre Windows y Linux.
- **FTP con TLS 1.2:** transferencia de archivos mediante una conexión protegida.
- **Plex Media Server:** gestión y acceso a contenido multimedia.
- **Ubuntu y Windows:** equipos cliente para comprobar el funcionamiento de los servicios.
- **CCTV:** análisis de cámaras, grabadores, cableado, alimentación y conectores.

## 📹 Parte 1: Sistemas CCTV

Estudio de los elementos necesarios para diseñar e instalar un circuito cerrado de televisión.

- Comparación de sistemas CCTV analógicos, digitales/IP e híbridos.
- Análisis de grabadores DVR, XVR y NVR.
- Tipos de cámaras: bullet, domo e IP.
- Selección de discos duros según las necesidades de grabación.
- Estudio del cableado coaxial, UTP, conectores y sistemas de alimentación.
- Consideraciones sobre la señalización de zonas videovigiladas.

## 💾 Parte 2: Instalación y configuración de TrueNAS

Despliegue de un servidor NAS virtualizado en Proxmox y configuración de sus principales servicios.

- Instalación de TrueNAS CORE y configuración de la dirección IP estática.
- Administración del sistema desde la interfaz web.
- Creación de usuarios, grupos y permisos de acceso.
- Configuración de pools y datasets con ZFS, incluyendo un ejemplo de RAID-Z1.
- Creación de recursos compartidos mediante Samba (SMB).
- Comprobación del acceso y transferencia de archivos desde Ubuntu y Windows.
- Configuración de un servidor FTP con TLS 1.2 y pruebas mediante FileZilla.
- Instalación y configuración de Plex Media Server para acceder a contenido multimedia.

## 🎯 Objetivos y resultados

- Comprender los componentes y las tecnologías utilizadas en instalaciones CCTV.
- Desplegar un servidor NAS en un entorno virtualizado.
- Administrar almacenamiento centralizado mediante ZFS.
- Compartir archivos entre distintos sistemas operativos mediante SMB.
- Configurar y probar servicios de transferencia de archivos y multimedia.
- Documentar el proceso de instalación, configuración y verificación mediante capturas de pantalla.

## 📚 Formación

**Ciclo formativo:** Administración de Sistemas Informáticos en Red (ASIR).

**Áreas de trabajo:** redes, virtualización, almacenamiento, servicios de red y sistemas de videovigilancia.

Aqui puedes ver de forma orientativa los objetivos de este proyecto [ProyectoTFG](TFG_RafaelNuñezVazquez.pdf)
