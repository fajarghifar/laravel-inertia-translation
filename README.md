## 🌐 Laravel Inertia Translation

A simple Laravel 10 project demonstrating how to implement **multi-language support** with **Inertia.js** and **Vue 3**.

This project showcases how to:

* Store selected language in session
* Set locale via middleware
* Share translations globally with Inertia
* Use a small JS helper to access translations in Vue

---

## 🧩 Features

* 🌍 Language selector component
* 🧠 Locale setting through middleware
* 📦 Translation caching
* 🔄 Dynamic language switching with Inertia
* ⚙️ Translation helper for Vue

---

## 🚀 Installation Guide

### 1. Clone the Repository

```bash
git clone https://github.com/fajarghifar/laravel-inertia-translation.git
cd laravel-inertia-translation
```

### 2. Install Dependencies

```bash
composer install
npm install
```

### 3. Configure Environment

Copy `.env` and generate the app key:

```bash
cp .env.example .env
php artisan key:generate
```

### 4. Set Up the Database

Edit your `.env` file and set your database credentials, then run:

```bash
php artisan migrate
```

### 5. Build Frontend Assets

```bash
npm run build
```

Or for development:

```bash
npm run dev
```

### 6. Start the Development Server

```bash
php artisan serve
```

---

## 🧪 Usage

Visit `http://localhost:8000`, then use the language selector on the top bar or dashboard. Your chosen language will be stored in the session and used across pages.

You can find translation files in:

```
resources/lang/
```

Example languages:

* `en.json`
* `id.json`

---

## 🛠 Tech Stack

* Laravel 10
* Inertia.js
* Vue 3
* Vite
* Tailwind CSS

---

## 💡 Contributing

Feel free to fork the repository, create a branch, and submit a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> Created by [Fajar Ghifari Nugroho](https://github.com/fajarghifar)
