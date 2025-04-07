# n8n Railway Deploy

Este repositorio contiene la configuración necesaria para desplegar una instancia de [n8n](https://n8n.io/) en [Railway](https://railway.app) utilizando un `Dockerfile`.

## 🚀 ¿Qué incluye?

- `Dockerfile` basado en la imagen oficial de n8n
- `railway.json` para configurar variables de entorno y el comando de inicio
- `.dockerignore` para evitar subir archivos innecesarios

## 🔐 Autenticación

Puedes proteger tu instancia agregando estas variables en Railway:

- `N8N_BASIC_AUTH_USER`: tu usuario
- `N8N_BASIC_AUTH_PASSWORD`: tu contraseña

## 🛠 Cómo desplegar

1. Haz fork o clona este repositorio
2. Conéctalo a Railway (New Project > Deploy from GitHub Repo)
3. Railway detectará el `Dockerfile` y construirá la instancia automáticamente
4. Agrega variables si deseas autenticación

---

> Hecho por @vargasb89 con propósito educativo y de automatización personal ⚡
