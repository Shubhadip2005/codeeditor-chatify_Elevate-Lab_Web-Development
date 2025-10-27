<div align="center">

# 🚀 Elevate Lab - Web Development Projects Internship

### Professional Full-Stack Web Applications Collection

[![Made with React](https://img.shields.io/badge/Made%20with-React-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

**[View Projects](#-projects) • [Getting Started](#-getting-started) • [Documentation](#-documentation) • [Contributing](#-contributing)**

*A curated collection of modern, production-ready web applications showcasing full-stack development expertise*

---

**Built by [Shubhadip Das](https://github.com/Shubhadip2005)** • Connect on [LinkedIn](https://www.linkedin.com/in/shubhadip-das-6040052a7)

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Projects](#-projects)
  - [Code Editor](#1-my-code-editor)
  - [Chatify](#2-chatify-app)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Features Comparison](#-features-comparison)
- [Documentation](#-documentation)
- [Development](#-development)
- [Deployment](#-deployment)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🌟 Overview

**Elevate Lab** is a comprehensive portfolio of modern web applications demonstrating expertise in full-stack development, real-time communication, and professional UI/UX design. This repository contains two major projects, each showcasing different aspects of modern web development.

### Why Elevate Lab?

- 🎯 **Production-Ready** - All projects are built with industry best practices
- 🔥 **Modern Stack** - Latest React, Node.js, and cutting-edge technologies
- 💡 **Real-World Applications** - Practical solutions to common development needs
- 📱 **Fully Responsive** - Perfect experience across all devices
- 🚀 **Performance Optimized** - Fast load times and smooth interactions
- 🔒 **Security First** - Implementing modern security practices

---

## 🎯 Projects

<table>
<tr>
<td width="50%" valign="top">

### 1. 🖥️ Code Editor Pro

<div align="cemter">

![codeeditor](/my-code-editor/public/Code%20Editor%20Interface.png)

</div>

**Modern Web Development Environment**

A powerful, feature-rich online code editor built with React, providing a complete development environment in your browser.

#### ✨ Key Features
- 🎨 Monaco Editor (VS Code engine)
- 📱 Real-time live preview
- 🎯 Professional templates
- 💾 Auto-save functionality
- 🌓 Dark/Light themes
- 📦 Export as ZIP

#### 🛠️ Technologies
- React 19.2.0
- Monaco Editor 4.7.0
- Tailwind CSS
- Firebase (Storage)
- Lucide React

#### 🔗 Quick Links
- [Live Demo](#) • [Documentation](./my-code-editor/README.md)

</td>
<td width="50%" valign="top">

### 2. 💬 Chatify

<div align="cemter">

![chat](/chatify-app/frontend/public/chat_for_frontend.png)

</div>

**Real-Time Chat Application**

A full-stack, real-time chat application featuring secure authentication, instant messaging, and beautiful UI design.

#### ✨ Key Features
- 🔐 JWT Authentication
- ⚡ Socket.IO real-time messaging
- 🖼️ Image sharing (Cloudinary)
- 👥 Online/Offline status
- 🎨 Modern dark theme
- 📧 Email integration (Resend)

#### 🛠️ Technologies
- React 19 + Node.js
- Socket.IO
- MongoDB + Mongoose
- Express.js

#### 🔗 Quick Links
- [Live Demo](#) • [Documentation](./chatify-app/README.md)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

### Frontend Technologies

<div align="center">

| Technology | Version | Purpose |
|------------|---------|---------|
| **React** | 19.x | UI library for building interfaces |
| **Vite** | Latest | Fast build tool and dev server |
| **Tailwind CSS** | 3.x | Utility-first CSS framework |
| **Zustand** | Latest | Lightweight state management |
| **Socket.io Client** | Latest | Real-time communication |
| **Axios** | Latest | HTTP client for API calls |
| **Monaco Editor** | 4.7.0 | Code editor component |
| **Lucide React** | Latest | Beautiful icon library |
| **LocalStorage & FireBase** | Latest | Save Code |

</div>

### Backend Technologies

<div align="center">

| Technology | Version | Purpose |
|------------|---------|---------|
| **Node.js** | 20.x | Server runtime environment |
| **Express.js** | Latest | Web application framework |
| **MongoDB** | 6.x | NoSQL database |
| **Mongoose** | Latest | MongoDB object modeling |
| **Socket.IO** | Latest | Real-time engine |
| **JWT** | Latest | Authentication tokens |
| **Bcryptjs** | Latest | Password hashing |
| **Cloudinary** | Latest | Image storage and CDN |

</div>

### Development Tools

- **ESLint** - Code linting and quality
- **Prettier** - Code formatting
- **Git** - Version control
- **Postman** - API testing
- **VS Code** - Development environment

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

```bash
# Check Node.js version (>= 20.0.0 required)
node --version

# Check npm version
npm --version

# MongoDB should be installed and running
mongod --version
```

### Quick Start

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Shubhadip2005/codeeditor-chatify_Elevate-Lab_Web-Development.git
   cd codeeditor-chatify_Elevate-Lab_Web-Development
   ```

2. **Choose Your Project**

   <table>
   <tr>
   <td width="50%">

   **For Code Editor Pro:**
   ```bash
   cd my-code-editor
   npm install
   npm start
   ```
   Access at: `http://localhost:3000`

   </td>
   <td width="50%">

   **For Chatify:**
   ```bash
   cd chatify-app
   npm run build
   
   # Configure .env in backend
   cd backend
   cp .env.example .env
   
   # Start application
   npm start
   ```
   - Frontend: `http://localhost:5173`
   - Backend: `http://localhost:3000`

   </td>
   </tr>
   </table>

### Environment Configuration

#### Code Editor Pro

```env
# .env
REACT_APP_API_URL=your_api_url
REACT_APP_ANALYTICS_ID=your_analytics_id
```

#### Chatify

```env
# backend/.env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_key
CLOUDINARY_API_SECRET=your_cloudinary_secret
RESEND_API_KEY=your_resend_api_key
NODE_ENV=development
PORT=3000
```

---

## 📁 Project Structure

```
codeeditor-chatify_Elevate-Lab_Web-Development/
│
├── my-code-editor/                    # Code Editor Pro Application
│   ├── public/
│   │   ├── index.html
│   │   └── favicon.ico
│   ├── src/
│   │   ├── components/
│   │   │   └── CodeEditor.js           # Main editor component
│   │   │ 
│   │   ├── utils/
│   │   │   ├── LZString.js            # LZString utilities
│   │   │   └── TEMPLATES.js           # Template definitions
│   │   ├── App.js                   
│   │   ├── index.css
│   │   └── index.js
│   ├── package.json
│   ├── tailwind.config.js
│   └── README.md                      # Detailed documentation
│
├── chatify-app/                       # Chatify Application
│   ├── backend/
│   │   ├── controllers/               # Route handlers
│   │   ├── models/                    # MongoDB schemas
│   │   ├── routes/                    # Express routes
│   │   ├── middleware/                # Auth & security
│   │   ├── lib/                       # Configuration
│   │   └── server.js
│   ├── frontend/
│   │   ├── src/
│   │   │   ├── components/            # React components
│   │   │   ├── pages/                 # Page components
│   │   │   ├── store/                 # Zustand stores
│   │   │   └── hooks/                 # Custom hooks
│   │   └── public/
│   ├── package.json
│   └── README.md                      # Detailed documentation
│
├── .gitignore
├── LICENSE
└── README.md                          # This file
```

---

## 🔍 Features Comparison

<div align="center">

| Feature | Code Editor Pro | Chatify |
|---------|:---------------:|:-------:|
| **Real-time Updates** | ✅ Live Preview | ✅ Socket.IO |
| **Authentication** | ❌ | ✅ JWT |
| **Database** | ❌ | ✅ MongoDB |
| **File Storage** | ✅ FireBase | ✅ Cloudinary |
| **Dark Mode** | ✅ | ✅ |
| **Responsive Design** | ✅ | ✅ |
| **Export Functionality** | ✅ .html Download | ❌ |
| **User Profiles** | ❌ | ✅ |
| **Multi-user Support** | ❌ | ✅ |
| **Code Editing** | ✅ Monaco Editor | ❌ |
| **Templates** | ✅ 4 Templates | ❌ |
| **Sound Mode** | ❌ | ✅ |
| **Email Integration** | ❌ | ✅ Resend |

</div>

---

## 📚 Documentation

### Project-Specific Documentation

Each project has its own comprehensive README with detailed setup instructions:

- **[Code Editor Pro Documentation](./my-code-editor/README.md)**
  - Installation guide
  - Feature overview
  - Template customization
  - Keyboard shortcuts
  - API reference

- **[Chatify Documentation](./chatify-app/README.md)**
  - Setup instructions
  - Authentication flow
  - Socket.IO implementation
  - API endpoints
  - Database schema

### Additional Resources

- 📖 [Contributing Guidelines](./CONTRIBUTING.md)
- 🐛 [Issue Templates](./.github/ISSUE_TEMPLATE/)
- 🔒 [Security Policy](./SECURITY.md)
- 📝 [Changelog](./CHANGELOG.md)

---

## 💻 Development

### Development Workflow

1. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes**
   - Write clean, documented code
   - Follow existing code style
   - Add tests if applicable

3. **Test your changes**
   ```bash
   # For Code Editor 
   cd my-code-editor
   npm test
   
   # For Chatify
   cd chatify-app
   npm test
   ```

4. **Commit with meaningful messages**
   ```bash
   git commit -m "feat: add new feature"
   git commit -m "fix: resolve bug in component"
   git commit -m "docs: update README"
   ```

5. **Push and create Pull Request**
   ```bash
   git push origin feature/your-feature-name
   ```

### Code Style Guidelines

- ✅ Use ES6+ features (arrow functions, destructuring, etc.)
- ✅ Follow React Hooks best practices
- ✅ Use meaningful variable and function names
- ✅ Add comments for complex logic
- ✅ Keep functions small and focused
- ✅ Use Prettier for consistent formatting

### Testing

```bash
# Run tests for Code Editor
cd my-code-editor
npm test

# Run tests with coverage
npm test -- --coverage

# Run tests for Chatify
cd chatify-app
npm test
```

---

## 🚀 Deployment

### Code Editor Pro Deployment

#### Vercel (Recommended)
```bash
cd my-code-editor
vercel --prod
```

#### Netlify
```bash
cd my-code-editor
npm run build
netlify deploy --prod --dir=build
```

### Chatify Deployment

#### Full-Stack Deployment (Railway/Render)

1. **Backend Deployment**
   ```bash
   cd chatify-app/backend
   # Configure environment variables on platform
   # Deploy using platform CLI or Git integration
   ```

2. **Frontend Deployment**
   ```bash
   cd chatify-app/frontend
   npm run build
   # Deploy build folder to Vercel/Netlify
   ```

#### Environment Variables for Production

Ensure all production environment variables are set:
- Set `NODE_ENV=production`
- Use secure random strings for `JWT_SECRET`
- Configure CORS for production domains
- Enable HTTPS for secure cookies

---

## 🤝 Contributing

We welcome contributions to both projects! Here's how you can help:

### Ways to Contribute

- 🐛 **Report Bugs** - Found an issue? Let us know!
- 💡 **Suggest Features** - Have ideas? We'd love to hear them!
- 📖 **Improve Documentation** - Help make our docs better
- 🔧 **Submit Pull Requests** - Code contributions are welcome!
- ⭐ **Star the Repository** - Show your support!

### Contribution Process

1. **Fork the repository**
2. **Create your feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

### Contribution Guidelines

- Follow the existing code style and conventions
- Write clear commit messages
- Add tests for new features
- Update documentation as needed
- Ensure all tests pass before submitting PR
- Be respectful and constructive in discussions

---

## 📊 Project Statistics

<div align="center">

### Repository Metrics

| Metric | Count |
|--------|-------|
| **Total Projects** | 2 |
| **Technologies Used** | 15+ |
| **Total Components** | 50+ |
| **API Endpoints** | 10+ |
| **Lines of Code** | 10,000+ |

### Technology Breakdown

```
React/JavaScript    ██████████████░░░░░░  70%
Node.js/Express     ████████░░░░░░░░░░░░  40%
CSS/Tailwind        ██████░░░░░░░░░░░░░░  30%
MongoDB/Database    ████░░░░░░░░░░░░░░░░  20%
Documentation       ████████░░░░░░░░░░░░  40%
```

</div>

---

## 🎯 Roadmap

### Short-term Goals (Q1 2025)

- [ ] Add TypeScript support to both projects
- [ ] Implement comprehensive test coverage (>80%)
- [ ] Add Docker configurations
- [ ] Create video tutorials
- [ ] Publish to npm (reusable components)

### Long-term Goals (2025)

- [ ] Add more projects to the collection
- [ ] Implement CI/CD pipelines
- [ ] Create mobile applications (React Native)
- [ ] Add internationalization (i18n)
- [ ] Build admin dashboards
- [ ] Integrate AI features

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Shubhadip Das

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

---

## 🙏 Acknowledgments

### Technologies & Libraries

- **[React](https://reactjs.org/)** - UI library
- **[Node.js](https://nodejs.org/)** - JavaScript runtime
- **[MongoDB](https://www.mongodb.com/)** - Database
- **[Socket.IO](https://socket.io/)** - Real-time engine
- **[Monaco Editor](https://microsoft.github.io/monaco-editor/)** - Code editor
- **[Tailwind CSS](https://tailwindcss.com/)** - CSS framework
- **[Cloudinary](https://cloudinary.com/)** - Image hosting
- **[Resend](https://resend.com/)** - Email service

### Inspiration & Learning

Special thanks to the open-source community and all the amazing developers whose work inspired these projects.

---

## 📞 Contact

<div align="center">

### 👨‍💻 Shubhadip Das

[![GitHub](https://img.shields.io/badge/GitHub-Shubhadip2005-181717?style=for-the-badge&logo=github)](https://github.com/Shubhadip2005)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-shubhadip--das-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/shubhadip-das-6040052a7)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shubhadipdas733@gmail.com)

---

### 💬 Get in Touch

| Platform | Link |
|----------|------|
| 🐙 **GitHub** | [@Shubhadip2005](https://github.com/Shubhadip2005) |
| 💼 **LinkedIn** | [Shubhadip Das](https://www.linkedin.com/in/shubhadip-das-6040052a7) |
| 📧 **Email** | shubhadipdas733@gmail.com |

</div>

---

## ⭐ Show Your Support

If you find these projects helpful, please consider:

- ⭐ **Starring the repository**
- 🐛 **Reporting bugs**
- 💡 **Suggesting new features**
- 🔀 **Contributing code**
- 📢 **Sharing with others**

---

<div align="center">

### 📈 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Shubhadip2005/codeeditor-chatify_Elevate-Lab_Web-Development&type=Date)](https://star-history.com/#Shubhadip2005/code-editor-chatify_Elevate-Lab_Web-Development&Date)

---

**Built with ❤️ and ☕ by [Shubhadip Das](https://github.com/Shubhadip2005)**

*Elevating web development, one project at a time*

---

⭐ **Don't forget to star this repository!** ⭐

[Report Bug](https://github.com/Shubhadip2005/codeeditor-chatify_Elevate-Lab_Web-Development/issues) • 
[Request Feature](https://github.com/Shubhadip2005/codeeditor-chatify_Elevate-Lab_Web-Development/issues) • 
[Contribute](https://github.com/Shubhadip2005/codeeditor-chatify_Elevate-Lab_Web-Development/pulls)

</div>
