# Laravel & React boilerplate..

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
  npm run prod or $ npm run production (build your site)
```

After build your site then Remove 
```
  * node_modules,
  * package-lock.json,
  * js folder in your resources folder, 
  * sass folder in your resources folder
  
```


## Or Menually set Laravel & React Documentation

1) install laravel project 
	Command: $ composer create-project --prefer-dist laravel/laravel myProject

2) Command: $ cd myProject 
			$ php artisan serve
  Check laravel properly install, you can show your browser.

3) Install React 
  Command: $ composer require laravel/ui

  			"npm install && npm run dev" to compile your fresh scaffolding.
			$ npm install or npm i
			$ npm run dev

			// Generate basic scaffolding...
			$ php artisan ui react

			// Generate login / registration scaffolding...
			$ php artisan ui react --auth

	check myProject folder, go to resources folder then you can see coponents folder and files..

4) Command: $ npm install

5) Command: $ npm run dev



6) set <div id="example"></div> in your welcome.blade.php body

7) load script <script src="/js/app.js"></script> 

8) load CSS <link href="/css/app.css" rel="stylesheet">

9) You can see your browser, there is Loading React Component 

10) Command: $ cd myProject 
			 $ php artisan serve
			 $ npm run watch or npm run dev

11) Happy Laravel & React Coding :-)