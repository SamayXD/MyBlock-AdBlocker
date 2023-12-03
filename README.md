# MyBlock AdBlocker

This is a basic adblocking extension developed as part of a personal project to block common advertising domains in the browser.

## Getting Started

### Prerequisites

- Google Chrome browser

### Installation

1. Clone this repository or download the source code.
2. Open Google Chrome and navigate to `chrome://extensions`.
3. Enable Developer mode by toggling the switch in the top right corner.
4. Click on "Load unpacked" and select the directory where the extension files are located.

## Usage

Once the extension is installed and enabled, it will automatically block requests to known advertising domains listed in the defaultFilters array in `background.js`. Users can modify this list to add or remove specific domains they wish to block.

## Manifest Details

- **Name:** MyBlock AdBlocker
- **Version:** 1.0
- **Description:** A basic adblocking extension developed for personal use.
- **Permissions:** `webRequest`, `webRequestBlocking`, `<all_urls>`
- **Background Script:** `background.js`
- **Icons:** Included in various sizes under the `icons/` directory
- **Manifest Version:** 2

## Contributing

Contributions are welcome! Feel free to fork this repository, make changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
