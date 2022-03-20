<div align="center">
  Check out the demo [here](https://gabrielle-blog.vercel.app/)
</div>

<h2 align="center">Guide</h2>

<h3 align="center">Dependencies</h3>

This project uses the following dependencies:

- `next.js` - v12.0.10.
- `react` - v17.0.2.
- `react-dom` - v17.0.2.
- `mongodb` - v4.4.1 `mongoose` do not be used in this project.
- `next-connect` - v0.9.0 easier to apply Express/Connect middleware and routing method.
- `next-session` - v3.3.2.
- `connect-mongo` - v3.2.0.
- `swr` - v1.2.2 used for state management.
- `passport`, `passport-local` - used for authentication.
- `bcrypt` - v5.0.1 used for hashing password.
- `joi` - v17.6.0 used for validate.
- `multer` - v1.4.4 handle upload image with `multipart/form-data` type
- `cloudinary` - v1.28.1 using [this](https://cloudinary.com) for image upload.
- `react-hook-form` - v7.27.1 used for handling forms.
- Some UI/UX library such as: [framer-motion](https://www.framer.com/motion/), [tailwindcss](https://tailwindcss.com/), etc.

<h3 align="center">Environmental variables</h3>

All environmental variables in this project, you can view them on `.env.local.example`:

- `NEXT_PUBLIC_API_URL` The _URL_ of your web app.
- `MONGODB_URL` The MongoDB Connection String (with credentials and database name)
- `CLOUDINARY_URL` Check [this](https://cloudinary.com/documentation/node_integration#configuration).

<h3 align="center">Development</h3>

Before doing anything, please be sure that you have already created a `.env.local` file with above variables. Then, start the development server by running `npm run dev`.