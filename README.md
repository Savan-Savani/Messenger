# Real-Time Messenger Clone: Next.js 13, React, Tailwind, Prisma, MongoDB, NextAuth, Pusher (2023)

This is a repository for a Real-Time Messenger Clone: Next.js 13, React, Tailwind, Prisma, MongoDB, NextAuth, Pusher.

Key Features:

- Real-time messaging using Pusher
- Tailwind animations and transition effects
- Full responsiveness for all devices
- Credential authentication with NextAuth
- Google authentication integration
- Github authentication integration
- File and image upload using Cloudinary CDN
- Server error handling with react-toast
- Message read receipts
- Online/offline user status
- Group chats and one-on-one messaging
- Message attachments and file sharing
- User profile customization and settings
- How to write POST, GET, and DELETE routes in route handlers (app/api)


### Cloning the repository

```shell
git clone https://github.com/Savan-Savani/Messenger.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
DATABASE_URL=
NEXTAUTH_SECRET=

NEXT_PUBLIC_PUSHER_APP_KEY=
PUSHER_APP_ID=
PUSHER_SECRET=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=

GITHUB_ID=
GITHUB_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
```

### Setup Prisma

```shell
npx prisma db push

```

### Start the app

```shell
npm run dev
```
