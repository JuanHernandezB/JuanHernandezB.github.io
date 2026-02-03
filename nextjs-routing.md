En Next.js (App Router), ya no se usa el componente <Head>. Asegúrate de revisar:

[ ] Metadata Object: ¿Estás exportando el objeto metadata en los layout.js o page.js?

[ ] generateMetadata: Para páginas dinámicas (ej. productos), ¿estás usando esta función para que el SEO sea único por ID?

[ ] Favicons y Manifest: ¿Están configurados en la raíz de /app?