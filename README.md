# Laravel-Pusher Chat Showcase

Presenting a chat application crafted with Laravel and Pusher, showcasing the prowess of real-time messaging through Pusher's WebSocket technology.

## Content Overview

- [Distinctive Traits](#features)
- [Prerequisites](#requirements)
- [Setup Process](#installation)
- [Tailoring Settings](#configuration)
- [Operational Guide](#usage)
- [Community Participation](#contributing)
- [Usage Rights](#license)

## Noteworthy Features
- Seamless real-time chat capabilities
- Laravel backend seamlessly integrated with Pusher
- Intuitive and uncluttered user interface design

## System Prerequisites
- PHP version 8.1 or higher
- Laravel version 10 or above
- Composer
- Pusher account with essential credentials (API key, secret, and app ID)

## Setup Instructions
1. Dependencies Installation:
   ```bash
   cd laravel-push-chat-demo
   composer install
   ```

2. Duplicate the `.env.example` file to `.env`:
   ```bash
   cp .env.example .env
   ```

3. Configure Pusher credentials in the `.env` file:
   ```dotenv
   BROADCAST_DRIVER=pusher
   PUSHER_APP_ID=your-app-id
   PUSHER_APP_KEY=your-app-key
   PUSHER_APP_SECRET=your-app-secret
   PUSHER_APP_CLUSTER=your-app-cluster
   ```

4. Execute migrations and seed the database:
   ```bash
   php artisan migrate --seed
   ```
