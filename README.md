# Authentication-with-sanctum-boilerplate-laravel
- Api auth (signup, login, logout, reset password)


## Use project technology
Project Details
- Laravel v8.46.0

## Setup Instructions
- clone the repo
  `git clone this.repo`,
- install dependencies
  `composer install`
- perform migrations
  `php artisan migrate`
- serve
  `php artisan serve`
- server hosted `localhost:8000`

### API endpoints

- Signup:

  `POST: /api/auth/signup`
 
- Login:

  `POST: /api/auth/login`
  
- Logout:

  `POST: /api/auth/logout`

- Get authenticated user details:

  `GET: /api/auth/user`
- Send forgot password email:

  `POST: /api/auth/password/email`

- Reset password:

  `POST: /api/auth/password/reset`
