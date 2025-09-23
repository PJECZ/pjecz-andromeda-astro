# PJECZ Andromeda Astro

Sitio web [justiciadigital.gob.mx](https://justiciadigital.gob.mx/) donde se documentan las plataformas del [Poder Judicial del Estado de Coahuila de Zaragoza](https://www.pjecz.gob.mx/).

## Desarrollar

Requiere [NodeJS](https://nodejs.org/) versión 22.

Clonar el repositorio

```bash
git clone https://github.com/PJECZ/pjecz-andromeda-astro.git
```

Instalar

```bash
npm install
```

Arrancar el servicio web en desarrollo

```bash
npm run dev
```

## Inicializar

A continuación se describen los pasos para instalar [Astro](https://astro.build/) y los paquetes que se usan en este sitio web.

Crear un nuevo sitio web con Astro

```bash
npm create astro@latest
```

El asistente le preguntará el nombre del directorio, que para este proyecto es `pjecz-andromeda-astro`

Ir al directorio creado

```bash
cd pjecz-andromeda-astro
```

Instalar [Tailwind](https://docs.astro.build/en/guides/styling/#tailwind) como framework de diseño

```bash
npx astro add tailwind
```

Instalar [MDX](https://docs.astro.build/en/guides/integrations-guide/mdx/) para tener sintaxis de markdown extendida

```bash
npx astro add mdx
```

Instalar [Partytown](https://partytown.qwik.dev/astro/) para correr scripts de terceros en pilas

```bash
npx astro add partytown
```

Instalar [Material Design Icons](https://www.astroicon.dev/guides/customization/)

```bash
npx astro add astro-icon
```

Y el paquete con iconos

```bash
npm install @iconify-json/mdi
```

Instalar [Astro Compress](https://www.npmjs.com/package/astro-compress)

```bash
npx astro add astro-compress
```

Instalar [Tailwind Typography](https://www.npmjs.com/package/@tailwindcss/typography) para que los archivos markdown reciban su estilo

```bash
npm install @tailwindcss/typography
```

Instalar [Astro NavBar](https://github.com/surjithctly/astro-navbar) para tener un menu responsivo de tres barras

```bash
npm install astro-navbar
```

Instalar [sharp](https://sharp.pixelplumbing.com/) necesario para procesar las imágenes

```bash
npm install sharp
```

Arrancar el servicio web para desarrollo

```bash
npm run dev
```
