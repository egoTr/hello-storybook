# 🔢 STEPS
* [x] `(React)` Create Typescript project
* [x] `(React)` Clean project  
├── `/public/index.html` Minimum code with new **title**       
├── `/public` Keep `index.html`    
├── `/src/App.tsx` Minimum code    
├── `/src/index.tsx` Minimum code    
├── `/src` Keep `App.tsx`, `index.tsx` & `react-app-env.d.ts`      
├── `/package.json` (1) Uninstall **@testing** packages (x3), `@types/jest` & `web-vitals`; (2) Remove `test` script;     
* [x] `(Storybook)` Install & clean
* [x] `(Storybook) ` 📝`/.storybook/manager-head.html` Set custom favicon
* [x] `(GIT)` 📝`.gitignore` Ignore folder `/storybook-static`
* [x] `(PRODUCTION)`📝`/vercel.json` Configure for deploying on **Vercel**

&nbsp;

# 🚀 COMMANDS
🚀 Create `React` project with Typescript
```bash
npx create-react-app react-story --template typescript # 'react-story' is the project name
```

🚀 Install `Storybook`
```bash
npx storybook init
```
  
🚀 Preview `Storybook`
```bash
npm run storybook-run # This script is automatically created during Storybook installation
```