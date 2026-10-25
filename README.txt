# IT Support Portfolio — GitHub Pages

This rebuild uses three files:
- `index.html` — page content
- `style.css` — responsive dark navy / blue styling
- `script.js` — mobile navigation and automatic footer year

## Publish on GitHub Pages
1. Back up your current repository.
2. Upload/replace `index.html`, `style.css`, and `script.js` in the repository root.
3. Keep your existing images and resume PDF in the repository root with their current filenames.
4. Check **Settings → Pages** and make sure GitHub Pages publishes from the correct branch and folder.
5. Wait for deployment, then refresh the site with `Ctrl + F5`.

## Important: personal links
Before publishing, update the contact email and LinkedIn URL in `index.html`. The email currently uses a placeholder.
Make sure the resume filename is exactly `Solim_Mindamou_Resume.pdf`. If your actual PDF has a different filename, update both resume links in `index.html` to match it.

## Existing image filenames referenced
- `favicon.jpg`
- `slow performance.jpg`
- `Task-manager.jpg`
- `startup-apps.jpg`
- `windows explorer.jpg`
- `Free space on local disk (C).jpg`
- `check for updates.jpg`
- `windows update.jpg`

Image filenames are case-sensitive on GitHub Pages. Keep spaces, punctuation, capitalization, and file extensions exactly as they appear in your repository.

The Active Directory and Network Connectivity project sections are included. Their existing screenshots have not been guessed or renamed because their exact filenames were not available in the supplied code.


## Display two images horizontally under a subtitle
Use this structure inside a project card. The subtitle spans the full row, and the two images appear side by side on desktop/tablet; on small screens they stack vertically.

```html
<div class="project-image-group">
  <h4>Subtitle for these screenshots</h4>
  <div class="project-image-row">
    <figure>
      <figcaption>First screenshot</figcaption>
      <a href="image-one.jpg" target="_blank" rel="noopener noreferrer">
        <img src="image-one.jpg" alt="Description of first screenshot" loading="lazy">
      </a>
    </figure>
    <figure>
      <figcaption>Second screenshot</figcaption>
      <a href="image-two.jpg" target="_blank" rel="noopener noreferrer">
        <img src="image-two.jpg" alt="Description of second screenshot" loading="lazy">
      </a>
    </figure>
  </div>
</div>
```

Replace `image-one.jpg` and `image-two.jpg` with your exact existing image filenames.
