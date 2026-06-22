# Weather App

This is a simple static weather website built with HTML, CSS, and JavaScript.

## Run locally

### Option 1: Open directly
1. Open `index.html` in your browser.
2. The app should load and allow city lookups.

### Option 2: Use a local web server
From the project folder, run:

```powershell
python -m http.server 8000
```

Then open:

```
http://localhost:8000
```

If you want to let others on your local network access it, share your PC's local IP address and use:

```
http://YOUR_LOCAL_IP:8000
```

## Publish online

### GitHub Pages
1. Create a new GitHub repository.
2. Push `index.html`, `index.js`, and `style.css`.
3. In the repo settings, enable GitHub Pages from the `main` branch and root folder.
4. Share the generated URL.

### Netlify
1. Sign in to https://www.netlify.com/.
2. Drag the project folder or connect a GitHub repo.
3. Deploy the site and share the provided URL.

### Vercel
1. Sign in to https://vercel.com/.
2. Import the project from GitHub or deploy a new static site.
3. Share the live URL.

## Notes

- This app uses the OpenWeatherMap API.
- The current API key is in `index.js` for development only.
- For long-term public use, replace the API key with your own key.
