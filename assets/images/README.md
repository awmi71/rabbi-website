# Images Folder

This folder contains all the images used in the portfolio website.

## Recommended Images

### Profile Picture
- **File Name:** `profile.jpg` or `profile.png`
- **Size:** 200x200 pixels (square)
- **Format:** JPG or PNG
- **Location:** `assets/images/profile.jpg`

### Additional Images
You can add other images here and reference them in your HTML using relative paths like:
- `assets/images/your-image.jpg`
- `assets/images/your-image.png`

## GitHub Usage

When you upload this project to GitHub, you can:
1. Add your images to this folder
2. Use GitHub's raw image URLs in your HTML
3. Example: `https://raw.githubusercontent.com/username/repo/main/assets/images/profile.jpg`

## Current Usage

The profile image is currently referenced in `index.html` at line 35:
```html
<img src="https://via.placeholder.com/200x200/5D2A4A/FFFFFF?text=RH" alt="Rabbi Hasan">
```

Replace this with your actual image:
```html
<img src="assets/images/profile.jpg" alt="Rabbi Hasan">
```
