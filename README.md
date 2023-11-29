# skip-youtube-ads
Skip un-skippable YouTube pre-roll and mid-roll ads, no ad block, just a bookmark

## Introduction
This README provides instructions on how to install a custom JavaScript bookmark across various major web browsers. The bookmark contains a JavaScript snippet designed to skip video ads or jump to the end of the video if no skip button is available.

## JavaScript Bookmark
```javascript
javascript:(function(){var skipButton=document.querySelector('button.ytp-ad-skip-button-modern');if(skipButton){skipButton.click();}else{document.querySelector('video').currentTime=document.querySelector('video').duration;}})();
```

## Installation Steps

### Google Chrome
1. **Open Bookmark Manager**: Press `Ctrl+Shift+O` or navigate to the three dots in the top right corner > Bookmarks > Bookmark manager.
2. **Add Bookmark**: Right-click anywhere in the Bookmark Manager and select "Add new bookmark".
3. **Name and Paste**: Give the bookmark a name (e.g., "Ad Skipper") and paste the JavaScript code into the URL field.
4. **Save**: Click 'Save'.

### Mozilla Firefox
1. **Show Bookmarks Bar**: Press `Ctrl+Shift+B` to show the Bookmarks Toolbar.
2. **Add Bookmark**: Right-click on the Bookmarks Toolbar and select "New Bookmark".
3. **Name and Paste**: Enter a name for the bookmark (e.g., "Ad Skipper") and paste the JavaScript code into the Location field.
4. **Save**: Click 'Add'.

### Safari (macOS)
1. **Open Bookmarks**: Click 'Bookmarks' in the menu bar and select 'Edit Bookmarks'.
2. **Add Bookmark**: In the lower left corner, click the '+' icon and choose 'Add Bookmark'.
3. **Name and Paste**: Enter a name (e.g., "Ad Skipper") and paste the JavaScript code into the Address field.
4. **Save**: Click 'Add'.

### Microsoft Edge
1. **Open Favorites**: Press `Ctrl+Shift+O` or click on the three dots in the top right corner > Favorites > Manage favorites.
2. **Add Favorite**: Click on 'Add favorite' in the top bar.
3. **Name and Paste**: Enter a name for the favorite (e.g., "Ad Skipper") and paste the JavaScript code into the URL field.
4. **Save**: Click 'Done'.

### Opera
1. **Show Bookmarks Bar**: Press `Ctrl+Shift+B` to open the bookmarks page.
2. **Add Bookmark**: Click on the '+' icon at the bottom of the bookmarks page.
3. **Name and Paste**: Enter a name for the bookmark (e.g., "Ad Skipper") and paste the JavaScript code into the URL field.
4. **Save**: Click 'Done'.

## Usage
After adding the bookmark to your browser, simply click on it while on a page with a video to execute the script. It will either skip the ad or fast forward the video to the end.

## Disclaimer
This script is provided for educational purposes. Please respect the terms of service of the video platforms you are using.

---

Remember, the effectiveness of this bookmark might vary depending on the website's structure and any updates they make to their video player or ad system.