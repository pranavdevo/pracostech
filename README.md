# Pracostech - IT Services Website

A professional, modern React website for Pracostech, an IT services company specializing in digital transformation, cybersecurity, software development, and managed IT services.

## 🚀 Features

- **Modern React Architecture**: Built with React, TypeScript, and modern best practices
- **Responsive Design**: Fully responsive across all devices
- **SEO Optimized**: React Helmet for meta tags and SEO
- **Form Validation**: Zod schema validation for contact forms
- **Professional UI Components**: Custom component library with consistent styling
- **Contact Integration**: Contact form with mutation handling
- **Service Wizard**: Interactive service recommendation tool

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── Button.tsx
│   ├── Form.tsx
│   ├── Accordion.tsx
│   ├── ServiceCard.tsx
│   ├── ServiceWizard.tsx
│   └── GlobalContextProviders.tsx
├── pages/              # Page components
│   ├── Home/           # Landing page
│   ├── About/          # About page
│   └── Services/       # Services page
├── constants/          # Constants and configuration
│   └── contact.ts      # Contact information
├── hooks/              # Custom React hooks
│   ├── useDebounce.ts
│   └── useIsMobile.ts
├── helpers/            # Helper functions and utilities
│   ├── useContactMutation.ts
│   └── themeMode.ts
└── endpoints/          # API endpoint schemas
    └── contact_POST.schema.ts
```

## 📞 Contact Information

- **Email**: info@pracostech.com
- **Phone**: +91 9415935597
- **Founder**: Anjani Pandey (Founder & CEO)

## 🛠️ Technologies Used

- React
- TypeScript
- React Router
- React Helmet
- Lucide React (Icons)
- Sonner (Toast notifications)
- Zod (Schema validation)
- TanStack Query (Data fetching)

## 📝 Key Improvements Made

1. **Centralized Constants**: Contact information and company details are now in a single constants file for easy maintenance
2. **Type Safety**: Improved TypeScript types and interfaces
3. **Code Organization**: Better component structure and separation of concerns
4. **Professional Structure**: Clean, maintainable code following React best practices
5. **Accessibility**: Improved semantic HTML and ARIA attributes
6. **Performance**: Optimized component rendering and data structures

## 🎯 Getting Started

1. Install dependencies:
```bash
npm install
```

2. Start development server:
```bash
npm run dev
```

3. Build for production:
```bash
npm run build
```

## 📄 License

Copyright © 2024 Pracostech. All rights reserved.

