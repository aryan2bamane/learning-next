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
  - [Chapter 7: Fetching Data!](#chapter-7-fetching-data)
  - [Chapter 8: Static and Dynamic Rendering!](#chapter-8-static-and-dynamic-rendering)
  - [Chapter 9: Streaming](#chapter-9-streaming)
  - [Chapter 10: Partial Prerendering!](#chapter-10-partial-prerendering)
  - [Chapter 11: Adding Search and Pagination](#chapter-11-adding-search-and-pagination)
  - [Chapter 12: Mutating data!](#chapter-12-mutating-data)
  - [Chapter 13: Handling Errors](#chapter-13-handling-errors)
  - [Chapter 14: Improving Accessibility](#chapter-14-improving-accessibility)
  - [Chapter 15: Adding Authentication](#chapter-15-adding-authentication)

---

## Day 1 (Jan 04)

### Chapter 1: Getting Started!

- **Introduction to Next.js**:  
  Next.js is a popular React-based framework for building server-side rendered (SSR) and statically generated websites and applications.

- **Setting up a new project**:  
  I set up a new project using `npx create-next-app my-app` and ran it with `pnpm dev` to see the default Next.js page. I also explored the project structure and the different folders and files created by the CLI.

- **Understanding the file system**:  
  I learned about the different types of files and folders in a Next.js project, including `pages`, `components`, `public`, and `styles`. I also learned about the `next.config.js` file and how it can be used to configure the project.

### Chapter 2: CSS Styling!

- **CSS in Next.js**:  
  I learned about the different ways to add CSS to a Next.js project, including using CSS modules, global CSS, and Tailwind CSS.

- **CSS Modules**:  
  I learned about CSS modules and how they can be used to write scoped CSS in a Next.js project. I also learned about the `module` attribute and how it can be used to import CSS modules.

- **Global CSS**:  
  I learned about global CSS and how it can be used to write CSS that applies to the entire application. I also learned about the `global.css` file and how it can be used to define global CSS styles.

- **Tailwind CSS**:  
  I learned about Tailwind CSS and how it can be used to write utility-first CSS in a Next.js project. I also learned about the `tailwind.config.js` file and how it can be used to configure Tailwind CSS.

### Chapter 3: Optimizing Fonts and Images!

- **Font Optimization**:
  I learned about font optimization and how it can be used to reduce the size of fonts in a Next.js project. I also learned about the `font-display` property and how it can be used to control how fonts are displayed.
- **Image Optimization**:
  I learned about image optimization and how it can be used to reduce the size of images in a Next.js project. I also learned about the `next/image` component and how it can be used to optimize images.
- **Lazy Loading**:
  I learned about lazy loading and how it can be used to load images and other resources only when they are needed.

### Chapter 4: Creating Layouts and Pages!

- **Creating the dashboard page**:
  I created a new page called `dashboard/page.tsx` and added some basic content to it. Also created more pages like `dashboard/customers/page.tsx` and `dashboard/invoices/page.tsx`.
- **Partial Rendering**:
  I learned about partial rendering and how it can be used to render only a portion of a page.
- **Root layout**:
  I learned about the root layout and how it can be used to define the layout for the entire application.

### Chapter 5: Navigating Between Pages!

- **How to use the `next/link` component.**:
  I learned about the `next/link` component and how it can be used to navigate between pages in a Next.js project. I also learned about the `href` attribute and how it can be used to specify the URL of the page to navigate to.
- **How to show an active link with the `usePathname()` hook.**:
  I learned about the `usePathname()` hook and how it can be used to get the current URL pathname. I also learned about how to use it to show an active link.
- **How navigation works in Next.js.**:
  I learned about how navigation works in Next.js, including how the `next/link` component works and how the `usePathname()` hook can be used to get the current URL pathname.

## Day 2 (Jan 05)

### Chapter 6: Setting Up My Database!

- **Pushing my project to GitHub**:
  I pushed my project to GitHub and created a new repository for it.
- **Set up a Vercel account and link your GitHub repo for instant previews and deployments.**:
  I set up a Vercel account and linked my GitHub repository to it. I also set up instant previews and deployments for my project.
- **Create and link your project to a Postgres database.**:
  I created a new Postgres database and linked it to my project using the documentation step-by-step.
- **Seed the database with initial data.**:
  I seeded the database with initial data using the automated process in Next-learn Documentation.

### Chapter 7: Fetching Data!

- **Learned about some approaches to fetching data: APIs, ORMs, SQL, etc.**:
  I learned about different approaches to fetching data, including APIs, ORMs, SQL, and more.
- **How Server Components can help you access back-end resources more securely.**:
  I learned about how Server Components can help me access back-end resources more securely.
- **What network waterfalls are.**:
  I learned about what network waterfalls are and how they can be used to improve the performance of my application.
- **How to implement parallel data fetching using a JavaScript Pattern.**:
  I learned about how to implement parallel data fetching using a JavaScript pattern.

### Chapter 8: Static and Dynamic Rendering!

- **Static Rendering**:
  I learned about static rendering and how it can be used to pre-render pages at build time. I also learned about the benefits of static rendering, including faster page loads and improved SEO.
- **Dynamic Rendering**:
  I learned about dynamic rendering and how it can be used to render pages at runtime. I also learned about the benefits of dynamic rendering, including the ability to handle complex logic and dynamic data.

### Chapter 9: Streaming!

- **What is Streaming?**:
  I learned about what streaming is and how it can be used to improve the performance of my application. I also learned about the benefits of streaming, including faster page loads even without required data and improved user experience with streaming.
- **How to use Next.js built-in streaming features.**:
  I learned about how to use Next.js built-in streaming features to improve the performance of my application.
  - There are two ways you implement streaming in Next.js:
  1. At the page level, with the loading.tsx file.
  2. For specific components, with `<Suspense>`.
- **Use of Suspense to stream**:
  I learned about how to use Suspense to stream only this component and immediately show the rest of the page's UI.
  - Learned to stream the whole page but that may lead to a longer loading time if one of the components has a slow data fetch.
  - Learned to stream only the component that has a slow data fetch and show the rest of the page's UI immediately.
  - Also learned create a staggered effect by streaming page sections. But _needs_ to create wrapper components.

### Chapter 10: Partial Prerendering!

- **What is Partial Prerendering?**:
  I learned about what partial prerendering is and how it can be used to improve the performance of my application. Next.js 14 introduced an experimental version of Partial Prerendering – a new rendering model that allows you to combine the benefits of static and dynamic rendering in the same route.

### Chapter 11: Adding Search and Pagination!

- **Learned to use the Next.js APIs: useSearchParams, usePathname, and useRouter.**:
  I learned about how to use the Next.js APIs: useSearchParams, usePathname, and useRouter to add search and pagination functionality to my application.
- **Implement search using URL search params.**:
  I learned about how to implement search using URL search params.
- **How Debouncing Works**:
  - **Trigger Event**: When an event that should be debounced (like a keystroke in the search box) occurs, a timer starts.
  - **Wait**: If a new event occurs before the timer expires, the timer is reset.
  - **Execution**: If the timer reaches the end of its countdown, the debounced function is executed.

### Chapter 12: Mutating Data

- **Server Actions**:

  - React Server Actions allow you to run asynchronous code directly on the server. They eliminate the need to create API endpoints to mutate your data.
  - Server Actions create a POST API endpoint. This is why you don't need to create API endpoints manually when using Server Actions. It is called automatically when the form is submitted.
  - Input elements with type="number" actually return a string, not a number!

    `COERCE = TO CHANGE FORCEFULLY! `

- **Use of Zod**:

  Zod, it is a TypeScript-first schema declaration and validation library. It is used to validate data in the server-side.

  `Good Practice`: Store monetary values **in cents** in your database to eliminate JavaScript floating-point errors and ensure greater accuracy.

- **Use of UUID**:

  UUIDs eliminate the risk of ID collision, are globally unique, and reduce the risk of enumeration attacks - making them ideal for large databases.

### Chapter 13: Handling Errors

- **Added `try-catch` block to handle errors**:
- **Used the special `error.tsx` file**:
  - This file is used to handle errors in Next.js.
- **Used the `notFound` function and `not-found.tsx` file**:
  - Used the `notFound` function to check whether the requested data does exist or not. If not, it will render the `not-found.tsx` file.

### Chapter 14: Improving Accessibility

- **Accessibility**:
  - Accessibility refers to designing and implementing web applications that everyone can use, including those with disabilities.
- **Server-Side validation**:
  - Server-side validation is a technique used to validate user input on the server-side.
  - It is used to prevent malicious input from reaching the client-side. It is also used to prevent the client-side from being overwhelmed with validation errors.

## Day 3 (Jan 06)

### Chapter 15: Adding Authentication

- **Authentication**:

  - Authentication is a key part of many web applications today. It's how a system checks if the user is who they say they are.

- **Authorization**:

  - Authorization is the next step. Once a user's identity is confirmed, authorization decides what parts of the application they are allowed to use.

- **NextAuth.js**:
  - NextAuth.js is a popular library for authentication in Next.js applications. It supports many authentication providers, including Google, GitHub, and more.
- **Step 1: Install NextAuth.js**:
  - Run the following command in your terminal: `pnpm i next-auth@beta`.
- **Step 2: Generate a secret key for our Application**:
  - Run the following command in your terminal: `npx auth secret`.
- **Step 3: Adding the pages option**:
  - Create an `auth.config.ts` file at the root of our project that exports an authConfig object.
  - It contains config options for NextAuth.js
- **Step 4: Add the logic to protect your routes**:
  - This will prevent users from accessing the dashboard pages unless they are logged in.
- **Step 5: Add the `middleware.ts` file**:

  - This file will be used to protect routes in our application. It will check if the user is logged in before allowing them to access the route.
  - The advantage of employing Middleware for this task is that the protected routes will not even start rendering until the Middleware verifies the authentication, enhancing both the security and performance of your application.

  ```bash
  import NextAuth from 'next-auth';
  import { authConfig } from './auth.config';

  export default NextAuth(authConfig).auth;

  export const config = {
    // https://nextjs.org/docs/app/building-your-application/routing/middleware#matcher
    matcher: ['/((?!api|_next/static|_next/image|.*\\.png$).*)'],
  };
  ```

- **Step 6: Password hashing**:

  - Password hashing is a technique used to protect passwords from being read or accessed by unauthorized parties.
  - Create a new file called `auth.ts` and add the following code to it:

  ```bash
  import NextAuth from 'next-auth';
  import { authConfig } from './auth.config';
  export const { auth, signIn, signOut } = NextAuth({
  ...authConfig,
  });
  ```

- **Step 7: Adding the Credentials provider**:

  - Add following code to `auth.ts`

  ```bash
  import NextAuth from 'next-auth';
  import { authConfig } from './auth.config';
  import Credentials from 'next-auth/providers/credentials';
  export const { auth, signIn, signOut } = NextAuth({
  ...authConfig,
  providers: [Credentials({})],
  });
  ```

- **Step 8: Adding the sign in functionality**:

  - Add the following code to `auth.ts`

  ```bash
  import NextAuth from 'next-auth';
  import { authConfig } from './auth.config';
  import Credentials from 'next-auth/providers/credentials';
  import { z } from 'zod';

  export const { auth, signIn, signOut } = NextAuth({
    ...authConfig,
    providers: [
      Credentials({
        async authorize(credentials) {
          const parsedCredentials = z
            .object({ email: z.string().email(), password: z.string().min(6) })
            .safeParse(credentials);
        },
      }),
    ],
  });

  ```

- **Step 9: Updating the login form**:
  - Connect the auth logic with your login form
- **Step 10: Adding the logout functionality**:

### Chapter 16: Adding Metadata

- **Metadata**:

  - Metadata means `data about data`.
  - Metadata plays a significant role in enhancing a webpage's SEO, making it more accessible and understandable for search engines and social media platforms.
  - **Types of metadata**: - There are various types of metadata, each serving a unique purpose.
    Some common types include:

  1. **_Title Metadata_**:

  - Responsible for the title of a webpage that is displayed on the browser tab. It's crucial for SEO as it helps search engines understand what the webpage is about.

    ```bash
    <title>Page Title</title>
    ```

  2. **_Description Metadata_**:

  - This metadata provides a brief overview of the webpage content and is often displayed in search engine results.

    ```bash
    <meta name="description" content="A brief description of the page content." />
    ```

  3. **_Keyword Metadata_**:

  - This metadata includes the keywords related to the webpage content, helping search engines index the page.

    ```bash
    <meta name="keywords" content="keyword1, keyword2, keyword3" />
    ```

  4. **_Open Graph Metadata_**:

  - This metadata enhances the way a webpage is represented when shared on social media platforms, providing information such as the title, description, and preview image.

    ```bash
    <meta property="og:title" content="Title Here" />
    <meta property="og:description" content="Description Here" />
    <meta property="og:image" content="image_url_here" />
    ```

  5. **_Favicon Metadata_**:

  - This metadata links the favicon (a small icon) to the webpage, displayed in the browser's address bar or tab.

    ```bash
    <link rel="icon" href="path/to/favicon.ico" />
    ```

  - Next.js has a Metadata API that can be used to define your application metadata. There are two ways you can add metadata to your application:

  1. **_Config-based_**: Export a static `metadata` object or a dynamic `generateMetadata` function in a `layout.js` or `page.js` file.

  2. **_File-based_**: Next.js has a range of special files that are specifically used for metadata purposes:

  - `favicon.ico`, `apple-icon.jpg`, and `icon.jpg`: Utilized for favicons and icons
  - `opengraph-image.jpg` and `twitter-image.jpg`: Employed for social media images
  - `robots.txt` : Provides instructions for search engine crawling
  - `sitemap.xml` : Offers information about the website's structure

**ImageResponse** :
The `ImageResponse` constructor allows you to generate dynamic images using JSX and CSS. This is useful for generating social media images such as Open Graph images, Twitter cards, and more.

- Use the `title.template` field in the `metadata object` to define a `template` for your page titles. This template can include the page title, and any other information you want to include.

**_The `%s` in the template will be replaced with the specific page title._**

---

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.
