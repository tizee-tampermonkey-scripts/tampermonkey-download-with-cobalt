# Download Media from Link (Cobalt API) UserScript

This Tampermonkey/Greasemonkey script enhances your browsing experience by adding a convenient context menu item to download media from various popular websites using the Cobalt API.  Instead of manually searching for download links or using external tools, you can now directly download media with a single right-click.

## Features

*   **Right-Click Context Menu:** Adds a "Download Media (Cobalt API)" option to the context menu (right-click menu) on supported websites.
*   **Cobalt API Integration:** Utilizes the Cobalt API (a popular media downloading service) to fetch and download media from links.
*   **Configurable API URL:** Allows you to easily configure the Cobalt API URL via a Tampermonkey menu option. You can switch between different Cobalt API instances.
*   **Wide Website Support:** Supports a wide range of popular media platforms, including:
    *   Bilibili
    *   Instagram (Posts, Reels)
    *   Twitter / X (Tweets, Spaces)
    *   Reddit
    *   SoundCloud
    *   Tumblr
    *   TikTok
    *   Vimeo
    *   YouTube (Videos, Shorts)
    *   VK
    *   Vine
    *   Streamable
    *   Pinterest
    *   Xiaohongshu
*   **Direct Download:** Opens the Cobalt API URL in a new tab to initiate the download.

## Installation

1.  Install a userscript manager like Tampermonkey (for Chrome, Safari, Firefox, Opera) or Greasemonkey (for Firefox).
2.  Copy the script content from this repository.
3.  In your userscript manager, create a new script.
4.  Paste the copied script content into the new script editor.
5.  Save the script.

## Usage

1.  Navigate to a supported website (e.g., YouTube, Twitter, Instagram).
2.  Right-click on the webpage.
3.  Select "Download Media (Cobalt API)" from the context menu.
4.  A new tab will open with the Cobalt API, initiating the download process.

### Configuring the Cobalt API URL

The script defaults to using `cobalt.tools` as the API URL.  To change this:

1.  Click on the Tampermonkey icon in your browser toolbar.
2.  Select "Download Media from Link (Cobalt API)" from the menu.
3.  Click on "Set Cobalt API URL".
4.  Enter the new Cobalt API URL in the prompt (e.g., `cobalt.tools` or a self-hosted instance address, remember no protocol).
5.  Click "OK". The script will now use the updated API URL.

## Permissions

The script requires the following permissions:

*   `GM_registerMenuCommand`:  Allows the script to add items to the Tampermonkey menu.
*   `GM_openInTab`: Allows the script to open the Cobalt API URL in a new tab.
*   `GM_getValue` and `GM_setValue`: Allows the script to store and retrieve the API URL configuration.

## License

This script is released under the MIT License.
