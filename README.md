# Eagles High Academy

A modern, responsive school website built for **Eagles High Academy**, designed to showcase the school's identity, academic environment, campus, student life, admissions, and contact information.

The project focuses on creating a clean and welcoming digital experience for students, parents, staff, and prospective families while demonstrating modern frontend development practices.

---

## ✨ Features

### 🏫 School Showcase

* Attractive school landing page
* Hero section with school imagery
* About the school
* Academic programs
* School facilities and campus showcase
* Student life and activities
* School achievements
* Testimonials

### 🎓 Admissions

* Dedicated admissions section
* Admission information
* Application call-to-actions
* Application modal/form interface
* Application fee information
* Payment information interface
* Payment screenshot upload UI

> Payment processing and backend submission can be integrated in a future version.

### 🖼️ Campus Gallery

* Responsive campus image gallery
* Science laboratory
* Classrooms
* Library
* Sports facilities
* Computer laboratory
* Assembly hall
* Full-image viewing modal
* Image navigation with previous/next controls

### 👨‍🎓 Student Life

* Clubs and activities
* Sports
* Student activities
* Interactive activity cards
* Image previews

### 💬 Testimonials

* Responsive testimonial cards
* Automatic scrolling
* Desktop, tablet, and mobile layouts

### 📱 Responsive Design

The website is designed to work across:

* Desktop
* Laptop
* Tablet
* Mobile devices

### 🧭 Navigation

* Transparent navbar over the hero section
* Navbar changes to a white background when scrolling
* Responsive mobile navigation
* Mobile menu overlay
* Smooth visual transitions
* Call-to-action admission button

### 📞 Contact

* Contact page
* Contact information
* Contact form
* School location information
* Responsive contact layout

---

## 🛠️ Technologies Used

* **Next.js** — React framework for the application
* **React** — UI development
* **JavaScript** — Application logic
* **Tailwind CSS** — Styling and responsive design
* **React Icons** — Interface icons
* **Next.js Image** — Optimized image handling
* **Google Fonts** — Typography

### Fonts

The website uses:

* **Fraunces** — Display/headline typography
* **Inter** — Body and interface typography

---

## 🎨 Design Direction

Eagles High Academy uses a clean, modern school aesthetic that feels professional without appearing overly luxurious.

The design focuses on:

* Clean layouts
* Strong typography
* Spacious sections
* School photography
* Friendly but professional colors
* Clear calls to action
* Mobile-first responsiveness

The visual identity combines **navy blue, warm gold/accent tones, cream/paper backgrounds, and neutral text colors**.

---

## 📂 Project Structure

```text
eagles-high-academy/
│
├── public/
│   └── images/
│       ├── school-building.webp
│       ├── science-lab.webp
│       ├── classroom.webp
│       ├── library.webp
│       ├── sport.webp
│       ├── computer-lab.webp
│       └── assembly-hall.webp
│
├── src/
│   └── app/
│       ├── components/
│       │   ├── Navbar.js
│       │   ├── Footer.js
│       │   ├── Hero.js
│       │   ├── CampusShowcase.js
│       │   ├── Testimonials.js
│       │   ├── StudentLife.js
│       │   └── ...
│       │
│       ├── about/
│       ├── admissions/
│       ├── contact/
│       ├── news/
│       ├── layout.js
│       ├── page.js
│       └── globals.css
│
├── package.json
├── next.config.js
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone <repository-url>
```

### 2. Navigate into the project

```bash
cd eagles-high-academy
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

### 5. Open the website

Visit:

```text
http://localhost:3000
```

---

## 📜 Available Scripts

### Development

```bash
npm run dev
```

Starts the Next.js development server.

### Production Build

```bash
npm run build
```

Creates an optimized production build.

### Start Production Server

```bash
npm start
```

Runs the production build.

### Lint

```bash
npm run lint
```

Checks the project for linting issues.

---

## 🖼️ Images

School and campus images are stored inside:

```text
public/images/
```

Images are used throughout the website for:

* Hero sections
* Campus facilities
* Student life
* Gallery sections
* Contact page
* School showcase sections

The project uses Next.js image optimization where appropriate.

---

## 💳 Future Payment Integration

The project is currently designed so that payment functionality can be added without redesigning the entire website.

Possible future payment features include:

* Admission/application fees
* School fees
* Other school charges
* Payment confirmation
* Payment history

A payment provider such as **Paystack** or **Flutterwave** could be integrated if the project eventually requires online payments.

---

## 🔐 Future Backend Features

The current project primarily focuses on the frontend experience.

Future versions could introduce a backend and database for:

* Student accounts
* Parent accounts
* Staff accounts
* Online applications
* Application status
* Student records
* School results
* Fee management
* Payment records
* News management
* Events management
* Gallery management
* Admin dashboard

Authentication and database functionality can be added when required.

---

## 📱 Responsive Experience

The website has been designed to provide a consistent experience across different screen sizes.

### Desktop

Features include:

* Full navigation
* Multi-column layouts
* Large campus imagery
* Interactive galleries
* Spacious content sections

### Tablet

Layouts automatically adapt to smaller screen widths while maintaining readable typography and comfortable spacing.

### Mobile

The mobile experience includes:

* Collapsible navigation
* Mobile menu overlay
* Single-column layouts
* Touch-friendly controls
* Responsive image galleries
* Mobile-friendly forms and buttons

---

## 🎯 Project Goals

The main goals of Eagles High Academy are to:

1. Create a professional online presence for a school.
2. Clearly communicate the school's identity and values.
3. Showcase the campus and facilities.
4. Provide useful information to prospective students and parents.
5. Create a simple admissions experience.
6. Provide a responsive experience across devices.
7. Build a foundation that can later support school management features.
8. Demonstrate modern frontend development skills.

---

## 🔮 Future Improvements

Possible future improvements include:

* [ ] Online admission submission
* [ ] Database integration
* [ ] User authentication
* [ ] Student portal
* [ ] Parent portal
* [ ] Admin dashboard
* [ ] Online school-fee payment
* [ ] Payment verification
* [ ] Student results portal
* [ ] News management system
* [ ] Events management
* [ ] School announcements
* [ ] Email notifications
* [ ] Image/file storage
* [ ] Search functionality
* [ ] SEO improvements
* [ ] Accessibility improvements

---

## 📌 Project Status

**Status:** Active Development

Eagles High Academy is currently being developed as a personal school website project. The frontend experience is the primary focus, with additional backend, authentication, database, and payment functionality planned as the project evolves.

---

## 👨‍💻 Developer

Built as a personal web development project using modern React and Next.js technologies.

---

## 📄 License

This project is intended for personal/portfolio use.

If you plan to reuse, distribute, or commercially deploy the project, review and update the license and third-party asset requirements accordingly.
