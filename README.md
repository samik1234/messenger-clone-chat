This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).


![msg1](https://github.com/samik1234/messenger-clone-chat/assets/82882143/b36a0acd-e0e1-4a4f-bab8-fa41521427a4)




Key Features:

Real-time messaging using Pusher
Message notifications and alerts
Tailwind design for sleek UI
Tailwind animations and transition effects
Full responsiveness for all devices
Credential authentication with NextAuth
Google authentication integration
Github authentication integration
File and image upload using Cloudinary CDN
Client form validation and handling using react-hook-form
Server error handling with react-toast
Message read receipts
Online/offline user status
Group chats and one-on-one messaging
Message attachments and file sharing
User profile customization and settings
How to write POST, GET, and DELETE routes in route handlers (app/api)
How to fetch data in server React components by directly accessing the database (WITHOUT API! like Magic!)
Handling relations between Server and Child components in a real-time environment
Creating and managing chat rooms and channels






Install packages
npm i
Setup .env file
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
Setup Prisma
npx prisma db push
Start the app
npm run dev
Available commands
Running commands with npm npm run [command]


## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
