## <a name="introduction">Introduction</a>

Road Runner is an innovative car rental application with customizable car selection based on passenger count and distance preference.
Integrated with a user-friendly map functionality, Stripe payment processing, and SMTP email sending capabilities to streamline rental processes for both individuals and teams, enhancing efficiency and convenience.
Leveraging Stripe payment gateway, Leaflet mapping library, and MongoDB API to develop robust payment, mapping, database features.

## <a name="tech-stack">Tech Stack</a>

- Next.js
- MongoDB
- Mongoose
- free map location
- stripe
- SMTP
- Shadcn
- Tailwind Css

## <a name="quick-start">Integration and Installation Process</a>

Follow these steps to set up the project locally on your device.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)
- [Git](https://git-scm.com/)


**Installation**

Install dependencies using yarn:

```bash
yarn
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env

NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=""
STRIPE_SECRET_KEY=""
NEXT_PUBLIC_FRONTEND_URL=http://localhost:3000
NEXT_PUBLIC_DATABASE_URL=""


NEXT_PUBLIC_SMTP_HOST=smtp.gmail.com
NEXT_PUBLIC_SMTP_PORT=465
NEXT_PUBLIC_SMTP_SERVICE=gmail
NEXT_PUBLIC_SMTP_MAIL=
NEXT_PUBLIC_SMTP_EMAIL=
NEXT_PUBLIC_SMTP_PASSWORD=
```

**Running the Project using yarn**

```bash
yarn run dev
```
