# WEB-STARTER-TEMPLATES 1.0
Get started prototyping quickly with pre-configured setups.

### Before gitclone
```sh
git config --global http.postBuffer 524288000
git config --global core.compression 0
```

# Bootstrap-simple-Template

<p>A minimal Bootstrap setup using npm and SASS,but without build tools. Perfect for quick learning,prototyping and small projects</p>
  <pre>
  Bootstrap-simple-Template/
├── css/
│   ├── custom.css
│   ├── custom.css.map
│   └── styles.css
├── scss/
│   ├── css/
│   └── custom.scss
├── node_modules/
├── index.html
├── package-lock.json
└── package.json
  </pre>
  
### Install Sass globally

```sh
npm install -g sass
```

<p><b>Clone this repository</b></p>

Run   <b>cd ~</b> on linux or <b>cd $HOME</b> on windows to avoid permission issues before git clone.

 ```sh
git clone https://github.com/Adamsomondi/WEB-STARTER-TEMPLATES-1.0.git

 cd  WEB-STARTER-TEMPLATES-1.0/Bootstrap-simple-Template

npm install --save-dev autoprefixer@10.4.20 bootstrap@5.3.3 postcss-cli@11.0.0 postcss@8.4.35 sass@1.63.6

sass --watch ./scss/custom.scss ./css/custom.css
```

# Tailwind-simple-Template

<p>A minimal Tailwind setup using npm, Postcss, autoprefixer, postcss-cli but without build tools. Perfect for quick learning,prototyping and small projects</p>
 <pre>
tailwind-simple-Template/
├── dist/
│   └── styles.css
├── node_modules/
├── src/
│   └── styles.css
|---index.html
├── package.json
├── postcss.config.js
└── tailwind.config.js
  </pre>
  
<p><b>Clone this repository</b></p>


Run   <b>cd ~</b> on linux or <b>cd $HOME</b>  on windows to avoid permission issues before git clone.

 ```sh
git clone https://github.com/Adamsomondi/WEB-STARTER-TEMPLATES-1.0.git

cd  WEB-STARTER-TEMPLATES-1.0/Tailwind-simple-Template

npm install -D autoprefixer@10.4.20 postcss-cli@11.0.0 postcss@8.5.3 tailwindcss@2.2.19

npm run build
npm run watch
```

## Laravel-project-template

<p>A minimal laravel setup using php built in server[choco install php] and Composer PHP package manager[choco install composer setup].Perfect for quick learning,prototyping and small projects</p>
 <pre>
laravel-project/
├── app/
│   ├── Console/
│   ├── Exceptions/
│   ├── Http/
│   │   ├── Controllers/
│   │   ├── Middleware/
│   ├── Models/
│   ├── Providers/
├── bootstrap/
│   ├── cache/
├── config/
├── database/
│   ├── factories/
│   ├── migrations/
│   ├── seeders/
├── public/
│   ├── css/
│   ├── js/
│   ├── index.php
├── resources/
│   ├── js/
│   ├── lang/
│   ├── sass/
│   ├── views/
├── routes/
│   ├── api.php
│   ├── channels.php
│   ├── console.php
│   ├── web.php
├── storage/
│   ├── app/
│   ├── framework/
│   │   ├── cache/
│   │   ├── sessions/
│   │   ├── views/
│   ├── logs/
├── tests/
│   ├── Feature/
│   ├── Unit/
├── vendor/
├── .env
├── .env.example
├── .gitattributes
├── .gitignore
├── artisan
├── composer.json
├── composer.lock
├── package.json
├── phpunit.xml
├── README.md
└── webpack/vite.mix.js
 </pre>
 
 <p><b>Clone this repository</b></p>

Run   <b>cd ~</b> on linux or <b>cd $HOME</b>  on windows to avoid permission issues before git clone.
 ```sh
 git clone https://github.com/Adamsomondi/WEB-STARTER-TEMPLATES-1.0.git

cd WEB-STARTER-TEMPLATES-1.0/laravel-project

composer install
npm install

cp .env.example .env
php artisan key:generate

```
## Note
Edit .env by uncommenting #-delete,adding your details and save to connect to your database.

<pre>
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your-database-name
DB_USERNAME=root
DB_PASSWORD=your-password
</pre>

## Ensure MySQL is running Before Executing

<p><b>Open Powershell</b></p>

```sh
Get-Service MySQL*
```

```sh
php artisan migrate
```

## Terminal 1

```sh
npm run dev
```

## Terminal 2

```sh
php artisan serve
```
## Django-project-Template

<p>A minimal Django  setup using the Anaconda Distribution.Perfect for quick learning,prototyping and can be scaled for any projects and application</p>
 <pre>
Django_Project/
├── my_env/                  
├── mysite/                  
│   ├── mysite/
│   │   ├── init.py
│   │   ├── asgi.py
│   │   ├── settings.py
│   │   ├── urls.py
│   │   └── wsgi.py
│   ├── manage.py
├── myapp/                   //The application you want to build
│   ├── init.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── views.py
│   ├── migrations/
│   └── templates/
├── requirements.txt         # List of project dependencies create using pip freeze > requirements.txt
└── .gitignore               # Git ignore file using gitignore.io
 </pre>
 
  <p><b>Clone this repository</b></p>

Run   <b>cd ~</b> on linux or <b>cd $HOME</b>  on windows to avoid permission issues before git clone in <b>Anaconda Powershell</b>.
 ```sh
 git clone https://github.com/Adamsomondi/WEB-STARTER-TEMPLATES-1.0.git

cd  WEB-STARTER-TEMPLATES-1.O/Django-Project

Remove-Item -Recurse -Force my_env
 python -m venv my_env
 .\my_env\Scripts\activate
pip install -r requirements.txt
````

```sh
cd mysite
python manage.py migrate
```
```sh
python manage.py runserver 8080
```

## Start Creating your  application

```sh
python manage.py startapp yourapp
```

