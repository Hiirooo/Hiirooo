# 🖥️ Retro Portfolio - Muhammad Rasyid Abdulah

> "Transforming caffeine into robust code and scalable solutions;"

![Retro Portfolio Preview](https://via.placeholder.com/1200x600?text=Retro+Portfolio+Preview)
*(Replace this link with a real screenshot of your website)*

## 📖 About
A unique, retro-styled developer portfolio inspired by the classic **Macintosh Aesthetic**. Built with modern technologies but designed to take you back to the monochrome era.

This project showcases my journey as a **Full Stack Web Developer**, featuring:
- **Interactive Windows**: Draggable and visually distinct "Mac" windows.
- **Global Localization**: Seamless switching between **Indonesian**, **English**, and **Japanese**.
- **System Info**: Creative "About Me" section styled as system specifications.
- **Retro Mail Client**: A functional contact form design.

## 🚀 Use the Site
Visit the live demo or run it locally to experience the retro interactions.

## 🛠️ Tech Stack
This project is built using the latest web technologies:

- **Framework**: [Next.js 16](https://nextjs.org/) (App Router)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Animation**: [Framer Motion](https://www.framer.com/motion/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Fonts**: `Press Start 2P` (Retro) & `Inter` (Modern)
- **State Management**: React Context API (for Localization)

## ✨ Features
- 🌐 **Multi-Language Support**: Complete translations for ID, EN, JP using a custom lightweight dictionary.
- 🎨 **Retro Design System**: Custom thick borders, heavy shadows, and monochrome palette defined in Tailwind v4 variables.
- 📱 **Fully Responsive**: Optimized for both Desktop (Grid Layout) and Mobile (Stacked Layout).
- 🔗 **Real Project Integration**: Direct links to live projects (Laravel, Next.js, aaPanel).

## 📦 Getting Started

### Prerequisites
- Node.js 18+ 
- npm / yarn / pnpm

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Hiirooo/retro-portfolio.git
   cd retro-portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 📂 Project Structure

```bash
├── app/
│   ├── layout.tsx      # Root layout with LanguageProvider
│   └── page.tsx        # Main page with Hero, Projects, About, Contact
├── components/
│   ├── ui/
│   │   ├── MacWindow.tsx    # Reusable Retro Window
│   │   ├── HeroSection.tsx  # Intro Section
│   │   ├── AboutSection.tsx # System Info Section
│   │   └── ContactSection.tsx # Mail Client Section
├── content/
│   └── translations.ts # Dictionary for ID/EN/JP
├── context/
│   └── LanguageContext.tsx # Global State
└── public/             # Static Assets
```

## 📬 Contact
Interested in collaborating? Reach out to me!

- **GitHub**: [Hiirooo](https://github.com/Hiirooo)
- **Email**: official.rasyidabdulah@gmail.com
- **WhatsApp**: [+62 831-7878-1472](https://wa.me/6283178781472)

---
*© 2026 Muhammad Rasyid Abdulah. Built with Next.js & Brutalism.*
