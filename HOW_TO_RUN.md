# How to Run the Pracostech Website

## Prerequisites

Make sure you have Node.js installed (version 16 or higher):
- Download from: https://nodejs.org/
- Verify installation: `node --version` and `npm --version`

## Step-by-Step Instructions

### 1. Install Dependencies

Open your terminal in the project directory and run:

```bash
npm install
```

This will install all required packages including React, TypeScript, Vite, and other dependencies.

### 2. Start Development Server

After installation completes, run:

```bash
npm run dev
```

This will:
- Start the Vite development server
- Open your browser automatically at `http://localhost:3000`
- Enable hot module replacement (changes reflect instantly)

### 3. Build for Production

To create a production build:

```bash
npm run build
```

This creates an optimized build in the `dist` folder.

### 4. Preview Production Build

To preview the production build locally:

```bash
npm run preview
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Troubleshooting

### Port Already in Use
If port 3000 is already in use, Vite will automatically use the next available port (3001, 3002, etc.).

### Module Not Found Errors
If you see "Cannot find module" errors:
1. Make sure you ran `npm install`
2. Delete `node_modules` folder and `package-lock.json`
3. Run `npm install` again

### TypeScript Errors
Some TypeScript errors are expected until you create the missing component files. The code will still run, but you'll need to create:
- Component files (Button, Form, Accordion, etc.)
- CSS module files
- Helper files

## Project Structure

```
procostech/
├── src/
│   ├── pages/          # Page components
│   ├── components/     # Reusable components
│   ├── hooks/          # Custom React hooks
│   ├── constants/      # Constants and config
│   ├── types/          # TypeScript types
│   ├── App.tsx         # Main app component
│   └── main.tsx        # Entry point
├── index.html          # HTML template
├── vite.config.ts      # Vite configuration
├── tsconfig.json       # TypeScript configuration
└── package.json        # Dependencies
```

## Next Steps

1. **Create Missing Components**: You'll need to create UI components or use a library like shadcn/ui
2. **Add Styling**: Create CSS module files for each page
3. **Add Helpers**: Create helper functions and API schemas
4. **Customize**: Update content, colors, and branding

## Need Help?

- Check `ERRORS_FIXED.md` for information about remaining errors
- Review `PROFESSIONAL_IMPROVEMENTS.md` for code improvements made
- See `README.md` for project overview

