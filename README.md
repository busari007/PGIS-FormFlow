# PGIS FormFlow – Job Completion Form Application

A **Laravel + Tailwind CSS web application** built to streamline how **Preciousgate Integrated Services Limited (PGIS)** generates **job completion forms and PDFs**.

This application replaces the former manual process of editing Word documents and converting them to PDFs, providing a **faster, more reliable, and standardized workflow** for internal operations.

---

## Overview

PGIS FormFlow is designed for internal company use, enabling staff to:

* Fill structured job completion forms online
* Automatically generate **professional PDF documents**
* Maintain consistency across all job reports
* Reduce human error and repetitive manual work

The system focuses on **efficiency, accuracy, and simplicity**, making job documentation easier and more scalable as the company grows.

---

## Key Features

### Job Completion Forms

* Structured digital forms for recording completed jobs
* Eliminates manual document editing

### Automatic PDF Generation

* One‑click generation of clean, printable PDF files
* Consistent formatting across all job reports

### Internal Workflow Optimization

* Faster turnaround time for job documentation
* Reduced operational overhead

### Clean User Interface

* Built with **Tailwind CSS** for a modern, responsive UI
* Simple and intuitive form layout

---

## Use Case

This application is specifically built for:

**Preciousgate Integrated Services Limited**

It supports teams that regularly:

* Complete technical or service‑based jobs
* Require official job completion documentation
* Need standardized PDFs for record‑keeping or client delivery

---

## Tech Stack

* **Backend:** Laravel
* **Frontend:** Blade Templates, Tailwind CSS
* **PDF Generation:** Laravel PDF tooling
* **Database:** MySQL
* **Tooling:** Composer, NPM
* **Local Environment:** XAMPP

---

## Installation & Setup

Follow the steps below to run the project locally.

```bash
# Clone repository
git clone https://github.com/busari007/PGIS-FormFlow.git
cd PGIS-FormFlow

# Install XAMPP
# Ensure Apache and MySQL are running

# Install PHP & JS dependencies
composer install
npm install

# Configure environment
cp .env.example .env
php artisan key:generate
```

### Database Configuration

Update your `.env` file with your local database credentials:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=pgis_formflow
DB_USERNAME=root
DB_PASSWORD=
```

### Run Migrations & Seeders

```bash
php artisan migrate --seed
```

### Start Development Servers

```bash
php artisan serve
npm run dev
```

Visit the application at:

👉 **[http://127.0.0.1:8000](http://127.0.0.1:8000)**

---

## Project Status

* 🚧 Currently under active development
* 🌐 No public live link yet (internal tool)
* 🔐 Intended for controlled company use

---

## Notes

* This is an **internal business application**, not a public SaaS product
* Designed to scale with additional form types if needed
* PDF output ensures uniform documentation standards

---

## Author/Developer

**William Busari**
Software Developer

---

If you’d like to extend this project with authentication, role management, or cloud storage, the architecture supports easy expansion.
