```
The requested module 'spinners-react' does not provide an export named 'SpinnerCircularFixed'
```

# Steps to recreate this issue

1. `npm create astro@latest` to set up basic Astro project
2. `npx astro add react` to add React (not sure if this is necessary)
3. `npm install spinners-react` to install package
4. `npm start` or `npm run dev` to see error
