# App Download Website

A beautiful website to download your mobile app. Built with HTML, CSS, and ready for deployment on Vercel.

## Features

- 🎨 Modern, responsive design
- 📱 Mobile-friendly interface
- ⚡ Fast and lightweight
- 🔗 Direct APK download
- 🚀 Ready for Vercel deployment

## Local Development

```bash
npm install
npm start
```

The website will be available at `http://localhost:3000`

## Deployment on Vercel

1. **Initialize Git Repository** (if not already done):
```bash
git init
git add .
git commit -m "Initial commit"
```

2. **Push to GitHub**:
```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git branch -M main
git push -u origin main
```

3. **Deploy to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository
   - Click "Deploy"

## File Structure

```
├── index.html          # Main landing page
├── app-release.apk     # Your APK file
├── package.json        # Project configuration
├── vercel.json         # Vercel deployment config
├── .gitignore          # Git ignore rules
└── README.md          # This file
```

## Customization

Edit `index.html` to:
- Change the app name and description
- Modify colors in the `<style>` section
- Add additional features or information
- Update the version number

## Notes

- The APK file is served directly from the website
- Users can download the APK on any device
- The website is fully responsive and mobile-friendly

## License

MIT
