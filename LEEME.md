# [[Ventoy-USB-es - README]]

## Introducción
[Ventoy](https://www.ventoy.net/en/index.html)  es una herramienta de código abierto para crear unidades USB de arranque para archivos ISO/WIM/IMG/VHD(x)/EFI permitiendo varias imágenes en una sola unidad.
Este repositorio pretende establecer una configuración inicial, general y estructurada basada en idioma español (España).

Está establecido los alias e iconos de la mayoría de ISOS , así como su organización en directorios (Windows, Linux, Utilidades).

Contiene un **autounattend.xml*** para **Windows 10-11** 
- Idioma y región español.
- ByPass para Windows 11.
- Automatización de la mayor parte de la instalación, exceptuando la solicitud del serial de Windows (activación post-instalación), nombre de equipo, usuario (local), contraseña y particionamiento del disco. 
- Eliminación la mayoria de bloatware de preinstalado de Windows, dejando lo mas básico.
- Se establece un tema oscuro con fondo gris y configuración de la barra de tareas. 

Ademas incluye un archivo de registro, para volver a tener el clásico **Visualizador de Imágenes** de Windows, e instrucciones para colocar la **Papelera de Reciclaje** en la barra de tareas

## Estructura
```
├─ 📂 Apps
├─ 📂 Docs
├─ 📂 drivers
|
├─ 📂 ISO
|  ├─ 📂 1-Windows
|  ├─ 📂 2-Linux
|  └─ 📂 3-Utility
|
├─ 📂 persistence
|
└ 📂 ventoy/
  ├─ {} ventoy.json
  ├─ 🖹 README.md
  ├─ 📂 script/
	  └─ 📂 W10-11_autounattend_v1
  └─ 📂 theme/
	  └─ 📂 poly-dark/
		  └─ 📂 icons
```

## Tema
El Tema es [Poly-Dark](https://github.com/shvchk/poly-dark). con fondo personalizado gris y algunos iconos añadidos

## Imágenes
- **Windows**
- **Linux**
	- [Arch](https://archlinux.org/)
	- [Debian](https://www.debian.org/)
	- [Fedora](https://fedoraproject.org/)
	- [Gentoo](https://www.gentoo.org/)
	- [OpenSUSE](https://www.opensuse.org/)
	- [Manjaro](https://manjaro.org/)
	- [Linux Mint](https://linuxmint.com/)
	- [Ubuntu](https://ubuntu.com/)
	- [Kali-Linux](https://www.kali.org/)
- **Utilidades**
	- [Acronis True Image](https://www.acronis.com/es/products/true-image/)
	- [CloneZilla](https://clonezilla.org/)
	- [HirensBootCD](https://www.hirensbootcd.org/)
	- [Gparted](https://gparted.org/index.php)
	- [Parted Magic](https://partedmagic.com/)
	- [Rescatux](https://www.supergrubdisk.org/rescatux/)
	- [System Rescue](https://www.system-rescue.org/)
	- [Virtio Win Drivers](https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/)
	- [WinPE Sergei Strelec](https://sergeistrelec.name/winpe-10-8-sergei-strelec-english/)
