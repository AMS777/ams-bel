
# ams-bel

Ember.js and Lumen JSON API quick-start boilerplate with common
functionality like user management, authentication and email notifications.

This repository is a quick and simple architecture to develop an API project 
using [Ember.js](https://www.emberjs.com/) as frontend and 
[Lumen](https://lumen.laravel.com/) as backend. Other architectures may be used.

It consists on a parent directory with two subdirectories and one file:

* `backend/`
* `frontend/`
* `.htaccess`

**This repository matches the [frontend project ams-be](https://github.com/AMS777/ams-be) 
developed with the Javascript framework [Ember.js](https://www.emberjs.com/) and
the [backend project ams-bl](https://github.com/AMS777/ams-bl) 
developed with the PHP micro-framework [Lumen](https://lumen.laravel.com/)** 
(though other frontend and backend may be used).


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


## Demo

**You can see a working demo of the ams-be frontend project and the ams-bl 
backend project with the ams-bel architecture at:**

**http://ams-bel.mas.gallery/**


## Install

Download or fork this repository and take it as the starting point of your own project.

If you want to use ams-be project as frontend and ams-bl project as backend, 
you have to download or fork their repositories take it as the starting point 
of your own project:

* [ams-be](https://github.com/AMS777/ams-be)
* [ams-bl](https://github.com/AMS777/ams-bl) 


## License

MIT License. Please see [LICENSE file](LICENSE) for more information.
