# Website Hosting & Customization Guide

## 🚀 Free Hosting Options

### 1. GitHub Pages (Recommended)
1. Create a new GitHub repository
2. Upload all files to the repository
3. Go to Settings → Pages
4. Select "Deploy from a branch" → "main" branch
5. Your site will be available at `https://username.github.io/repository-name`

### 2. Netlify
1. Create account at netlify.com
2. Drag and drop your project folder
3. Get instant URL like `https://random-name.netlify.app`

### 3. Vercel
1. Create account at vercel.com
2. Import your GitHub repository
3. Get instant deployment

### 4. Surge.sh
1. Install: `npm install -g surge`
2. Run: `surge` in your project directory
3. Follow prompts for free domain

## 🛠️ Customization Guide

### Changing Titles and Metadata
1. **Easy Method**: Edit `config.json` and update the titles, descriptions, and URLs
2. **Direct Method**: Edit the `<title>` and `<meta>` tags in each HTML file

### Changing Content
- **Page Headlines**: Edit the `<h1>` tags in each HTML file
- **Page Descriptions**: Edit the `<p>` tags under headlines
- **Company Name**: Replace "TechVista" throughout all files

### Changing Images/Thumbnails
- Replace placeholder URLs in HTML files
- Use services like:
  - Unsplash.com (free stock photos)
  - Placeholder.com (custom placeholder images)
  - Your own hosted images

### Styling Changes
Edit `styles.css` to change:
- **Colors**: Update color codes (e.g., `#667eea` to your preferred color)
- **Fonts**: Change `font-family` values
- **Layout**: Modify grid layouts and spacing

## 🌐 Making it Embeddable

The site is already configured to be embedded in other sites with:
- `X-Frame-Options: ALLOWALL` meta tag
- Responsive design for iframe compatibility

### To embed in another site:
```html
<iframe src="https://your-site-url.com" width="100%" height="600px" frameborder="0"></iframe>
```

## 📝 SEO Setup

1. **Update sitemap.xml**: Replace `your-site.github.io` with your actual domain
2. **Update robots.txt**: Replace the sitemap URL with your domain
3. **Submit to search engines**:
   - Google Search Console
   - Bing Webmaster Tools

## 🔧 Technical Features

- ✅ Responsive design (mobile-friendly)
- ✅ SEO optimized with meta tags
- ✅ Social media sharing (Open Graph + Twitter Cards)
- ✅ Sitemap for search engines
- ✅ Cross-origin embedding support
- ✅ Modern CSS with gradients and animations
- ✅ Placeholder images that work immediately

## 📱 Testing Your Site

Before going live:
1. Open each page in different browsers
2. Test on mobile devices
3. Check that all images load
4. Verify navigation works
5. Test embedding in an iframe

## 🎨 Customization Examples

### Change Color Scheme:
In `styles.css`, replace:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```
With your colors:
```css
background: linear-gradient(135deg, #ff6b6b 0%, #4ecdc4 100%);
```

### Change Company Name:
Find and replace "TechVista" in all HTML files with your company name.

### Add Your Logo:
Replace the text logo in the navigation with:
```html
<img src="your-logo.png" alt="Your Company" class="logo">
```

## 🆘 Troubleshooting

- **Images not loading**: Check that URLs are correct and accessible
- **Site not updating**: Clear browser cache or wait a few minutes for hosting service
- **Mobile layout issues**: Test CSS media queries
- **Embedding problems**: Ensure the hosting service allows iframe embedding

Your website is now ready to deploy and customize! 🎉