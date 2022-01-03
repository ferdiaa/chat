# Laravel-Vue Realtime Chat


## Installation

- `git clone composer https://github.com/BakayDev/private-chat.git`
- `cd private-chat && composer i && cp .env.example .env `
- Edit `.env` and set your database connection details
- Edit `.env` and set your pusher connection key `https://dashboard.pusher.com/apps/yourId/keys`)
- (When installed via git clone or download and make .env, run `php artisan key:generate` 
- `php artisan migrate:fresh --seed `
- `php artisan serve` open `http://127.0.0.1:8000`
- You can login - email :`test@gmail.com` password :`test@gmail.com`

## Usage

#### Development
resources/js/components/PrivateChatComponent.vue
resources/js/components/PrivateMessageComponent.vue

#### serve with hot reloading
npm run watch


