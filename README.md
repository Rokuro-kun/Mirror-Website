# Mirror Website

This is a mirrored website extracted from a Site123 archive.

## How to View the Website

The website is now fully functional and can be viewed locally. All external CDN resources have been converted to local paths.

### Option 1: Using Python HTTP Server (Recommended)

1. Navigate to the repository directory
2. Start a local HTTP server:
   ```bash
   python3 -m http.server 8080
   ```
3. Open your browser and visit:
   ```
   http://localhost:8080/698ac19c6667a.site123.me/index.html
   ```

### Option 2: Using Node.js HTTP Server

1. Install http-server globally (if not already installed):
   ```bash
   npm install -g http-server
   ```
2. Navigate to the repository directory and run:
   ```bash
   http-server -p 8080
   ```
3. Open your browser and visit:
   ```
   http://localhost:8080/698ac19c6667a.site123.me/index.html
   ```

### Option 3: Direct File Access

You can also open the file directly in your browser, but some features may not work due to browser security restrictions:
```
file:///path/to/698ac19c6667a.site123.me/index.html
```

## Structure

- `698ac19c6667a.site123.me/` - Main website directory containing the index.html
- `cdn-cms-s-8-4.f-static.net/` - CSS, JavaScript, and other assets
- `files.cdn-files-a.com/` - Uploaded images and files
- `fonts.gstatic.com/` - Font files
- `images.cdn-files-a.com/` - SVG icons and images
- Other directories contain additional resources

## About

This website was created using Site123 and has been exported as a static HTML site with all assets localized for offline viewing.
