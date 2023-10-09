
<div align="center">
<h1>MI PORTAFOLIO PERSONAL</h1>
<h3>USANDO ASTRO, SVELTE, TYPESCRIPT, TAILWIND Y VERCEL</h3>
</div>


Antes de comenzar, asegúrate de tener instalados los siguientes requisitos previos en tu sistema:

- **Node.js** (versión 16.12.0 o superior)
- **Visual Studio Code** con las siguientes extensiones: "astro-vscode," "prettier-vscode," "svelte-vscode," y "tailwindcss-intellisense."

### Paso 1: Configuración Inicial del Proyecto Astro

Comencemos creando un nuevo proyecto Astro con el siguiente comando:

```shell
npm create astro@latest
```

Astro te solicitará detalles específicos. Sigue las instrucciones y elige las opciones que mejor se adapten a tus necesidades. Es fundamental seleccionar TypeScript y mantener la configuración predeterminada para una configuración coherente.

### Paso 2: Agregar Svelte, Tailwind CSS, Vercel y Prettier

A continuación, incorporaremos las integraciones deseadas en nuestro proyecto. Ejecuta los siguientes comandos desde el directorio recién creado de Astro, optando por las opciones predeterminadas cuando se te solicite:

```shell
npx astro add svelte
npx astro add tailwindcss
npx astro add vercel
npm install prettier prettier-plugin-astro prettier-plugin-svelte prettier-plugin-tailwindcss
```

