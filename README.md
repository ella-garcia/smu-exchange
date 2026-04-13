# 🇸🇬 Singapore Places Explorer

An interactive web application to explore 194 amazing places across Singapore with YouTube video integration.

## Features

- 🔍 **Smart Search** - Search across place names, descriptions, and categories
- 🗺️ **Multiple Filters** - Filter by area, new places, categories, and video availability
- 🎥 **YouTube Integration** - Add YouTube videos/shorts for each location
- 💾 **Data Persistence** - All edits saved locally in browser
- 📱 **Responsive Design** - Works on mobile and desktop

## Deployment on Vercel

### Option 1: Using Vercel CLI

1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Navigate to the project folder:
   ```bash
   cd singapore-places-site
   ```

3. Deploy:
   ```bash
   vercel
   ```

4. Follow the prompts:
   - Set up and deploy? **Y**
   - Which scope? Select your account
   - Link to existing project? **N**
   - What's your project's name? `singapore-places-explorer` (or your choice)
   - In which directory is your code located? `./`
   - Want to override settings? **N**

5. Your site will be live at the provided URL!

### Option 2: Using Vercel Dashboard (No CLI needed)

1. Go to [vercel.com](https://vercel.com) and sign in/sign up

2. Click "Add New Project"

3. Choose "Import Git Repository" or "Upload Files"

4. If uploading files:
   - Drag and drop this entire folder
   - Or use the file browser to select all files

5. Vercel will auto-detect it as a static site

6. Click "Deploy"

7. Done! Your site will be live in seconds

### Option 3: GitHub + Vercel (Recommended for continuous deployment)

1. Create a new GitHub repository

2. Push this folder to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/singapore-places-explorer.git
   git push -u origin main
   ```

3. Go to [vercel.com](https://vercel.com)

4. Click "Add New Project"

5. Import your GitHub repository

6. Vercel will auto-configure everything

7. Click "Deploy"

8. Every push to `main` branch will auto-deploy!

## Usage

### Viewing Mode
- Browse all 194 Singapore places
- Filter by area, category, or search
- Watch embedded YouTube videos

### Edit Mode
- Click "🎬 Edit Mode" button
- Add YouTube videos by pasting:
  - Full YouTube URL: `https://youtube.com/shorts/VIDEO_ID`
  - Embed code: `<iframe src="...">`
  - Just the video ID: `VIDEO_ID`
- Click "💾 Save Video" to store
- All changes saved to browser localStorage

### Export Data
- Click "💾 Export Data" to download your YouTube mappings as JSON

## Technical Details

- **Framework**: Pure HTML/CSS/JavaScript (no dependencies)
- **Data Storage**: Browser localStorage
- **Video Embed**: YouTube privacy-enhanced mode (`youtube-nocookie.com`)
- **Hosting**: Static site (works on Vercel, Netlify, GitHub Pages, etc.)

## File Structure

```
singapore-places-site/
├── index.html       # Main application
├── vercel.json      # Vercel configuration
└── README.md        # This file
```

## Browser Compatibility

- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers

## Notes

- YouTube videos must have embedding enabled by their owners
- Data is stored locally - clearing browser data will reset
- Export your data regularly for backup

## License

Free to use and modify!

---

Built with ❤️ for exploring Singapore
