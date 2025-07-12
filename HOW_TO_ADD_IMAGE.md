# How to Add Your Profile Image

## 📸 Step-by-Step Instructions

### 1. Prepare Your Image
- Use a square image (recommended: 400x400 pixels or larger)
- Supported formats: JPG, PNG, WebP
- Make sure it's a professional headshot or profile photo

### 2. Add Your Image File
1. Place your image file in the `images` folder
2. Rename your image file to something like:
   - `profile.jpg`
   - `kratos.jpg`
   - `avatar.png`
   - Or any name you prefer

### 3. Update the HTML
In `index.html`, find this line (around line 72):
```html
<img src="images/your-image.jpg" alt="Kratos" class="profile-image">
```

Change `your-image.jpg` to your actual image filename:
```html
<img src="images/profile.jpg" alt="Kratos" class="profile-image">
```

### 4. Example
If your image is named `kratos-profile.png`, update the line to:
```html
<img src="images/kratos-profile.png" alt="Kratos" class="profile-image">
```

## 🎯 Image Requirements
- **Size**: Square format (1:1 ratio)
- **Resolution**: At least 400x400 pixels
- **Format**: JPG, PNG, or WebP
- **Style**: Professional headshot or profile photo
- **Background**: Clean background works best

## 🔧 Troubleshooting
- If your image doesn't appear, check the file path
- Make sure the image file is actually in the `images` folder
- Verify the filename matches exactly (case-sensitive)
- The fallback icon will show if the image fails to load

## 📁 File Structure
Your folder should look like this:
```
kratos portfolio/
├── index.html
├── styles.css
├── script.js
├── README.md
└── images/
    └── your-image.jpg  ← Your image goes here
```

That's it! Your image will now appear in the profile card with the same professional styling as the rest of the portfolio. 