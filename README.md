# Web Assets

A collection of reusable static assets used across multiple web projects.

This repository serves as a centralized place to store images, icons, logos, and other static resources that are commonly used in different projects. Instead of uploading the same files repeatedly, assets can be referenced directly using CDN links.

---

## Purpose

The main goal of this repository is to keep commonly used assets in one place so they can be reused easily across different projects.

Benefits of this approach:

- Avoid duplicating assets in every project
- Keep projects lighter and cleaner
- Access assets from anywhere
- Faster loading through CDN
- Easier updates and maintenance

---

## Folder Structure

The repository can be organized into folders depending on the asset type.

Example structure:

assets
- images
  - backgrounds
  - illustrations
  - general
- icons
  - ui
  - social
- logos
- placeholders
- patterns

You can add more folders depending on your needs.

---

## CDN Usage

Files in this repository can be accessed using jsDelivr CDN.

CDN format:

https://cdn.jsdelivr.net/gh/USERNAME/REPOSITORY/PATH/FILE

Example:

https://cdn.jsdelivr.net/gh/USERNAME/REPOSITORY/images/logo.png

Replace `USERNAME` and `REPOSITORY` with your GitHub username and repository name.

---

## Usage Examples

### HTML

<img src="https://cdn.jsdelivr.net/gh/USERNAME/REPOSITORY/images/logo.png" alt="Logo">

### CSS

.logo {
  background-image: url("https://cdn.jsdelivr.net/gh/USERNAME/REPOSITORY/images/logo.png");
}

---

## Versioned CDN (Optional)

You can lock assets to a specific version using tags.

Example:

https://cdn.jsdelivr.net/gh/USERNAME/REPOSITORY@1.0/images/logo.png

This prevents future updates from affecting existing projects.

---

## Recommended Asset Types

Typical assets stored in this repository may include:

- Logos
- UI icons
- Social media icons
- Background images
- SVG graphics
- Placeholder images
- Patterns or textures

---

## Notes

- Keep assets optimized for web performance.
- Prefer SVG for icons and logos whenever possible.
- Organize files clearly to make them easy to reuse across projects.

---

## License

Assets in this repository are intended for personal and project usage.
