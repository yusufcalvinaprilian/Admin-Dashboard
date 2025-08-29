# Admin Dashboard - E-Commerce

A modern, responsive admin dashboard for e-commerce management built with Next.js, TypeScript, Redux Toolkit, and Tailwind CSS.

## 🚀 Features

- **Modern UI/UX**: Clean and professional design with Tailwind CSS
- **TypeScript**: Full type safety throughout the application
- **State Management**: Redux Toolkit for efficient state management
- **Authentication**: Basic login system with protected routes
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Real-time Data**: JSON Server for simulating REST API
- **Component Library**: Reusable UI components with Shadcn UI patterns

## 📊 Dashboard Sections

### 1. **Overview Dashboard**

- Key performance metrics (sales, orders, customers, products)
- Recent orders with status tracking
- Low stock alerts
- Visual data representation

### 2. **Product Management**

- Product listing with images and details
- Stock level monitoring
- Category management
- Product status tracking

### 3. **Order Management**

- Order tracking and status updates
- Customer order history
- Real-time order status changes
- Order details and shipping information

### 4. **Customer Management**

- Customer database with contact information
- Order history per customer
- Customer spending analytics
- Customer engagement metrics

### 5. **Analytics**

- Sales performance metrics
- Product category distribution
- Order status analytics
- Top-performing products
- Revenue trends

### 6. **Settings**

- User profile management
- Notification preferences
- Appearance customization
- Security settings

## 🛠️ Tech Stack

- **Frontend**: Next.js 15 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **State Management**: Redux Toolkit
- **UI Components**: Custom components with Shadcn UI patterns
- **Icons**: Lucide React
- **Mock API**: JSON Server
- **Authentication**: Custom auth system

## 📦 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yusufcalvinaprilian/Admin-Dashboard.git
   cd Admin-Dashboard
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm run dev
   ```

4. **Start JSON Server (in a separate terminal)**

   ```bash
   npm run json-server
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🔐 Authentication

**Demo Credentials:**

- Username: `admin`
- Password: `admin123`

## 📁 Project Structure

```
src/
├── app/                    # Next.js App Router
│   ├── dashboard/         # Dashboard pages
│   ├── login/            # Authentication
│   ├── globals.css       # Global styles
│   ├── layout.tsx        # Root layout
│   ├── page.tsx          # Home page
│   └── providers.tsx     # Redux provider
├── components/           # Reusable components
│   ├── ui/              # Base UI components
│   ├── layout/          # Layout components
│   └── dashboard/       # Dashboard-specific components
├── store/               # Redux store
│   ├── slices/          # Redux slices
│   └── index.ts         # Store configuration
├── types/               # TypeScript type definitions
├── lib/                 # Utility functions
└── data/                # JSON Server data
```

## 🎨 UI Components

The project includes custom UI components built with:

- **Button**: Multiple variants (default, outline, ghost, etc.)
- **Card**: Flexible card layouts with headers, content, and footers
- **Layout**: Responsive sidebar and main content area
- **Forms**: Styled form inputs and controls

## 📊 Data Management

### JSON Server Endpoints

- `GET /products` - Fetch all products
- `POST /products` - Create new product
- `PUT /products/:id` - Update product
- `DELETE /products/:id` - Delete product
- `GET /orders` - Fetch all orders
- `PATCH /orders/:id` - Update order status
- `GET /customers` - Fetch all customers
- `GET /users` - Fetch users for authentication

### Sample Data

The application comes with sample data including:

- 5 products with images and details
- 4 orders with different statuses
- 3 customers with order history
- 1 admin user for authentication

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint
- `npm run json-server` - Start JSON Server

## 🌟 Key Features

### 1. **Responsive Design**

- Mobile-first approach
- Adaptive layouts for all screen sizes
- Touch-friendly interface

### 2. **Real-time Updates**

- Live data from JSON Server
- Instant status updates
- Real-time notifications

### 3. **Performance Optimized**

- Next.js App Router for optimal routing
- Redux Toolkit for efficient state management
- Optimized bundle size

### 4. **Developer Experience**

- TypeScript for type safety
- ESLint for code quality
- Hot reload for development

## 🚀 Deployment

### Vercel (Recommended)

1. Connect your GitHub repository to Vercel
2. Deploy automatically on push to main branch
3. Configure environment variables if needed

### Other Platforms

- Netlify
- Railway
- DigitalOcean App Platform

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) for the amazing React framework
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [Redux Toolkit](https://redux-toolkit.js.org/) for state management
- [Lucide React](https://lucide.dev/) for beautiful icons
- [Shadcn UI](https://ui.shadcn.com/) for component design patterns

## 📞 Support

If you have any questions or need help, please open an issue on GitHub or contact the maintainer.

---

**Built with ❤️ using Next.js, TypeScript, and Tailwind CSS**
