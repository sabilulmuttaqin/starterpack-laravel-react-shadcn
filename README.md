# Laravel + React + Tailwind + Shadcn UI Starter Kit

<p align="center">
  <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="300" alt="Laravel Logo">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-12-FF2D20?style=flat-square&logo=laravel" alt="Laravel">
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=flat-square&logo=react" alt="React">
  <img src="https://img.shields.io/badge/Tailwind-4-06B6D4?style=flat-square&logo=tailwindcss" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Inertia.js-2.0-9553E9?style=flat-square" alt="Inertia.js">
  <img src="https://img.shields.io/badge/Vite-7-646CFF?style=flat-square&logo=vite" alt="Vite">
</p>

A modern, clean starter kit for building fullstack applications with **Laravel**, **React**, **Inertia.js**, **Tailwind CSS**, and **Shadcn UI** components.

## ✨ Features

- ⚡ **Laravel 12** - Latest PHP framework
- ⚛️ **React 18** - Modern frontend library
- 🎨 **Tailwind CSS 4** - Utility-first CSS framework
- 🧩 **Shadcn UI** - Beautiful, accessible React components
- 🔗 **Inertia.js** - Modern monolith SPA architecture
- ⚡ **Vite** - Lightning fast build tool with HMR
- 🌙 **Dark Mode** - Built-in dark mode toggle
- 📱 **Responsive** - Mobile-first design

## 📦 Included Components

### Shadcn UI Components
- `Button` - Multiple variants (default, secondary, destructive, outline, ghost, link)
- `Card` - Card layout with header, content, footer
- `Input` - Form input component
- `DropdownMenu` - Interactive dropdown menus

### Utility Components
- `Checkbox`, `Modal`, `Dropdown`
- `InputLabel`, `InputError`, `TextInput`
- And more...

## 🚀 Quick Start

### Prerequisites
- PHP 8.2+
- Composer
- Node.js 18+
- MySQL/PostgreSQL/SQLite

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/starter-laravel-tailwind.git
cd starter-laravel-tailwind

# Install PHP dependencies
composer install

# Install Node.js dependencies
npm install

# Copy environment file
cp .env.example .env

# Generate application key
php artisan key:generate

# Configure your database in .env, then run migrations
php artisan migrate
```

### Development

Run both servers in separate terminals:

```bash
# Terminal 1 - Laravel server
php artisan serve

# Terminal 2 - Vite dev server
npm run dev
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser.

### Build for Production

```bash
npm run build
```

## 📁 Project Structure

```
├── app/
│   ├── Http/
│   │   ├── Controllers/
│   │   └── Middleware/
│   └── Models/
├── resources/
│   └── js/
│       ├── Components/
│       │   └── ui/          # Shadcn UI components
│       ├── Layouts/
│       └── Pages/
│           └── Welcome.jsx  # Landing page
├── routes/
│   └── web.php
└── ...
```

## 🎨 Adding More Shadcn Components

This starter uses [Shadcn UI](https://ui.shadcn.com/) components. To add more:

1. Visit [ui.shadcn.com](https://ui.shadcn.com/docs/components)
2. Copy the component code
3. Add to `resources/js/Components/ui/`
4. Import and use in your pages

## 📄 License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

---

**Happy Coding!** 🚀
