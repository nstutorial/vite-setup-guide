# Create Vite Application - Step by Step

## Prerequisites
- Node.js (version 18 or higher)
- npm or yarn or pnpm

## Step-by-Step Commands

### 1. Create a new Vite project
```bash
npm create vite@latest
```

### 2. Follow the prompts
- Enter your project name
- Select a framework (React, Vue, Svelte, etc.)
- Select a variant (TypeScript, JavaScript, etc.)

### 3. Navigate to your project directory
```bash
cd your-project-name
```

### 4. Install dependencies
```bash
npm install
```

### 5. Start the development server
```bash
npm run dev
```

### 6. Build for production
```bash
npm run build
```

### 7. Preview production build
```bash
npm run preview
```

## Alternative: Create with specific template

### React + TypeScript
```bash
npm create vite@latest my-app -- --template react-ts
cd my-app
npm install
npm run dev
```

### React + JavaScript
```bash
npm create vite@latest my-app -- --template react
cd my-app
npm install
npm run dev
```

### Vue + TypeScript
```bash
npm create vite@latest my-app -- --template vue-ts
cd my-app
npm install
npm run dev
```

## Using other package managers

### With Yarn
```bash
yarn create vite
```

### With PNPM
```bash
pnpm create vite
```

### With Bun
```bash
bun create vite
```
