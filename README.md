<div align="center">

<img src="https://trackbook-official.vercel.app/assets/favicon.png" alt="TrackBook Logo" width="50" />

# TrackBook - Book Management System

A modern, full-stack web application for seamless book browsing, borrowing, and library management — designed to make every reading journey organized, delightful, and effortless.

[![Live Demo](https://img.shields.io/badge/▶_Live_Demo-trackbook--official.vercel.app-00C853?style=for-the-badge&logo=vercel&logoColor=white)](https://trackbook-official.vercel.app/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/zahid-official/milestone-11-client)
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
<img src="https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white" alt="React Router" />
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
<img src="https://img.shields.io/badge/DaisyUI-5A0EF8?style=for-the-badge" alt="DaisyUI" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />

</div>

<br/>

## 🔍 Overview

**TrackBook** is a comprehensive library management system that brings clarity and convenience to every reader's experience. Users can browse categorized book collections, view detailed information, borrow and return books, and manage their reading activity — all backed by Firebase authentication, JWT-secured endpoints, and a RESTful backend API.

> _Where every reading journey is just a page away._

<br/>

## ✨ Key Features

### 📚 Book Management

<table align="center">
<thead>
<tr><th align="left">Feature</th><th align="left">Description</th></tr>
</thead>
<tbody>
<tr><td><b>Browse by Category</b></td><td>Explore books organized into distinct categories with dedicated listing pages</td></tr>
<tr><td><b>Detailed Book View</b></td><td>View comprehensive book information including author, rating, description, and availability</td></tr>
<tr><td><b>Add New Books</b></td><td>Authenticated users can contribute new book entries to the library collection</td></tr>
<tr><td><b>Update Books</b></td><td>Edit and update existing book details including title, author, category, and more</td></tr>
<tr><td><b>All Books</b></td><td>View the complete library catalog with filter and toggle between card and table views</td></tr>
</tbody>
</table>

### 🔐 Authentication & Security

<table align="center">
<thead>
<tr><th align="left">Feature</th><th align="left">Description</th></tr>
</thead>
<tbody>
<tr><td><b>Email/Password Auth</b></td><td>Register and sign in with email credentials powered by Firebase Authentication</td></tr>
<tr><td><b>Google OAuth</b></td><td>Quick one-click sign-in using Google account via Firebase</td></tr>
<tr><td><b>JWT Authentication</b></td><td>Secure token-based access control for protected API endpoints</td></tr>
<tr><td><b>Protected Routes</b></td><td>All Books, Add Book, Borrowed Books, and Book Details are secured behind private routes</td></tr>
<tr><td><b>Profile Display</b></td><td>Logged-in users see their profile photo and name with a sign-out dropdown</td></tr>
</tbody>
</table>

### 🎨 User Interface

<table align="center">
<thead>
<tr><th align="left">Feature</th><th align="left">Description</th></tr>
</thead>
<tbody>
<tr><td><b>Responsive Design</b></td><td>Fully optimized for mobile, tablet, and desktop viewports using Tailwind CSS</td></tr>
<tr><td><b>Interactive Carousels</b></td><td>Swiper-powered sliders for dynamic banner and content presentation</td></tr>
<tr><td><b>Scroll Animations</b></td><td>Smooth entrance animations powered by <code>AOS</code> (Animate On Scroll)</td></tr>
<tr><td><b>Lottie Animations</b></td><td>Engaging animated illustrations via <code>lottie-react</code> on login and register pages</td></tr>
<tr><td><b>Motion Effects</b></td><td>Fluid micro-animations using the <code>motion</code> library for enhanced interactivity</td></tr>
<tr><td><b>Star Ratings</b></td><td>Visual book ratings through <code>@smastrom/react-rating</code> components</td></tr>
<tr><td><b>Toast Notifications</b></td><td>User-friendly feedback through <code>react-toastify</code> alerts for all CRUD operations</td></tr>
<tr><td><b>Dynamic Page Titles</b></td><td>Website title changes dynamically based on the current route for better UX</td></tr>
</tbody>
</table>

<br/>

## 🛠️ Tech Stack

<table align="center">
<thead>
<tr><th align="left">Technology</th><th align="center">Version</th><th align="left">Purpose</th></tr>
</thead>
<tbody>
<tr><td><b>React</b></td><td align="center"><code>^18.3.1</code></td><td>Component-based UI development</td></tr>
<tr><td><b>JavaScript</b></td><td align="center"><code>ES6+</code></td><td>Application logic and interactivity</td></tr>
<tr><td><b>Vite</b></td><td align="center"><code>^6.0.1</code></td><td>Lightning-fast dev server and build tooling</td></tr>
<tr><td><b>Firebase</b></td><td align="center"><code>^11.1.0</code></td><td>Authentication and user management</td></tr>
<tr><td><b>React Router DOM</b></td><td align="center"><code>^7.0.2</code></td><td>Declarative client-side routing</td></tr>
<tr><td><b>Tailwind CSS</b></td><td align="center"><code>^3.4.16</code></td><td>Utility-first CSS framework</td></tr>
<tr><td><b>DaisyUI</b></td><td align="center"><code>^4.12.22</code></td><td>Tailwind-based UI component library</td></tr>
<tr><td><b>Axios</b></td><td align="center"><code>^1.7.9</code></td><td>Promise-based HTTP client for API requests</td></tr>
<tr><td><b>Swiper</b></td><td align="center"><code>^11.1.15</code></td><td>Touch-enabled slider and carousel</td></tr>
<tr><td><b>Motion</b></td><td align="center"><code>^11.15.0</code></td><td>Production-ready animation library</td></tr>
<tr><td><b>AOS</b></td><td align="center"><code>^2.3.4</code></td><td>Scroll-triggered reveal animations</td></tr>
<tr><td><b>Lottie React</b></td><td align="center"><code>^2.4.0</code></td><td>Lottie JSON animation renderer</td></tr>
<tr><td><b>React Rating</b></td><td align="center"><code>^1.5.0</code></td><td>Accessible star rating component</td></tr>
<tr><td><b>React Toastify</b></td><td align="center"><code>^10.0.6</code></td><td>Toast notification system</td></tr>
<tr><td><b>React Icons</b></td><td align="center"><code>^5.4.0</code></td><td>Popular icon sets as React components</td></tr>
</tbody>
</table>

<br/>

## 🏗️ Architecture

<div align="center">
<pre>
┌─────────────────────────────────────────────────────────────┐
│                        Browser                              │
├─────────────────────────────────────────────────────────────┤
│  React App (Vite)                                           │
│  ┌───────────┐  ┌──────────────┐  ┌──────────────────────┐  │
│  │  Layout   │  │  React       │  │  Auth Provider       │  │
│  │  (Navbar+ │◄─┤  Router      │  │  (Firebase Context)  │  │
│  │   Footer) │  │  (Public +   │  │                      │  │
│  │           │  │   Private)   │  │  • Login / Register  │  │
│  └───────────┘  └──────┬───────┘  │  • Google OAuth      │  │
│                        │          │  • JWT Tokens         │  │
│               ┌────────▼────────┐ └──────────────────────┘  │
│               │     Pages       │                           │
│               │  Home │AllBooks │                           │
│               │  AddBook│Update│                           │
│               │  BorrowedBooks  │                           │
│               │  BookDetails    │                           │
│               │  Category       │                           │
│               └────────┬────────┘                           │
│                        │                                    │
│               ┌────────▼────────┐                           │
│               │   Components    │                           │
│               │  Navbar│Footer  │                           │
│               │  Quotes│PageTtl │                           │
│               └─────────────────┘                           │
├─────────────────────────────────────────────────────────────┤
│  Backend API: https://trackbook-server.vercel.app           │
│  Database: MongoDB (via Vercel serverless functions)        │
└─────────────────────────────────────────────────────────────┘
</pre>
</div>

## 📂 Project Structure

```
milestone-11-client/
│
├── index.html                     # HTML entry point
├── package.json                   # Dependencies and scripts
├── vite.config.js                 # Vite configuration
├── tailwind.config.js             # Tailwind CSS configuration
├── postcss.config.js              # PostCSS configuration
├── vercel.json                    # Vercel deployment configuration
│
├── public/                        # Static assets
│   └── assets/                   # Images, icons, banners, and media
│
└── src/
    ├── main.jsx                   # React DOM entry point
    ├── App.jsx                    # Root application wrapper
    ├── index.css                  # Global styles and Tailwind directives
    │
    ├── Auth/                      # Authentication system
    │   ├── Context/              # Auth context definition
    │   ├── Firebase/             # Firebase configuration
    │   ├── Hook/                 # Custom auth hooks
    │   └── Provider/             # Auth context provider
    │
    ├── Layout/                    # Shared layout (MainLayout wrapper)
    ├── Router/                    # Route config and private route guard
    ├── Lottie/                    # Lottie animation JSON files
    │
    ├── Components/                # Reusable UI components
    │   ├── Navbar.jsx            # Navigation bar
    │   ├── Footer.jsx            # Site footer
    │   ├── PageTitle.jsx         # Dynamic page title component
    │   └── Quotes.jsx            # Inspirational quotes section
    │
    └── Pages/                     # Application pages
        ├── Home/                 # Landing page, categories, and book details
        ├── AddBook/              # Add new book form
        ├── All Books/            # Browse all books and update book
        ├── BorrowedBooks/        # User's borrowed books dashboard
        ├── Login/                # Login page with Lottie animation
        ├── Register/             # Registration page
        └── Error/                # 404 error page
```

<br/>

## 🚀 Getting Started

### Prerequisites

<table align="center">
<thead>
<tr><th align="left">Requirement</th><th align="left">Details</th></tr>
</thead>
<tbody>
<tr><td><b>Node.js</b></td><td>v18 or higher recommended</td></tr>
<tr><td><b>npm</b></td><td>Comes bundled with Node.js</td></tr>
<tr><td><b>Firebase Project</b></td><td>Required for authentication features</td></tr>
<tr><td><b>Modern Browser</b></td><td>Chrome, Firefox, Safari, or Edge</td></tr>
</tbody>
</table>

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/zahid-official/milestone-11-client.git

# 2. Navigate to the project directory
cd milestone-11-client

# 3. Install dependencies
npm install

# 4. Set up environment variables (see section below)

# 5. Start the development server
npm run dev
```

The application will be available at `http://localhost:5173` by default.

<br/>

## 🔑 Environment Variables

Create a `.env.local` file in the project root with the following Firebase credentials:

```env
VITE_apiKey=your_firebase_api_key
VITE_authDomain=your_project.firebaseapp.com
VITE_projectId=your_project_id
VITE_storageBucket=your_project.appspot.com
VITE_messagingSenderId=your_sender_id
VITE_appId=your_app_id
```

> **Note:** All environment variables must be prefixed with `VITE_` for Vite to expose them to the client bundle. Never commit `.env.local` to version control.

<br/>

## 📜 Available Scripts

<table align="center">
<thead>
<tr><th align="left">Command</th><th align="left">Description</th></tr>
</thead>
<tbody>
<tr><td><code>npm run dev</code></td><td>Start the Vite development server with HMR</td></tr>
<tr><td><code>npm run build</code></td><td>Create an optimized production build</td></tr>
<tr><td><code>npm run preview</code></td><td>Preview the production build locally</td></tr>
<tr><td><code>npm run lint</code></td><td>Run ESLint to check for code quality issues</td></tr>
</tbody>
</table>

<br/>

## ⚙️ How It Works

<div align="center">
<pre>
User lands on Home ──► Browses Book Categories ──► Selects a Category
                                                        │
                                ┌───────────────────────┘
                                ▼
                      Route requires auth?
                       ┌──── Yes ────┐
                       ▼             ▼
                  Not logged in   Logged in
                       │             │
                       ▼             ▼
                  Redirect to    View Category
                  Login Page     Book Listings
                       │             │
                       ▼             ▼
                  Authenticate   Select a Book
                  (Email/Google) (View Details)
                       │             │
                       ▼             ▼
                  Return to ────► Borrow Book
                  Category Page   (Set Return Date)
                                     │
                                     ▼
                               Manage Dashboard
                            (Borrowed Books + Returns)
</pre>
</div>

1. **Landing** — Users explore the platform overview, featured books, category cards, inspirational quotes, and reading stories on the home page.
2. **Category Browsing** — Selecting a category loads all books in that genre dynamically from the backend API.
3. **Authenticated Access** — Viewing book details or borrowing triggers a private route; unauthenticated users are redirected to sign in.
4. **Book Details & Borrowing** — Users can view complete book information, ratings, and borrow books with a specified return date.
5. **Dashboard Management** — Users can add new books, update existing entries, and manage their borrowed books from dedicated dashboard pages.

<br/>

## 🌟 Author

<div align="center">
  <a href="https://github.com/zahid-official">
    <img src="https://github.com/zahid-official.png" width="100" height="100" style="border-radius: 50%;" alt="Zahid Official" />
  </a>

  <h3>Zahid Official</h3>
  <p><b>Web Developer | Tech Enthusiast</b></p>

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/zahid-official)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/zahid-web)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zahid.official8@gmail.com)

  <p>Creating impactful digital experiences with passion and purposeful design</p>
</div>

<br/>

## 🤝 Contributing

Contributions are welcome and appreciated! Here's how you can help improve **TrackBook**:

```bash
# 1. Fork the repository

# 2. Create a feature branch
git checkout -b feature/your-feature-name

# 3. Make your changes and commit
git commit -m "feat: add your feature description"

# 4. Push to your fork
git push origin feature/your-feature-name

# 5. Open a Pull Request against the main branch
```

<p align="center"><b>TrackBook</b> <i>— Where every reading journey is just a page away.</i></p>
