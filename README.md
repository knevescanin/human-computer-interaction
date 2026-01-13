# 🛍️ HCI Pricehare

HCI Pricehare is a modern Next.js application that enables users to search and compare product prices across various stores in Croatia. The platform features user authentication, favorites management, search functionality, and a responsive design for optimal user experience across all devices.

 

## 💡 Idea

This web application was created as a collaborative project combining two courses: **Human-Computer Interaction (HCI)** and **Introduction to Data Science**. The goal was to develop a price comparison platform that helps users find the best deals on products across different stores in Croatia. The project demonstrates best practices in web design, usability, and modern web development, while also incorporating data-driven features and analytics. It emphasizes intuitive navigation, responsive design, and seamless user interactions to enhance the shopping and price comparison experience.

 

## 🛠️ Features

**User Authentication and Authorization**: Users can sign up and log in to access personalized features.

**Product Browsing**: Browse products organized by categories and stores with an intuitive interface.

**Price Comparison**: Compare prices for the same products across different Croatian stores to find the best deals.

**Search Functionality**: Search capabilities to quickly find desired products.

**Favorites Management**: Users can save their favorite products for easy access later.

**Responsive Design**: Fully responsive layout that adapts to different screen sizes and devices.

**Real-Time Updates**: Dynamic content loading with optimized performance.

**Categorized Navigation**: Easy-to-use category and store filtering system.

**Pagination**: Efficient pagination for browsing large product catalogs.

 

## 💻 Technologies Used

**Next.js 15**: For building a fast, server-side rendered React application.

**React 18**: For building interactive and dynamic user interfaces.

**TypeScript**: For type-safe code and improved developer experience.

**Tailwind CSS**: For modern, responsive styling.

**NextAuth.js**: For authentication and session management.

**Prisma ORM**: For database management and queries.

**PostgreSQL**: For relational data storage.

**Vercel**: For deployment and hosting.

 

## ▶️ Application Preview

Check out the live application: [https://hci-bay.vercel.app](https://hci-bay.vercel.app)

 

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ installed
- PostgreSQL database

### Installation

*Note: The installation steps below are provided for developers who want to run the project locally or contribute to the codebase. The live application is already deployed and accessible at the link above.*

1. Clone the repository:
```bash
git clone <repository-url>
cd HCI/hci-course
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
Create a `.env` file in the `hci-course` directory with the following:
```env
DATABASE_URL="your-postgresql-connection-string"
NEXTAUTH_URL="http://localhost:3000"
NEXTAUTH_SECRET="your-secret-key"
```

4. Run Prisma migrations:
```bash
npx prisma generate
npx prisma db push
```

5. Start the development server:
```bash
npm run dev
```

6. Open [http://localhost:3000](http://localhost:3000) in your browser.

 

## 🔮 Possible Future Enhancements

**Advanced Filtering**: Add more filtering options (price range, ratings, etc.).

**Wishlist Sharing**: Enable users to share their favorite products with others.

**Price Tracking**: Notify users when products go on sale.

**Multiple Languages**: Support for internationalization and multiple languages.

 

## 🤝 Contributing

If you'd like to contribute to this project, please feel free to submit a pull request or file an issue on GitHub.

 

## 📜 License

This project is licensed under the MIT License.

 

## 👥 Authors

This project was developed collaboratively as part of the HCI course curriculum.
