# Deployment Guide for astewaykebede.com

## 🚀 Quick Start - Deploy Today!

### Step 1: Initialize Git Repository
```bash
cd /Users/aayykayy/Documents/AI/astewaykebede.com
git init
git add .
git commit -m "Initial portfolio website setup"
```

### Step 2: Create GitHub Repository
1. Go to [GitHub.com](https://github.com)
2. Click "New repository"
3. Name it: `astewaykebede.com` or `portfolio`
4. Make it public
5. Don't initialize with README (we already have one)

### Step 3: Connect and Push
```bash
git remote add origin https://github.com/kasteway/astewaykebede.com.git
git branch -M main
git push -u origin main
```

### Step 4: Deploy with Vercel (Recommended)

1. **Go to [vercel.com](https://vercel.com)**
2. **Sign up with GitHub**
3. **Click "New Project"**
4. **Import your repository**
5. **Configure deployment:**
   - Framework Preset: Other
   - Build Command: (leave empty)
   - Output Directory: (leave empty)
6. **Click "Deploy"**

### Step 5: Add Custom Domain

1. **In Vercel dashboard, go to your project**
2. **Click "Settings" → "Domains"**
3. **Add domain: `astewaykebede.com`**
4. **Add www subdomain: `www.astewaykebede.com`**
5. **Update DNS records at NameHero:**
   - Add CNAME record: `www` → `cname.vercel-dns.com`
   - Add A record: `@` → `76.76.19.61` (Vercel's IP)

### Alternative: Deploy with Netlify

1. **Go to [netlify.com](https://netlify.com)**
2. **Sign up with GitHub**
3. **Click "New site from Git"**
4. **Choose GitHub and select your repository**
5. **Deploy settings:**
   - Build command: (leave empty)
   - Publish directory: (leave empty)
6. **Click "Deploy site"**
7. **Add custom domain in Site settings**

## 🔧 DNS Configuration at NameHero

### For Vercel:
```
Type: A
Name: @
Value: 76.76.19.61

Type: CNAME  
Name: www
Value: cname.vercel-dns.com
```

### For Netlify:
```
Type: A
Name: @
Value: 75.2.60.5

Type: CNAME
Name: www  
Value: your-site-name.netlify.app
```

## ✅ Post-Deployment Checklist

- [ ] Website loads at astewaykebede.com
- [ ] HTTPS certificate is active
- [ ] Mobile responsive design works
- [ ] All links work correctly
- [ ] Contact form/links are functional
- [ ] Google Analytics is set up (optional)
- [ ] SEO meta tags are optimized

## 🎨 Customization After Deployment

1. **Update personal information** in `index.html`
2. **Add your actual photo** (replace placeholder)
3. **Update project links** to your real GitHub repos
4. **Add real contact information**
5. **Customize colors** in the CSS
6. **Add more projects** as you build them

## 📱 Testing Your Site

- Test on desktop (Chrome, Firefox, Safari)
- Test on mobile devices
- Test on different screen sizes
- Check loading speed with [PageSpeed Insights](https://pagespeed.web.dev/)
- Validate HTML with [W3C Validator](https://validator.w3.org/)

## 🚨 Troubleshooting

### Domain not working?
- Wait 24-48 hours for DNS propagation
- Check DNS records are correct
- Clear browser cache

### Site not updating?
- Check if auto-deployment is enabled
- Manually trigger deployment
- Check build logs for errors

### SSL certificate issues?
- Vercel/Netlify handle this automatically
- Wait a few minutes after adding domain
- Check domain configuration

## 📞 Need Help?

- Vercel Docs: https://vercel.com/docs
- Netlify Docs: https://docs.netlify.com
- GitHub Pages: https://pages.github.com

Your portfolio should be live within 15 minutes! 🎉
