# Meditation Music Player

This repository contains a meditation music file and a web player interface.

## Files

- `meditation-music.mp3` - The meditation music file (26MB)
- `index.html` - A beautiful web player interface

## How to Host on GitHub Pages

1. Go to your repository settings on GitHub: https://github.com/gtrush03/chill/settings
2. Scroll down to the "Pages" section
3. Under "Source", select the `main` branch
4. Click "Save"
5. Your site will be available at: `https://gtrush03.github.io/chill/`

## Direct File Access

You can also access the MP3 file directly via the raw GitHub URL:
- `https://raw.githubusercontent.com/gtrush03/chill/main/meditation-music.mp3`

Or use it in your website with:
```html
<audio controls>
    <source src="https://raw.githubusercontent.com/gtrush03/chill/main/meditation-music.mp3" type="audio/mpeg">
</audio>
```

## Embedding in Your Website

Once GitHub Pages is enabled, you can embed the player in your website using an iframe:

```html
<iframe 
    src="https://gtrush03.github.io/chill/" 
    width="100%" 
    height="400" 
    frameborder="0">
</iframe>
```

