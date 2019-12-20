<h1>LaraNuxt-API</h1>

Laravel API with CRUD functionality for decoupled app. Includes JWT Authentication, pagination, threads, posts, likes.

I have built a Nuxt frontend that integrates this API: https://github.com/jtbradley/LaraNuxt-client

<h2>Installation</h2>

<h4>Install Dependencies</h4>
<code>composer install</code>

<h4>Run Migrations</h4>
<code>php artisan migrate</code>

<h4>Generate Key for JWT Auth</h4>
<code>php artisan jwt:secret</code>

<h2>Endpoints</h2>

<h4>Get the endpoints</h4>

<code>php artisan route:list</code>
