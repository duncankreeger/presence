[README.md](https://github.com/user-attachments/files/24779888/README.md)
# Presence

A personal companion that helps you follow through on what matters.

## Deploy to GitHub Pages

1. Create a new repository on GitHub
2. Push this folder to the repository
3. Go to Settings > Pages
4. Set Source to "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. Click Save

Your app will be live at: `https://yourusername.github.io/repository-name`

## Add to iPhone Home Screen

1. Open the deployed URL in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Name it "Presence" and tap Add

The app will now appear on your home screen and open in full-screen mode.

## Security Note

The API key is currently baked into the code for convenience. For production:
1. Rotate your API key regularly at console.anthropic.com
2. Consider moving to a backend proxy that holds the key securely

## Customisation

Edit `SYSTEM_PROMPT.md` to change Presence's personality, then update the matching `PRESENCE_SYSTEM_PROMPT` constant in `index.html`.
