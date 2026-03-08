# Next.js Demo App

A modern demo application built with Next.js, showcasing best practices for building scalable web applications.

## Getting Started

### Prerequisites

- Node.js 20 or higher
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/nextjs-product-dashboard.git
cd nextjs-product-dashboard
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the application for production
- `npm run start` - Start the production server
- `npm run lint` - Run ESLint to check code quality

## Explore Page Routing

This application includes an Explore page that showcases product listing functionality using Next.js routing:

- **Explore Page** - Located at `/explore` route
- **Product Listing** - Displays a dynamic list of products with details
- **File-based Routing** - Uses Next.js file-based routing system for seamless navigation
- **Dynamic Routes** - Supports dynamic product pages using `[id].js` for individual product details
- **Server-side Rendering** - Products are pre-rendered for optimal performance and SEO

The Explore page demonstrates Next.js routing capabilities by:
- Creating routes using the `pages/explore` directory
- Fetching and displaying product data
- Implementing navigation between product listings and individual product pages
- Utilizing Next.js Link component for client-side navigation

## Project Structure

```
next_js_demo_app/
├── pages/           # Next.js pages and routes
├── components/      # Reusable React components
├── public/          # Static files
├── styles/          # CSS and styling
├── utils/           # Utility functions
└── README.md        # This file
```

## Technologies Used

- **Next.js** - React framework
- **React** - UI library
- **JavaScript/TypeScript** - Programming language
- **CSS/Tailwind** - Styling

## Deployment

The easiest way to deploy is using [Vercel](https://vercel.com):

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Vercel automatically deploys on every push

Alternatively, deploy using any Node.js hosting provider.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, open an issue on GitHub or contact the project maintainer.

---

Made with ❤️ using Next.js