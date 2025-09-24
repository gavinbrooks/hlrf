# H-LRF Hugo Site

This is the Hugo site structure for h-lrf.org, mapped from the original WordPress site.

## Site Structure

```
hlrf/
├── hugo.toml              # Main configuration file
├── content/               # All content files
│   ├── _index.md         # Homepage
│   ├── about.md          # About page
│   └── conferences/      # Conference pages
│       ├── _index.md     # Previous Conferences index
│       ├── 2024.md       # 2024 Conference
│       ├── 2023.md       # 2023 Conference
│       ├── 2022.md       # 2022 Conference
│       ├── 2021.md       # 2021 Conference
│       └── 2020.md       # 2020 Conference
├── static/               # Static assets
│   └── images/          # Images folder
└── README.md            # This file
```

## Navigation Menu (from original site)

- Home
- About  
- 2024 Conference
- Previous Conferences
  - 2020 Conference
  - 2021 Conference
  - 2022 Conference
  - 2023 Conference

## Next Steps

### 1. Install Hugo
```bash
# On macOS with Homebrew
brew install hugo

# Or download from https://gohugo.io/installation/
```

### 2. Choose a Theme
Some good options:
- **Ananke** (simple, clean): `git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke themes/ananke`
- **Mainroad** (blog-like): `git submodule add https://github.com/Vimux/Mainroad themes/mainroad`
- **Hugo-coder** (minimal): `git submodule add https://github.com/luizdepra/hugo-coder themes/hugo-coder`

Then add to `hugo.toml`:
```toml
theme = "ananke"  # or your chosen theme
```

### 3. Test Locally
```bash
cd /Users/gavin/Desktop/hlrf
hugo server -D
# Visit http://localhost:1313
```

### 4. Build for Production
```bash
hugo
# Files will be in ./public/ folder
```

### 5. Deploy Options

#### Option A: GitHub Pages (Free)
1. Create GitHub repo
2. Push this content
3. Add GitHub Actions for auto-deploy
4. Point h-lrf.org DNS to GitHub Pages

#### Option B: Upload to Current Hosting
1. Run `hugo` to generate site
2. Upload contents of `public/` folder to HostGator/Katamari
3. Point h-lrf.org to that hosting

## Images to Download

The following images are referenced and should be downloaded to `/static/images/`:

1. `hiroshima-university.jpeg` - Main banner image
   - Source: https://i0.wp.com/h-lrf.org/wp-content/uploads/2022/06/hiroshima-university.jpeg
2. `hiroshima-2.jpg` - Conference page banner
   - Source: https://i0.wp.com/h-lrf.org/wp-content/uploads/2022/06/hiroshima-2.jpg

## Content Updates Needed

1. **Replace banner images** with your new banner image
2. **Update 2022, 2023 conference pages** with actual content
3. **Add contact information** and forms
4. **Update organizing committee** details if needed
5. **Add your flyins functionality** (CSS/JS animations)

## Flyins Implementation

The original site has "flyins" functionality. This can be implemented with:
- CSS animations in your theme
- Custom CSS in `static/css/custom.css`
- JavaScript if needed in `static/js/custom.js`

Let me know if you need help with any of these steps!
