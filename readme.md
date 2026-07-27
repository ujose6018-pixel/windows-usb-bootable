# Windows USB Booteable - Chrome OS Flex

Una herramienta web simple para crear un USB booteable con Windows desde Chrome OS Flex, **sin necesidad de usar terminal complicada**.

## 🎯 Qué hace

- ✅ Guía paso a paso en interfaz web amigable
- ✅ Descarga automática de ISO de Windows
- ✅ Genera script bash listo para copiar/pegar
- ✅ Incluye driver NVMe para tu HP
- ✅ Funciona en Chrome OS Flex

## 📱 Cómo usar

1. **Abre en tu Chrome OS Flex:**
   - Abre el navegador
   - Ve a: `https://tu-usuario.github.io/windows-usb-bootable/`

2. **Sigue los pasos:**
   - Selecciona Windows 11 o 10
   - Copia el script que se genera
   - Pega en terminal de Chrome OS Flex
   - Espera 20-30 minutos
   - Reinicia tu HP e instala Windows

## 🚀 Cómo desplegar en GitHub Pages

### Opción 1: Fork + GitHub Pages (más fácil)

1. Haz fork de este repositorio en GitHub
2. Ve a Settings → Pages
3. En "Source", selecciona "main" y "/ (root)"
4. Guarda
5. Tu app estará en: `https://tu-usuario.github.io/windows-usb-bootable/`

### Opción 2: Crear nuevo repositorio

```bash
# Clonar este proyecto
git clone https://github.com/tu-usuario/windows-usb-bootable.git
cd windows-usb-bootable

# Subir a tu propio repo
git remote set-url origin https://github.com/tu-usuario/mi-windows-usb.git
git push -u origin main
```

## 📋 Requisitos

- USB de 8GB mínimo
- Chrome OS Flex con internet
- HP compatible (producto testado en HP 15s-fq2000)

## ⚙️ Tecnología

- React 18 (desde CDN, sin build step)
- Babel Standalone (para JSX)
- CSS puro
- Hospedado en GitHub Pages (estático)

## 🔧 Personalizar

Edita `index.html` directamente para:
- Cambiar colores (busca `#667eea`)
- Modificar texto e instrucciones
- Agregar más dispositivos o versiones de Windows

## 📝 Notas

- El script descarga la ISO (5GB) - toma tiempo
- Balena Etcher se instala automáticamente
- Tienes que presionar confirmar en terminal (por seguridad)
- Intel VMD debe desactivarse en BIOS para que funcione

## ⚠️ Advertencia

- **Se formateará completamente el USB**
- Asegúrate de que sea el dispositivo correcto
- Verifica con `lsblk` antes de confirmar

## 🤝 Contribuir

Si encuentras bugs o tienes mejoras:
1. Abre un Issue
2. O haz un Pull Request

## 📄 Licencia

MIT - Úsalo libremente

---

**Creado para hacer más fácil instalar Windows en Chrome OS Flex** 💜
