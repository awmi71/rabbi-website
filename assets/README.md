# Assets Folder

This folder contains all static assets for the portfolio website.

## Structure

```
assets/
├── images/
│   ├── README.md
│   └── profile.jpg (add your profile picture here)
└── README.md
```

## Usage

### Local Development
- Place your images in the `assets/images/` folder
- Reference them using relative paths: `assets/images/your-image.jpg`

### GitHub Deployment
When you push to GitHub, you can use GitHub's raw URLs:
1. Upload your images to this folder
2. Get the raw URL from GitHub
3. Use URLs like: `https://raw.githubusercontent.com/username/repo/main/assets/images/profile.jpg`

### Recommended Profile Image
- **Size:** 200x200 pixels (square)
- **Format:** JPG or PNG
- **File Name:** `profile.jpg`
- **Location:** `assets/images/profile.jpg`

## Adding Images

1. Place your image files in `assets/images/`
2. Update the HTML to reference your images
3. For GitHub deployment, commit and push your changes

## Current References

- Profile image: `assets/images/profile.jpg` (line 40 in index.html)
