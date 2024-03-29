## Laravel 10 + Inertia.js + Vue 3 -> single page application

> This is a fork of https://github.com/perisicnikola37/laravel-inertia-vue-spa, and pre-includes the [Pinegrow Vite Plugin](https://www.npmjs.com/package/@pinegrow/vite-plugin), [Pinegrow Tailwind CSS Plugin](https://www.npmjs.com/package/@pinegrow/tailwindcss-plugin) and other goodies for Vue Designer.<br><br>It specifically configures the PHP application server (instead of Vite which is used as a middleware) in Pinegrow Vite Plugin, to enable live-designing of Vue components of this laravel/inertia project.

Youtube video tutorial here - https://www.youtube.com/@vuedesigner

```js
liveDesigner({
    devServerUrls: {
        local: "http://127.0.0.1:8000/",
    },
    //...
}),
```

**Vue Designer** is a desktop visual editor for Mac, Windows and Linux that lets you visually design your Vue applications. Take it for a free trial at [Vue Designer](https://vuedesigner.com)!<br><br>

<div style="display: flex;">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Laravel.svg/985px-Laravel.svg.png" alt="Laravel Logo" style="width: 40px;">
  <img src="https://user-images.githubusercontent.com/79047182/222930653-4c8079bc-30f0-43e1-9c63-b50a9ad68320.png" alt="image" style="width: 40px;">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1184px-Vue.js_Logo_2.svg.png" alt="Vue.js Logo" style="width: 40px;">
 <img src="https://ih1.redbubble.net/image.2428884987.0603/st,small,507x507-pad,600x600,f8f8f8.jpg" alt="Redbubble Image" style="width: 40px;">
</div>
<br>
The application is designed to provide a smooth and interactive user experience. This SPA offers an all-in-one solution for managing users and roles, featuring an easy-to-use dashboard for administrators.

## Preview

[gif.webm](https://user-images.githubusercontent.com/79047182/222930543-9883369c-1d8f-4985-9b61-baa933122596.webm)

## Installation

To get started with the installation, follow these steps:

1. Clone the repository
   `git clone https://github.com/perisicnikola37/laravel-inertia-vue-spa.git`

2. Enter project directory
   `cd laravel-inertia-vue-project`

3. Install/update composer
   `composer install | composer update`

4. Install npm
   `npm install`

5. Set up the environment variables
   `cp .env.example .env`

6. Generate an application key
   `php artisan key:generate`

7. Configure the database
   `php artisan migrate`

8. Start the app server
   `php artisan serve`

9. Parallely (in a separate terminal), start the development server
   `npm run dev`

10. Visit the application at [http://localhost:8000](http://localhost:8000)

## Features

This application includes the following features:

-   User authentication and authorization
-   CRUD operations for users and roles
-   Real-time updates using Inertia.js and Vue.js
-   Two factor authentication
-   Browser sessions
-   Full text searching
-   Pagination
-   Multi delete users
-   Inertia.ks progress indicator
-   Font Awesome icons
-   Application analytics
-   User default profile avatar

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.
