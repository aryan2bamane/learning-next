# Documented Next.js Learning Progress

## Table of Contents

- [Day 1 (Jan 04)](#day-1-jan-04)
  - [Chapter 1: Getting Started!](#chapter-1-getting-started)
  - [Chapter 2: CSS Styling!](#chapter-2-css-styling)
  - [Chapter 3: Optimizing Fonts and Images!](#chapter-3-optimizing-fonts-and-images)
  - [Chapter 4: Creating Layouts and Pages!](#chapter-4-creating-layouts-and-pages)
  - [Chapter 5: Navigating Between Pages!](#chapter-5-navigating-between-pages)
- [Day 2 (Jan 05)](#day-2-jan-05)
  - [Chapter 6: Setting Up My Database](#chapter-6-setting-up-my-database)

---

## Day 1 (Jan 04)

- ### Chapter 1: Getting Started!

  - **Introduction to Next.js**:  
    Next.js is a popular React-based framework for building server-side rendered (SSR) and statically generated websites and applications.

  - **Setting up a new project**:  
    I set up a new project using `npx create-next-app my-app` and ran it with `pnpm dev` to see the default Next.js page. I also explored the project structure and the different folders and files created by the CLI.

  - **Understanding the file system**:  
    I learned about the different types of files and folders in a Next.js project, including `pages`, `components`, `public`, and `styles`. I also learned about the `next.config.js` file and how it can be used to configure the project.

- ### Chapter 2: CSS Styling!

  - **CSS in Next.js**:  
    I learned about the different ways to add CSS to a Next.js project, including using CSS modules, global CSS, and Tailwind CSS.

  - **CSS Modules**:  
    I learned about CSS modules and how they can be used to write scoped CSS in a Next.js project. I also learned about the `module` attribute and how it can be used to import CSS modules.

  - **Global CSS**:  
    I learned about global CSS and how it can be used to write CSS that applies to the entire application. I also learned about the `global.css` file and how it can be used to define global CSS styles.

  - **Tailwind CSS**:  
    I learned about Tailwind CSS and how it can be used to write utility-first CSS in a Next.js project. I also learned about the `tailwind.config.js` file and how it can be used to configure Tailwind CSS.

- ### Chapter 3: Optimizing Fonts and Images!

  - **Font Optimization**:
    I learned about font optimization and how it can be used to reduce the size of fonts in a Next.js project. I also learned about the `font-display` property and how it can be used to control how fonts are displayed.
  - **Image Optimization**:
    I learned about image optimization and how it can be used to reduce the size of images in a Next.js project. I also learned about the `next/image` component and how it can be used to optimize images.
  - **Lazy Loading**:
    I learned about lazy loading and how it can be used to load images and other resources only when they are needed.

- ### Chapter 4: Creating Layouts and Pages!

  - **Creating the dashboard page**:
    I created a new page called `dashboard/page.tsx` and added some basic content to it. Also created more pages like `dashboard/customers/page.tsx` and `dashboard/invoices/page.tsx`.
  - **Partial Rendering**:
    I learned about partial rendering and how it can be used to render only a portion of a page.
  - **Root layout**:
    I learned about the root layout and how it can be used to define the layout for the entire application.

- ### Chapter 5: Navigating Between Pages!

  - **How to use the `next/link` component.**:
    I learned about the `next/link` component and how it can be used to navigate between pages in a Next.js project. I also learned about the `href` attribute and how it can be used to specify the URL of the page to navigate to.
  - **How to show an active link with the `usePathname()` hook.**:
    I learned about the `usePathname()` hook and how it can be used to get the current URL pathname. I also learned about how to use it to show an active link.
  - **How navigation works in Next.js.**:
    I learned about how navigation works in Next.js, including how the `next/link` component works and how the `usePathname()` hook can be used to get the current URL pathname.

## Day 2 (Jan 05)

- ### Chapter 6: Setting Up My Database!

  - **Pushing my project to GitHub**:
  - **Set up a Vercel account and link your GitHub repo for instant previews and deployments.**:
  - **Create and link your project to a Postgres database.**:
  - **Seed the database with initial data.**:

- ### Chapter 7: Fetching Data!

  - **Learned about some approaches to fetching data: APIs, ORMs, SQL, etc.**:
  - **How Server Components can help you access back-end resources more securely.**:
  - **What network waterfalls are.**:
  - **How to implement parallel data fetching using a JavaScript Pattern.**:

---

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.
