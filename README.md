# Simple Portfolio Site

A clean, easy-to-customize Jekyll portfolio website with forest green theme.

## 🎨 Easy Customization

### To Change Colors:
1. Open `assets/css/style.css`
2. Find the `:root` section at the top
3. Change the color values:
   ```css
   --bg-primary: #1e4620;        /* Main background color */
   --accent-primary: #b87333;    /* Links and highlights */
   ```

### To Change Content:
- **Homepage**: Edit `index.html`
- **Projects**: Edit `projects.html`
- **Blog**: Edit `blog.html`

### To Change Site Info:
- Open `_config.yml`
- Update your name, email, and description

## 📁 File Structure

```
simple-portfolio-site/
├── _config.yml              # Site configuration
├── _layouts/
│   └── default.html         # Main layout template
├── assets/
│   ├── css/
│   │   └── style.css        # ALL STYLES HERE - Easy to customize!
│   └── images/
│       └── bio-photo.jpg    # Add your photo here
├── index.html               # Homepage
├── projects.html            # Projects page
├── blog.html                # Blog page
└── Gemfile                  # Ruby dependencies
```

## 🚀 Setup

1. Copy your bio photo to `assets/images/bio-photo.jpg`
2. Update `_config.yml` with your info
3. Commit and push to GitHub
4. Enable GitHub Pages in your repo settings

## 🎯 Key Features

- ✅ Single CSS file for ALL styling
- ✅ Forest green color scheme with copper accents
- ✅ Fully responsive design
- ✅ Clean, minimal layout
- ✅ Easy to customize
- ✅ No complex theme dependencies

## 💡 Tips

- All colors are defined once at the top of `style.css` as CSS variables
- To adjust spacing, look for the "SPACING" and "RESPONSIVE DESIGN" sections in `style.css`
- The site uses system fonts, so no external font loading needed
