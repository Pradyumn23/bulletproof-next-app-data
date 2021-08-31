By default Next.js pre renders a page. This means that Next.js  runs the javascipt and generates pure HTML on server side and sends that file to client side. This allows the browsers and client systems to generate pages very fast.

Next.js has two types for rendering depending on the requirements. 

Static rendering: The page is generated at build time and will be used on each request.

Server side rendering. On each request the getServersideprops(server side rendering) is called to provide the necessary details to generate the page.

With Next.js You can make a hybrid of the two in a custom  web application.

It is recommended to use  Static generation for performance reasons. Statically generated pages can be cached by CDN with no extra configuration to boost performance. 

Additionally stable static regeneration is also provided by Next.js!

Next.js allows you to create or update static pages after  you’ve built your site. Incremental Static Regeneration (ISR) enables you to use static-regeneration on a per-page basis, without needing to rebuild the entire site every time. ISR lets you scale a website to thousands of pages.

 ISR can be implemented by adding a revalidate property after the props in the return statement .


