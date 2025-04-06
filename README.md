# Modern E-Commerce Platform

A beautiful and fast e-commerce website built with **Next.js 15** and **Wix Studio Headless APIs**.

## ✨ Features

- **Blazing Fast Performance**: Leverages Next.js 15's server components and streaming for optimal loading speeds
- **Responsive Design**: Looks great on all devices from mobile to desktop
- **Complete E-Commerce Solution**: Includes everything an online store needs:
  - Cart management
  - Secure checkout process
  - User account management
  - Email automation
  - Payment provider integration
  - Order tracking
  - Inventory management

## 🚀 Technical Stack

- **Frontend**: Next.js 15, React, Tailwind CSS
- **Backend**: Wix Studio Headless APIs
- **State Management**: React Context API with optimistic updates
- **Styling**: Tailwind CSS with custom theming
- **Authentication**: JWT-based auth with secure HTTP-only cookies
- **Deployment**: Vercel

## 💻 Best Practices Implemented

- **Server-Side Rendering**: For improved SEO and performance
- **URL State Management**: For shareable and bookmarkable pages
- **Optimistic Updates**: For a snappy user experience
- **Incremental Static Regeneration**: For dynamic content with static-like performance
- **Responsive Images**: With Next.js Image optimization
- **API Route Handlers**: For secure backend communication
- **Error Boundary Implementation**: For graceful error handling

## 🛠️ Getting Started

### Prerequisites

- Node.js 18.0.0 or later
- npm or yarn package manager
- Wix Studio account with API access

### Installation

```bash
# Clone the repository
git clone https://github.com/iamsufiyan560/Quick-Pick-Shop.git

# Navigate to the project directory
cd ecommerce-platform

# Install dependencies
npm install
# or
yarn install

# Set up environment variables
cp .env.example .env.local
```

### Configuration

1. Create a Wix Studio account and set up your store
2. Generate API keys from your Wix dashboard
3. Add the API keys to your `.env.local` file:

```
WIX_API_KEY=your_api_key_here
WIX_SITE_ID=your_site_id_here
NEXT_PUBLIC_SITE_URL=http://localhost:3000
```

### Development

```bash
# Run the development server
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

### Building for Production

```bash
# Build the application
npm run build
# or
yarn build

# Start the production server
npm start
# or
yarn start
```

## 📂 Project Structure

```
/
├── app/               # Next.js 15 app directory
│   ├── api/           # API route handlers
│   ├── (shop)/        # Shop routes grouped layout
│   ├── account/       # User account pages
│   ├── checkout/      # Checkout flow
│   └── layout.tsx     # Root layout
├── components/        # Reusable React components
│   ├── ui/            # UI components (buttons, inputs, etc.)
│   ├── products/      # Product-related components
│   ├── cart/          # Shopping cart components
│   └── checkout/      # Checkout components
├── lib/               # Utility functions and shared logic
│   ├── wix/           # Wix API client and helpers
│   ├── auth/          # Authentication utilities
│   └── hooks/         # Custom React hooks
├── public/            # Static assets
└── tailwind.config.js # Tailwind CSS configuration
```

## 🔄 API Integration

The platform integrates with Wix Studio Headless APIs for:

- **Product Catalog**: Fetching and filtering products
- **Inventory**: Real-time stock management
- **Cart & Checkout**: Order processing
- **User Management**: Authentication and profiles
- **Content Management**: Dynamic pages and blog

## 🛒 E-Commerce Features

### Product Catalog

- Advanced filtering and search
- Product variations (size, color, etc.)
- Related products
- Wishlist functionality

### Shopping Cart

- Real-time updates
- Save for later
- Discount code application
- Tax calculation

### Checkout Process

- Guest checkout
- Multiple payment methods
- Address validation
- Order summary

### User Accounts

- Order history
- Saved addresses
- Payment methods
- Email preferences

## 📱 Mobile Experience

The platform is fully responsive and provides a native-like experience on mobile devices:

- Touch-friendly interface
- Optimized images for faster loading
- Mobile-specific layouts
- Bottom navigation for easy access

## 🔒 Security

- HTTPS-only deployment
- CSRF protection
- Input validation
- Rate limiting
- XSS prevention

## 📈 Performance Optimization

- Lighthouse score > 90 on all metrics
- Core Web Vitals optimization
- Code splitting
- Image optimization
- Font optimization
- Third-party script management

## 🧪 Testing

```bash
# Run unit tests
npm run test
# or
yarn test

# Run end-to-end tests
npm run test:e2e
# or
yarn test:e2e
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👏 Acknowledgements

- [Next.js](https://nextjs.org/) - The React Framework
- [Wix Studio](https://www.wix.com/studio) - Headless CMS and E-commerce
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Vercel](https://vercel.com/) - Deployment platform

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Support

For questions and support, please open an issue in the GitHub repository or contact us at msufiyanhusen@gmail.com.
