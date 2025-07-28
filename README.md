# Quiz Preview App

This is a simple static web app to preview a math quiz from a JSON file. Works on Netlify.

## 📦 How to Use

1. Place your `quiz.json` in the `public/` directory.
2. Edit `public/index.html` as needed.
3. Deploy to Netlify:

```bash
npm install -g netlify-cli
netlify deploy --dir=public --prod
