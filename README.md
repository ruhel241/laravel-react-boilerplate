# Laravel & React boilerplate

## Project setup
Install node_modules.
```
npm install
```

Install Laravel Composer in your project folder, command in your terminal. 
```
composer install
```

Create .env file just command in your terminal:
```
cp .env.example .env
```

Laravel key:Generate in your project
```
php artisan key:generate
```
Navigate your project then command in your terminal:
``` 
php artisan serve
```

Compiles and reloads for development
``` 
npm run watch or npm run dev
```
Happy Coding :)


Compiles and minifies for production
```
npm run prod or npm run production (build your site)
```

After build your site then Remove 
```
  * node_modules,
  * package-lock.json,
  * js folder in your resources folder, 
  * sass folder in your resources folder

```


# Or Menually set Laravel & React Documentation

## Installation Laravel
Install Laravel Project
```  
composer create-project --prefer-dist laravel/laravel myProject
```

Navigate your project
``` 
* cd myProject 
* php artisan serve
```
Check laravel properly install, you can show your browser.


## Installation React 

Navigate your project then command in your terminal:
``` 
composer require laravel/ui
``` 

npm install && npm run dev to compile your fresh scaffolding 
```	
npm install or npm i

npm run dev
```

Generate basic scaffolding...
```	
php artisan ui react
```	

Generate login / registration scaffolding...
```	
php artisan ui react --auth
```	

Check your myProject folder, go to resources folder then you can see components folder and files..

Compiles and reloads for development
```	 
npm install

npm run dev
```	

### React integrate in your laravel blade file

```
 * set <div id="example"></div> in your welcome.blade.php body
 * load script <script src="/js/app.js"></script> 
 * load CSS <link href="/css/app.css" rel="stylesheet">
 * You can see your browser, there is Loading React Component 

```

Navigate your project then command in your terminal:
```
cd myProject 
php artisan serve
npm run watch or npm run dev
```

Happy Laravel & React Coding :-)