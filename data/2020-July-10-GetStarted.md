By default next,js pre renders a page. This means that nextjs generates pure HTML on server side and sends that file to client side. This allows the browsers and client systems to generate pages very fast.

Nextjs has two types for rendering depending on the requirements. 

Static rendering: The page is generated at build time and will be used on each request.

Server side rendering. On each request the getServersideprops are called to provide the necessary details to generate the page.


