<h1 align="center">LinuxCommandAutomation 🐧</h1>

<p align="center"><strong>Scripts en Bash para automatizar tareas de administración de sistemas en Linux, con menús interactivos.</strong></p>

<p align="center">
  <img alt="Bash" src="https://img.shields.io/badge/Bash-shell-4eaa25">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-sysadmin-fcc624">
  <img alt="Licencia Apache 2.0" src="https://img.shields.io/badge/licencia-Apache%202.0-22c55e">
</p>

---

Tres scripts de **Bash** que agrupan las tareas habituales de administración de un sistema Linux en menús sencillos, para no tener que recordar cada comando. Nacieron durante mi formación en **Administración de Sistemas Informáticos en Red** y los uso como base para automatizar.

Cada script comprueba que se ejecuta como **root**, valida cada paso y guía al usuario con un menú por pantalla.

---

## 🧰 Qué incluye

| Script | Qué hace |
|---|---|
| **`ManageGroupsAndUsers.sh`** | Lista, crea, modifica y elimina usuarios y grupos del sistema. |
| **`ManageNetworkInterfaces.sh`** | Muestra las interfaces de red y sus IP, y activa o desactiva las que elijas. |
| **`ManagePackages.sh`** | Instala, actualiza y desinstala paquetes, comprobando antes si están presentes. |

---

## 🚀 Cómo se usan

Necesitas una distribución de **Linux** y permisos de **root** (los scripts lo verifican al arrancar).

```bash
# Dar permiso de ejecución (solo la primera vez)
chmod +x ManageGroupsAndUsers.sh ManageNetworkInterfaces.sh ManagePackages.sh

# Ejecutar como root
sudo ./ManageGroupsAndUsers.sh
sudo ./ManageNetworkInterfaces.sh
sudo ./ManagePackages.sh
```

Cada uno abre un menú; escribe el número de la opción que quieras y sigue las indicaciones. La opción `0` sale.

> ⚠️ `ManagePackages.sh` está pensado para distribuciones basadas en **Debian/Ubuntu** (gestor de paquetes `apt`). Revisa el script antes de usarlo en otra distribución.

---

## 📄 Licencia

Publicado bajo licencia **Apache 2.0**. Puedes usarlo, modificarlo y distribuirlo libremente conservando el aviso de licencia.

---

<p align="center">
  Hecho con 🐧 por <strong>Alexei Barberà Roca</strong><br>
  <a href="https://www.linkedin.com/in/alexei-barbera-roca">LinkedIn</a> ·
  <a href="https://github.com/alexeibarbera">GitHub</a>
</p>
