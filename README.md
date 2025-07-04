# CAPTCHA Image Verification App

This is a **Next.js** project built with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app), featuring a CAPTCHA image verification system. Users are required to select images containing dogs before submitting a message.

## Tech Stack

- **Next.js**: React framework used for building the frontend and backend API routes.
- **React 19**: Core frontend library.
- **Tailwind CSS**: Utility-first CSS framework for responsive styling.
- **iron-session**: Used to manage secure, stateless session data across requests.
- **Node.js**: Backend runtime environment.
- **ESLint**: For code linting and best practices.
- **TypeScript (optional)**: Used for type safety. If you prefer JavaScript, you can remove `tsconfig.json` and all `.ts` or `.tsx` files.

## Getting Started

First, install dependencies:

```bash
npm install
```

Then, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

- `pages/`: Contains React components rendered by route.
- `pages/api/`: API routes handled by Next.js.
- `components/`: Reusable React components.
- `public/api/captcha-images`: Stores static captcha images.
- `styles/`: Global and component-specific styles.

## How CAPTCHA Works

1. A random set of images is displayed.
2. Users must click on images that contain dogs.
3. Selected indexes are validated on the server before sending the message.

## Deployment

You can deploy this project on platforms like [Vercel](https://vercel.com) or [Netlify](https://www.netlify.com/) with minimal configuration.

## License

This project is licensed under the MIT License.
