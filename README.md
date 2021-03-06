
# ams-bel

This repository is a quick and simple architecture to develop an API project 
using [Ember.js](https://www.emberjs.com/) as frontend and 
[Lumen](https://lumen.laravel.com/) as backend. Everything stays within the same domain, hence no CORS is needed (Cross-Origin Resource Sharing).

It consists on a parent directory with two subdirectories and one file:

* `backend/`
* `frontend/`
* `.htaccess`

**This repository matches the [frontend project ams-be](https://github.com/AMS777/ams-be) 
developed with the Javascript framework [Ember.js](https://www.emberjs.com/) and
the [backend project ams-bl](https://github.com/AMS777/ams-bl) 
developed with the PHP micro-framework [Lumen](https://lumen.laravel.com/)**. 
These two projects are a quick-start boilerplate with common functionality like user management, authentication and email notifications to quickly start a JSON API web project.
Other frontend and backend may be used with this architecture and other architecture may be used with those frontend and backend.

## `backend/` directory

Contains all the Lumen backend files.

## `frontend/` directory

Contains the `dist/` directory generated by Ember.js with:

```
ember build -prod
```

## `.htaccess` file

Handles the request redirections to the `frontend/` and `backend/` directories
explained above.


## Install

Download or fork this repository and take it as the starting point of your own project.

If you want to use ams-be project as frontend and ams-bl project as backend, 
you have to download or fork their repositories take it as the starting point 
of your own project:

* [ams-be](https://github.com/AMS777/ams-be)
* [ams-bl](https://github.com/AMS777/ams-bl) 


## Run Development Environment

To serve the project locally, you need to run first the Lumen development server
and then the Ember.js development server proxied.

To run the Lumen development server, on command line in the backend directory 
(command from Flipbox Lumen Generator package):

```
$ php artisan serve
```

To run the Ember.js development server proxied, on command line in the frontend 
directory:

```
$ ember serve --proxy http://localhost:8000
```


## Usage

After creating your own project from the ones in the repositories, 
add your own files to the existing ones.

You can modify the existing files on the project you've created. The key
files are described in the Ember.js and Lumen repositories.


## License

MIT License. Please see [LICENSE file](LICENSE) for more information.
