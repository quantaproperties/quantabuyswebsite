# Quanta Properties - Vercel Deployment Guide

## Your Website is Ready to Deploy! 🚀

Your Quanta Properties website is fully prepared and ready to go live on your custom domain **www.quantabuys.com**.

---

## Step-by-Step Deployment Instructions

### Step 1: Create a Free Vercel Account
1. Go to **https://vercel.com/signup**
2. Sign up using:
   - GitHub account (recommended), OR
   - Email address
3. Complete the verification process

### Step 2: Upload Your Website Files
**Option A: Using Git (Recommended)**
1. Create a GitHub repository (if using GitHub signup)
2. Upload these files to your repository:
   - `index.html`
   - `css/` folder
   - `js/` folder
   - `images/` folder
   - `vercel.json`

3. In Vercel dashboard, click **"New Project"**
4. Select your GitHub repository
5. Click **"Deploy"** - Vercel will automatically deploy it!

**Option B: Using Vercel CLI (Alternative)**
1. Download and install Vercel CLI: https://vercel.com/docs/cli
2. In your terminal, navigate to the folder containing your website files
3. Run: `vercel`
4. Follow the prompts to deploy

**Option C: Drag & Drop (Easiest)**
1. Go to https://vercel.com/new
2. Scroll down to "Import from Git" section
3. Or use the "Hobby" plan and drag-and-drop your files

### Step 3: Connect Your Custom Domain
1. After deployment, go to your Vercel project settings
2. Click **"Domains"** in the left sidebar
3. Click **"Add Domain"**
4. Enter: **quantabuys.com**
5. Choose one of these options:

**Option A: Buy Domain Through Vercel**
- Click "Buy Domain"
- Complete the purchase
- Domain is automatically configured

**Option B: Use Existing Domain**
- If you already own quantabuys.com:
- Copy the nameservers Vercel provides
- Log into your domain registrar (GoDaddy, Namecheap, etc.)
- Update your domain's nameservers to Vercel's nameservers
- Wait 24-48 hours for DNS propagation

### Step 4: Verify Your Domain
- Vercel will show a verification status
- Once verified (usually within minutes), your site is live!
- Visit **https://www.quantabuys.com** to see your website

---

## What's Included in Your Deployment Package

```
quanta-vercel/
├── index.html              # Main website page
├── css/
│   └── styles.css         # All styling
├── js/
│   └── script.js          # Interactive features
├── images/
│   ├── hero-bg.jpg        # Hero section background
│   └── property-showcase.jpg  # Property showcase image
├── vercel.json            # Vercel configuration
└── DEPLOYMENT_INSTRUCTIONS.md  # This file
```

---

## Website Features

✅ **Fully Responsive** - Works on mobile, tablet, and desktop
✅ **Fast Loading** - Optimized images and CSS
✅ **Professional Design** - Modern, clean aesthetic
✅ **SEO Friendly** - Proper HTML structure
✅ **Contact Information** - Phone: (470) 485-5239 | Email: quantapropertiesintl@gmail.com
✅ **Interactive Elements** - Smooth scrolling, hover effects, mobile menu

---

## After Deployment

### Monitor Your Site
- Vercel provides free analytics
- Track page views and performance
- Monitor uptime and errors

### Make Updates
- Edit files in your GitHub repository
- Vercel automatically redeploys on every push
- Changes go live within seconds

### Custom Email
- Your email (quantapropertiesintl@gmail.com) is already on the website
- Set up email forwarding through your domain registrar if needed

---

## Troubleshooting

### Domain Not Working
- **Wait 24-48 hours** for DNS propagation
- Check that nameservers are correctly updated
- Verify domain in Vercel dashboard shows "Verified"

### Website Shows 404 Error
- Ensure `index.html` is in the root directory
- Check that all file paths in index.html are correct
- Verify `vercel.json` is present

### Images Not Loading
- Check that the `images/` folder is uploaded
- Verify image file names match those in index.html
- Clear browser cache (Ctrl+Shift+Delete or Cmd+Shift+Delete)

### Slow Loading
- Images are optimized, but you can compress further if needed
- Vercel provides CDN acceleration automatically
- Check Vercel Analytics for performance insights

---

## Support Resources

- **Vercel Docs:** https://vercel.com/docs
- **Domain Setup Help:** https://vercel.com/docs/concepts/projects/domains
- **CLI Documentation:** https://vercel.com/docs/cli

---

## Next Steps (Optional Enhancements)

1. **Add Contact Form** - Collect inquiries from potential clients
2. **Add Blog Section** - Share market insights and tips
3. **Add Property Listings** - Showcase available properties
4. **Add Video** - Feature property tours or testimonials
5. **Add Analytics** - Track visitor behavior and conversions

---

## Questions?

If you need help with deployment, feel free to reach out. Your website is production-ready and will serve your business well!

**Good luck with Quanta Properties! 🏠**
