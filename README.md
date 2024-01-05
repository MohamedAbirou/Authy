# Authy

## Description

Authy is an advanced authentication service that i developed myself to help me with other projects authentication implementations and it's built using Next Auth V5
<br />

## Demo
<br />

[![Authy](https://github.com/MohamedAbirou/Authy/assets/109366637/26c0084c-c9f2-4966-ab3a-687c0a636846)](https://authy-zeta.vercel.app/)



<br />
<br />


## Features:

- 🔐 Next-auth v5 (Auth.js)
- 🚀 Next.js 14 with server actions
- 🔑 Credentials Provider
- 🌐 OAuth Provider (Social login with Google & GitHub)
- 🔒 Forgot password functionality
- ✉️ Email verification
- 📱 Two factor verification (2FA)
- 👥 User roles (Admin & User)
- 🚧 Role Gate
- 🔍 Advanced next.js middleware configuration
- 📈 next-auth session
- 🔄 next-auth callbacks
- 🛡️ Protect API Routes for admins only
- 🔐 Protect Server Actions for admins only
- 📧 Change email with new verification in Settings page
- 🔑 Change password with old password confirmation in Settings page
- 🔔 Enable/disable two-factor auth in Settings page
- 🔄 Change user role in Settings page (for development purposes only)

## Technologies used

- Next.js 14
- Next Auth
- TypeScript
- Tailwind CSS
- ShadcnUI
- Prisma ORM
- MongoDB


### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/MohamedAbirou/Authy.git
```

### Install packages

```shell
npm i
```

### Setup Prisma

```shell
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the issues page if you want to contribute.

## License

MIT
