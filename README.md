# Sri Ambience - The City Pad

A modern, single-page website for Sri Ambience PG accommodation built with Next.js.

## Features

- 🏠 Single-page website with smooth scrolling navigation
- 🎨 Modern, responsive design with Tailwind CSS
- 📱 Mobile-friendly responsive layout
- ⚡ Fast and optimized with Next.js
- 🖼️ Image gallery with lightbox modal view
- 💰 Pricing section with 2, 3, and 4 sharing room options
- 📞 Complete contact information with address, phone, and email
- 🎯 Sections include:
  - Hero section with background image and call-to-action
  - About section with images
  - Gallery section with interactive image viewer
  - Pricing section with room options (2/3/4 sharing) and prices
  - Features/Why Choose Us
  - Amenities list
  - Contact form and detailed contact information
  - Footer

## Getting Started

### Prerequisites

- Node.js 18+ installed
- npm or yarn package manager

### Installation

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser to see the website.

### Build for Production

```bash
npm run build
npm start
```

## Project Structure

```
demo/
├── app/
│   ├── globals.css      # Global styles with Tailwind
│   ├── layout.tsx       # Root layout
│   └── page.tsx         # Main single page
├── package.json
├── tailwind.config.js
├── postcss.config.js
├── next.config.js
└── tsconfig.json
```

## Customization

- **Contact Information**: Update address, phone numbers, and email addresses in the `Contact` section of `app/page.tsx`
- **Pricing**: Modify room prices in the `Pricing` section
- **Images**: Replace Unsplash image URLs with your own images in:
  - Hero section background
  - About section
  - Gallery section
  - Pricing cards
- **Colors**: Modify colors in `tailwind.config.js`
- **Content**: Edit all text content directly in `app/page.tsx`

## Technologies Used

- Next.js 14
- React 18
- TypeScript
- Tailwind CSS

