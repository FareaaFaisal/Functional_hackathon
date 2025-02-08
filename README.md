## Introduction

# FoodTuck - Q-Commerce Marketplace Website  

This project is a **Next.js** application, built as part of a **marketplace hackathon**.  
**FoodTuck** is a **Q-commerce (Quick Commerce) website** designed to facilitate seamless online food ordering with fast delivery. It provides an intuitive user experience, robust API integrations, and efficient performance optimizations for a smooth shopping experience.  

## Getting Started

To set up and run the project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/FareaaFaisal/day06.git
   cd day06
   ```

2. **Install dependencies:**

   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   # or
   bun install
   ```

3. **Start the development server:**

   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```

4. **Open the application:**

   Navigate to [http://localhost:3000](http://localhost:3000) in your browser to view the application.

You can start editing the main page by modifying `app/page.tsx`. The application supports hot-reloading, so your changes will reflect immediately.

## File Structure

The project follows a structured directory layout:


Functional Hackathon (FoodTuck)/
│── public/                                                # Static assets like images, fonts, and icons
│── src/                                                   # Source code directory
│   ├── app/                                               # Next.js app directory (routes and pages)
│   │   ├── layout.tsx                                     # Global layout component
│   │   ├── page.tsx                                       # Home page component
│   |   |── components/                                    # Reusable React components
|   |   |── About/page.tsx                                 # About Section
|   |   |── FAQ/page.tsx                                                       # FAQ Section
|   |   |── Blog |── [Blogpage].tsx                        # Blog Section
|   |   |        |── page.tsx 
|   |   |── Cart/page.tsx                                  # Cart Section
|   |   |── Checkout/page.tsx                              # Checkout Section
|   |   |── context/CartContex.tsx                         # Contex Section
|   |   |── menu/page.tsx                                  # Menu Section
|   |   |── error/page.tsx                                 # Error Section
|   |   |── Pages/page.tsx                                 # Pages Section
|   |   |── Shop |── [Slug] ── |──  page.tsx               # Shop Section
|   |   |        |             |──  ProductDetail.tsx 
|   |   |        |── page.tsx 
|   |   |── SignUp/page.tsx                                # Signup Section
|   |   |── team/page.tsx                                  # Team Section
|   |   |── studio / [[...tool]] / page.tsx                # Studio
|   |   |── payment-success/page.tsx                       # Payment-sucess Section
│   |   |── styles/                                        # Global styles and Tailwind configurations
│   |   |── lib/                                           # Utility functions and helper methods
│   ├── sanity/                                            # Sanity CMS configuration files
│── .eslintrc.json                                         # ESLint configuration
│── .gitignore                                             # Git ignore file
│── next.config.js                                         # Next.js configuration
│── tailwind.config.ts                                     # Tailwind CSS configuration
│── tsconfig.json                                          # TypeScript configuration
│── package.json                                           # Project dependencies and scripts
│── README.md                                              # Project documentation

## Reports

   Inside the Documentation folder

## Project Details:

📌 Day 1: Laying the Foundation for My MarketPlace
* Choosing the MarketPlace Type
* Defining the Business Goals
* Creating a Testing Schema


📌 Day 2: PLanning the Technical Foundation
* Defining Technical Requirements
* Designing System Architecture
* Planning API Requirements


📌 Day 3: API Integration & Data Migration
* Fetching the Data from API
* Adjusting Data Schema
* Data Migration


📌 Day 4: Building Dynamic Frontend Components
* Product Listing Grid
* Product Details Component
* Category Component
* Search Bar and Filter Search Component
* Cart Component
* Checkout Component
* Review And Ratings Component
* Pagination Component
* Header & Footer Component
* Notifications Feature
* FAQ & Help Center Component
* Social Media Sharing Feature
* Customer Reviews Component
* Advanced Search Component


📌 Day 5: Testing Error Handling and Backend Integration Refinement
Recorded all identified bugs in an Excel sheet.
Categorized bugs by severity (Critical, Major, Minor).


📌 Day 6: Deployment Preparation and Staging Environment Setup
* Testing types throuh Functional Testing , Performance Testing and Security Testing
* ( Test Case Report and Performance Testing are available in Documentation folder )


📌 Day 7: Live Deployment & Post Launch Practices
Set up a staging environment for testing.
Prepared for final deployment.
Conducted final regression testing.


## Steps For Deployment
* Connect GitHub to Vercel
* Go to Vercel Dashboard.
* Click "New Project".
* Select "Import Git Repository" and choose the repository.
* Vercel will detect it's a Next.js project and suggest optimal settings.
* Give environment variables from .enc.local file
* Click "Deploy" to start the deployment.

   
## Features

- **Next.js Framework:** Utilizes Next.js for server-side rendering and static site generation.
- **TypeScript Support:** Configured with TypeScript for static typing.
- **Tailwind CSS:** Integrated for utility-first CSS styling.
- **Sanity.io Integration:** Set up with Sanity for content management.
- **ESLint Configuration:** Includes ESLint for linting and code quality assurance.

## Dependencies

The project relies on the following major dependencies:

- **Next.js:** A React framework for production.
- **React:** A JavaScript library for building user interfaces.
- **Sanity:** A headless CMS for structured content.
- **Tailwind CSS:** A utility-first CSS framework.
- **TypeScript:** A superset of JavaScript for static typing.

For a complete list of dependencies, refer to the `package.json` file.

## Configuration

- **ESLint:** Configured via `.eslintrc.json` for linting rules.
- **Tailwind CSS:** Configured through `tailwind.config.ts` for customizing the design system.
- **Sanity CLI:** Configured with `sanity.cli.ts` and `sanity.config.ts` for managing Sanity projects.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your proposed changes. Ensure that your code adheres to the established coding standards and passes all linting checks.

📊 Performance Testing
Used Google Lighthouse for performance analysis.
JMeter for load testing (if applicable).
Reports stored in Documentation Folder.

🚀 How to Use This Repository
Navigate to the relevant folders for test documents, cases, or performance reports.
Review test cases in CSV format for execution details.
Check the deployment folder for setup guidelines.

📜 License
This project is licensed under the MIT License.
