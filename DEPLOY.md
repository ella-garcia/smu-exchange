# 🚀 Quick Deploy to Vercel

## Fastest Method (No Git, No CLI)

1. **Go to Vercel**: https://vercel.com/new

2. **Sign in** with GitHub, GitLab, or email

3. **Click "Browse"** in the file upload section

4. **Select all files** from the `singapore-places-site` folder:
   - index.html
   - vercel.json
   - README.md
   - .gitignore

5. **Click "Deploy"**

6. **Done!** Your site will be live in ~30 seconds

Your URL will be: `https://singapore-places-explorer-XXXX.vercel.app`

---

## Using Vercel CLI (If you prefer terminal)

```bash
# Install Vercel CLI
npm install -g vercel

# Navigate to project
cd singapore-places-site

# Deploy (first time)
vercel

# Follow prompts:
# - Link to existing project? N
# - Project name: singapore-places-explorer
# - Deploy now? Y

# Deploy updates later
vercel --prod
```

---

## Custom Domain (Optional)

1. Go to your project in Vercel dashboard
2. Click "Settings" → "Domains"
3. Add your domain (e.g., `singapore.yourname.com`)
4. Follow DNS instructions
5. SSL certificate auto-configured!

---

## Environment Notes

- ✅ No build process needed (static HTML)
- ✅ No environment variables needed
- ✅ Works instantly after deploy
- ✅ Free tier is generous (100GB bandwidth/month)
- ✅ Auto-SSL with custom domains

---

## Troubleshooting

**Problem**: Site not loading
- **Solution**: Clear browser cache, try incognito mode

**Problem**: Videos not showing
- **Solution**: Check if video owner allows embedding

**Problem**: Changes not saving
- **Solution**: localStorage works on live site, not on file://

---

Your site is ready to deploy! 🎉
