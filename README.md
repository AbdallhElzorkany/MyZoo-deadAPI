# MyZoo

A modern veterinary clinic management system built with Next.js, featuring appointment booking, service management, and a clean UI powered by Tailwind CSS.

## 🚀 Features

- **Clinic Overview** - Beautiful homepage with hero banner and clinic introduction
- **Service Catalog** - Detailed sections for all treatments and care services
- **Appointment System** - Easy-to-use booking form for scheduling visits
- **Responsive Design** - Fully responsive layout that works on all devices
- **Modern Stack** - Built with Next.js 15, TypeScript, and Tailwind CSS
- **Secure Authentication** - Complete user authentication with NextAuth.js

## 🛠️ Technologies Used

### Core
- **Next.js 15.3.1** - React framework for server-side rendering and static site generation
- **React 19** - JavaScript library for building user interfaces
- **TypeScript** - Type-safe JavaScript for better developer experience
- **Tailwind CSS** - Utility-first CSS framework for styling

### Authentication
- **NextAuth.js 5.0.0-beta.27** - Authentication for Next.js applications

### UI Components
- **Lucide React 0.503.0** - Beautiful & consistent icon toolkit
- **Date-fns 4.1.0** - Modern date utility library

### Development Tools
- **ESLint** - JavaScript/TypeScript linter
- **TypeScript** - Type checking
- **Turbopack** - Fast Rust-based bundler (used in dev script)

### Build & Package Management
- **npm** - Package manager
- **Node.js** - JavaScript runtime (required version 18.0.0 or later)

### Configuration
- **PostCSS** - CSS processing
- **Tailwind CSS PostCSS plugin** - For processing Tailwind CSS

## 📦 Prerequisites

- Node.js 18.0.0 or later
- npm or yarn package manager

## 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AbdallhElzorkany/myzoo.git
   cd myzoo
   ```

2. Install dependencies:

   ```bash
   npm install
   # or
   yarn
   ```

3. Set up environment variables:
   Create a `.env.local` file in the root directory and add the necessary environment variables with the following command:
   ```
   npx auth secret
   ```

## 🚦 Running the Development Server

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 🏗️ Building for Production

```bash
npm run build
npm start
# or
yarn build
yarn start
```

## 🧪 Running Tests

```bash
npm test
# or
yarn test
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ✨ Author

- [Abdallh Elzorkany](https://github.com/AbdallhElzorkany)

---

Built with ❤️ and Next.js
