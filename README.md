# Certified GitOps Associate (CGOA) - Free Quiz

Challenge Your GitOps Knowledge.

- https://cgoa.purutuladhar.com

<img src='https://github.com/user-attachments/assets/14caa03e-9b21-4bff-ad1b-e5949264d574' width=720 />

## Local Development

1. Run development server
```bash
cd /Users/puru/next.js/quiz-app/cgoa-quiz
npx next dev
```
2. Browse https://localhost:3000

## Release

1. Build static files
```bash
cd /Users/puru/next.js/quiz-app/cgoa-quiz
npx next build
```

2. Upload static files to GitHub
3. Once uploaded, Cloudflare pages will auto-trigger the deploy.
4. Browse https://cgoa.purutuladhar.com
