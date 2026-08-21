![BlackMaps Banner](public/image/readme-banner.webp)
# 🗺️ BlackMaps™ - Sitio en desarrollo

## Descripción

Bienvenido al sitio web oficial de **BlackMaps**, una cuenta de X (antes Twitter) que se dedica a publicar mapas sobre absolutamente todo. ¿Algo existe? Le hacemos un mapa.

## Paginas

- **[Inicio](https://blackmaps.com.ar/)**
- **[Mapas](https://blackmaps.com.ar/maps)**
- **[Contacto](https://blackmaps.com.ar/contact)**

## Desarrollo

Este sitio web ha sido desarrollado por **[gefydev](https://www.linkedin.com/in/genadev)** y alojado por **[GenaHost](https://genahost.vercel.app/)**. Los mapas y logos del sitio son propiedad de BlackMaps y no deben ser utilizados sin autorización.

- **[Repositorio](https://github.com/gefydev/BlackMaps-Website/)**
- **[Licencia](https://github.com/gefydev/BlackMaps-Website/blob/main/LICENSE.md)**
- **[gefydev](https://www.linkedin.com/in/genadev)**

## Contacta a BlackMaps

- [Twitch](https://www.twitch.tv/mapsblack/)
- [Instagram](https://www.instagram.com/maps_black/)
- [Twitter](https://x.com/maps_black/)
- [GitHub](https://github.com/gefydev/BlackMaps-Website/)
- [Correo Electrónico](mailto:maps.black8@gmail.com)

## Información Adicional

© 2024 **[BlackMaps™](https://blackmaps.com.ar/)**. Sitio web desarrollado por **[gefydev](https://www.linkedin.com/in/genadev)** y alojado por **[GenaHost](https://genahost.vercel.app/)**. Los mapas y logos del sitio son propiedad de BlackMaps y no deben ser utilizados sin autorización.

## Estructura del Proyecto
### Framework: **[NextJS 14.2.5](http://nextjs.org)**
![BlackMaps Logo](public/image/readme-framework.webp)
Using APP Router

<pre style="font-family: 'Inter'; font-size: 14px; white-space: pre-wrap; word-wrap: break-word; color: white; background: #46776;">
🗺️ BlackMaps
├─ 📦 <a href="https://github.com/gefydev/BlackMaps-Website/tree/main/app">app</a>
│  ├─ 🈲 <a href="https://github.com/gefydev/BlackMaps-Website/tree/main/app/%5Blocale%5D">locale</a> -> Envuelve el contenido y varía según el idioma del usuario
│  │  ├─ ❌ <a href="https://github.com/gefydev/BlackMaps-Website/tree/main/app/%5Blocale%5D/%5B...notfound%5D">[...notfound]</a> -> Redirige inexistentes al archivo not-found.jsx
│  │  │  └─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/%5B...notfound%5D/page.jsx">page.jsx</a>
│  │  ├─ 🧩 <a href="https://github.com/gefydev/BlackMaps-Website/tree/main/app/%5Blocale%5D/components">components</a>
│  │  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/components/ClientHeader.jsx">ClientHeader.jsx</a> -> 🧑‍💻 Client Component
│  │  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/components/ClientSide.jsx">ClientSide.jsx</a> -> 🧑‍💻 Client Component
│  │  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/components/ContactForm.jsx">ContactForm.jsx</a> -> 🧑‍💻 Client Component
│  │  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/components/ErrorMessage.jsx">ErrorMessage.jsx</a> -> 🛜 Server Component
│  │  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/components/Footer.jsx">Footer.jsx</a> -> 🛜 Server Component
│  │  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/components/Header.jsx">Header.jsx</a> -> 🛜 Server Component
│  │  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/components/HomeArticle.jsx">HomeArticle.jsx</a> -> 🛜 Server Component
│  │  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/components/Logo.jsx">Logo.jsx</a> -> 🛜 Server Component
│  │  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/components/MapCard.jsx">MapCard.jsx</a> -> 🛜 Server Component
│  │  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/components/NotFoundTitle.jsx">NotFoundTitle.jsx</a> -> 🛜 Server Component
│  │  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/components/Pathname.jsx">Pathname.jsx</a> -> 🧑‍💻 Client Component
│  │  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/components/PoweredByGpt.jsx">PoweredByGpt.jsx</a> -> 🛜 Server Component
│  │  │  └─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/components/TranslationsProvider.jsx">TranslationsProvider.jsx</a> -> 🛜 Server Component
│  │  ├─ 📨 <a href="https://github.com/gefydev/BlackMaps-Website/tree/main/app/%5Blocale%5D/contact">contact</a>
│  │  │  └─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/contact/page.jsx">page.jsx</a>
│  │  ├─ 🌱 <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/layout.jsx">layout.jsx</a>
│  │  ├─ 🗺️ <a href="https://github.com/gefydev/BlackMaps-Website/tree/main/app/%5Blocale%5D/maps">maps</a>
│  │  │  └─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/maps/page.jsx">page.jsx</a>
│  │  ├─ ❌ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/not-found.jsx">not-found.jsx</a> -> Página 404
│  │  ├─ 🏠 <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/page.jsx">page.jsx</a> -> Homepage
│  │  └─ 🎨 <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/%5Blocale%5D/template.jsx">template.jsx</a> -> Aplica animaciones y resuelve algunas gestiones antes de cargar la página.
│  ├─ 🛜 <a href="https://github.com/gefydev/BlackMaps-Website/tree/main/app/api">api</a> -> Backend
│  │  ├─ 📨 <a href="https://github.com/gefydev/BlackMaps-Website/tree/main/app/api/mail">mail</a> -> Envía correos electrónicos (Formulario de contacto)
│  │  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/api/mail/route.js">route.js</a> -> Realmente devuelve 405 (Method not allowed)
│  │  │  └─ <a href="https://github.com/gefydev/BlackMaps-Website/tree/main/app/api/mail/send">send</a>
│  │  │     └─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/api/mail/send/route.js">route.js</a>
│  │  ├─ 🗺️ <a href="https://github.com/gefydev/BlackMaps-Website/tree/main/app/api/maps">maps</a> -> Carga los mapas desde otro servidor
│  │  │  └─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/api/maps/route.js">route.js</a>
│  │  └─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/api/route.js">route.js</a> -> Realmente devuelve 405 (Method not allowed)
│  ├─ 🎨 <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/globals.css">globals.css</a> -> CSS Principal
│  └─ 🈲 <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/app/i18n.js">i18n.js</a> -> Plugin de idioma
├─ 🈲⚙️ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/i18nConfig.js">i18nConfig.js</a> -> Configuración plugin de idioma
├─ 🈲 <a href="https://github.com/gefydev/BlackMaps-Website/tree/main/locales">locales</a> -> Carpeta que almacena las traducciones
│  ├─ 🇬🇧 <a href="https://github.com/gefydev/BlackMaps-Website/tree/main/locales/en">en</a> -> English
│  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/locales/en/ai-card.json">ai-card.json</a>
│  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/locales/en/contact.json">contact.json</a>
│  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/locales/en/footer.json">footer.json</a>
│  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/locales/en/header.json">header.json</a>
│  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/locales/en/home.json">home.json</a>
│  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/locales/en/maps.json">maps.json</a>
│  │  └─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/locales/en/notfound.json">notfound.json</a>
│  └─ 🇪🇸 <a href="https://github.com/gefydev/BlackMaps-Website/tree/main/locales/es">es</a> -> Español
│     ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/locales/es/ai-card.json">ai-card.json</a>
│     ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/locales/es/contact.json">contact.json</a>
│     ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/locales/es/footer.json">footer.json</a>
│     ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/locales/es/header.json">header.json</a>
│     ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/locales/es/home.json">home.json</a>
│     ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/locales/es/maps.json">maps.json</a>
│     └─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/locales/es/notfound.json">notfound.json</a>
├─ 🛜 <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/middleware.js">middleware.js</a> -> Se ejecuta antes de cargar la página
├─ 📦 <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/package.json">package.json</a>
├─ 📢 <a href="https://github.com/gefydev/BlackMaps-Website/tree/main/public">public</a>
│  ├─ ⚙️ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/public/browserconfig.xml">browserconfig.xml</a>
│  ├─ 🖼️ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/public/favicon.ico">favicon.ico</a>
│  ├─ 📷 <a href="https://github.com/gefydev/BlackMaps-Website/tree/main/public/image">image</a>
│  │  ├─ 🏳️ <a href="https://github.com/gefydev/BlackMaps-Website/tree/main/public/image/flags">flags</a>
│  │  │  ├─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/public/image/flags/en.svg">en.svg</a>
│  │  │  └─ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/public/image/flags/es.svg">es.svg</a>
│  │  └─ 🖼️ <a href="https://github.com/gefydev/BlackMaps-Website/tree/main/public/image">Imagenes del sitio</a>
│  ├─ 📲 <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/public/manifest.json">manifest.json</a>
│  ├─ 🤖 <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/public/robots.txt">robots.txt</a>
│  ├─ 🛡️ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/public/security.txt">security.txt</a>
│  └─ 🗺️ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/public/sitemap.xml">sitemap.xml</a>
├─ ©️ <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/LICENSE.md">LICENSE.md</a>
└─ 📖 <a href="https://github.com/gefydev/BlackMaps-Website/blob/main/README.md">README.md</a>
</pre>
---

[<img src="public/image/app-icon-512.webp" width="256"/>](public/image/app-icon-512.webp)

<font size="6" color="#ccc">**BlackMaps** by **Agustin Sanchez** ©2024</font>

Todos los derechos reservados

 [![Twitter Logo](public/image/x.webp) Twitter](https://x.com/maps_black)


---

<img alt="Logo de gefydev" src="public/image/genadev-v-nobg-2.webp">

<font size="6" color="#ccc">Developed by **gefydev** ©2024</font>

[![Github Logo](public/image/github.webp) Github](https://github.com/gefydev)

[![LinkedIn Logo](public/image/lnk.webp) LinkedIn](https://www.linkedin.com/in/genadev/)

[![Twitter Logo](public/image/x.webp) Twitter](https://x.com/gefydev)
