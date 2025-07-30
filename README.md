# YouTube Shorts Remover

A simple Chrome extension that removes YouTube Shorts from your YouTube feed and video pages, helping you focus on regular YouTube content.

## Features

- **Feed Cleanup**: Removes YouTube Shorts sections from the main YouTube homepage
- **Video Page Cleanup**: Hides Shorts recommendations on video watch pages
- **Lightweight**: Uses CSS-only approach for minimal performance impact
- **Privacy-Focused**: No data collection or tracking

## Installation

### Manual Installation

1. **Download the extension files**

   - Clone or download this repository to your local machine

2. **Open Chrome Extensions**

   - Navigate to `chrome://extensions/` in your Chrome browser
   - Enable "Developer mode" in the top right corner

3. **Load the extension**

   - Click "Load unpacked" button
   - Select the folder containing the extension files (`youtube-shorts-remover`)

4. **Verify installation**
   - The extension should now appear in your extensions list
   - Visit YouTube to see the Shorts sections hidden

## How It Works

The extension uses CSS to hide YouTube Shorts content:

- **Main Feed**: Hides `.ytd-rich-section-renderer` elements (Shorts sections on homepage)
- **Video Pages**: Hides `.ytd-reel-shelf-renderer` elements (Shorts recommendations on video pages)

## File Structure

```
youtube-shorts-remover/
├── manifest.json          # Extension configuration
├── icon.png              # Extension icon
└── styles/
    ├── main.css          # Styles for YouTube homepage
    └── video.css         # Styles for video pages
```

## Compatibility

- **Browser**: Google Chrome (and Chromium-based browsers)
- **YouTube**: Works with the current YouTube interface
- **Manifest Version**: 3 (latest Chrome extension standard)

## Troubleshooting

### Extension not working?

1. Make sure the extension is enabled in `chrome://extensions/`
2. Refresh the YouTube page
3. Check if YouTube has updated their CSS classes (the extension may need updates)

### Want to temporarily see Shorts?

- Disable the extension in `chrome://extensions/` when you want to view Shorts content

## Contributing

Feel free to submit issues or pull requests if you find bugs or want to add features.

## License

This project is licensed under the MIT License.

**Note**: This extension is not affiliated with YouTube or Google. It's a third-party tool designed to improve your YouTube browsing experience.
