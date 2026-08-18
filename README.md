# CIICCTE-server-frontend

## Sobre el proyecto

Frontend creado para interactuar con la infraestructura de CIICCTE-server-backend-V2

## Tech stack

Por motivos de documentacion, este es el stack de tecnologias usado para el desarrollo de este repo

- bun como runtime de js y gestor de paquetes
- vite para el servidor y por el ecosistema de desarrollo
- tailwindcss para desarrollar de manera rapida el apartado estetico
- react para iterar de manera rapida y estandarizada para el desarrollo del frontend


## Como iniciar el frontend

De manera personal utilizo bun para mis proyectos de desarrollo web, en teoria existe un alto grado de compatibilidad con node y npm pero para mantener la consistencia recomiendo usar [bun](https://bun.com/)

1. Clonar el repositorio

```bash
git clone https://github.com/mena-skibidi/CIICCTE-server-frontend.git
```

2. Instalar las dependencias del proyecto corriendo:

```bash
bun install
```

3. Y por ultimo se debera ejecutar el siguiente comando:

```bash
bun run dev --host
```