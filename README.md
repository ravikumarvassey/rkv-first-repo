# Ravi Kumar Vassey — Personal Website

Live at: https://ravikumarvassey.com

## To deploy updates:

```bash
git add .
git commit -m "Update website"
git push origin main
```

## To add your profile photo:
1. Save your photo as `photo.jpg` in this folder
2. In `index.html`, find the `.photo-placeholder` div and replace it with:
   `<img src="photo.jpg" style="width:100%;height:100%;object-fit:cover;" alt="Ravi Kumar Vassey">`
3. Commit and push.
