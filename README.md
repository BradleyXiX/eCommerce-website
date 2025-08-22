# QuickCart - E-Commerce Website

QuickCart is a modern e-commerce web application built with [Next.js](https://nextjs.org/), React, and Tailwind CSS. It features a seamless shopping experience, seller dashboard, cart management, and order tracking.

## Features

- 🛒 Browse and search for products
- 🏷️ Product details with images and descriptions
- 🛍️ Add to cart and checkout flow
- 🚚 Order summary and address management
- 📦 Seller dashboard for product management and order tracking
- 🔒 Authentication-ready (Clerk integration)
- ⚡ Fast, responsive, and mobile-friendly UI
- 🎨 Styled with Tailwind CSS

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/BradleyXiX/quickcart.git
   cd quickcart
   ```

2. **Install dependencies:**
   ```sh
   npm install
   # or
   yarn install
   ```

3. **Configure environment variables:**

   Copy `.env` and fill in your credentials:
   ```
   NEXT_PUBLIC_CURRENCY=$
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   MONGODB_URI=
   INNGEST_SIGNING_KEY=
   INNGEST_EVENT_KEY=
   CLOUDINARY_CLOUD_NAME=
   CLOUDINARY_API_KEY=
   CLOUDINARY_API_SECRET=
   ```

4. **Run the development server:**
   ```sh
   npm run dev
   # or
   yarn dev
   ```

5. **Open your browser:**

   Visit [http://localhost:3000](http://localhost:3000) to see the app.

## Project Structure

```
.
├── app/                # Next.js app directory (pages, layouts, routes)
├── components/         # Reusable React components
├── context/            # React context for global state
├── assets/             # Images, icons, and dummy data
├── lib/                # Utility libraries (e.g., authentication)
├── public/             # Static assets
├── .env                # Environment variables
├── tailwind.config.mjs # Tailwind CSS configuration
├── package.json        # Project metadata and scripts
└── ...
```

## Scripts

- `npm run dev` – Start the development server
- `npm run build` – Build for production
- `npm start` – Start the production server
- `npm run lint` – Run ESLint

## Customization

- **Products & Orders:** Dummy data is used for products and orders. Integrate with your backend or database for production use.
- **Authentication:** Clerk is set up for authentication. Configure your Clerk keys in `.env`.
- **Styling:** Tailwind CSS is used for styling. Customize in `tailwind.config.mjs` and `app/globals.css`.

## License

This project is for educational purposes. Please check individual dependencies for their licenses.

---

Built with from a tutorial by GreatStack.