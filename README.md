# Next.js 14 Blog

Next.js 14 powered blog. This project is a modern, fast, and responsive web application designed to deliver content beautifully and efficiently. Leveraging the latest features from Next.js 14, Tailwind CSS for styling, and Sanity.io as the Content Management System (CMS).

## Features

- **Next.js 14**: Utilizes the cutting-edge features of Next.js 14, including:
  - **Built-in Caching**: Enhances performance by caching pages and static assets at the edge, reducing load times significantly.
  - **Dynamic Routes**: Offers flexible routing mechanisms, allowing for the creation of SEO-friendly URLs based on our content from Sanity.
  - **Automatic Image Optimization**: Integrated image component that optimizes and serves images in modern formats for faster page loads.
  - **Middleware**: Leverages Next.js middleware for tasks like SEO enhancements and redirect handling directly on the server side.
  - **Incremental Static Regeneration (ISR)**: Updates static content without rebuilding the entire site, ensuring content is fresh while maintaining blazing fast speeds.
- **Shadcn UI Components**: Implements Shadcn, a robust UI framework for React, to create intuitive and beautiful user interfaces with minimal effort.
- **Tailwind CSS**: Employs Tailwind CSS for custom styling, enabling responsive design and a consistent look and feel across the blog.
- **Sanity CMS**: Integrates with Sanity.io to manage blog content seamlessly, providing a powerful and flexible backend for content operations.

## Getting Started

To get this project up and running on your local machine, follow these simple steps.

### Prerequisites

- Node.js (LTS version recommended)
- A Sanity.io account and project setup

### Installation

1. Clone the repository:

```bash
git clone https://github.com/hasham-qaiser/next14-blog
```

2. Navigate into the project directory:

```bash
cd next14-blog
```

3. Install dependencies:

```bash
npm install
```

4. Set up your environment variables by creating a `.env.local` file with your Sanity project credentials and other necessary configurations.

5. Start the development server:

```bash
npm run dev
```

The application should now be running on [http://localhost:3000](http://localhost:3000).

## License

This project is open-sourced under the MIT License. See the LICENSE file for more details.
