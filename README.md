# Coursera Transcript to Right Side

A userscript that moves the Coursera video transcript to the right side of the video player, making it easier to follow along while watching lectures.

## Features

- **Side-by-side layout**: Moves the transcript panel to the right side of the video
- **Auto-scroll**: Automatically scrolls to the current sentence when the video is playing
- **Pause-friendly**: When video is paused, you can freely scroll through the transcript
- **Clean UI**: Styled transcript panel with shadow and rounded corners

## Screenshot

![Screenshot](screenshot.png)

## Installation

1. Install a userscript manager extension:
   - [Tampermonkey](https://www.tampermonkey.net/) (Chrome, Firefox, Safari, Edge)
   - [Violentmonkey](https://violentmonkey.github.io/) (Chrome, Firefox)
   - [Greasemonkey](https://www.greasespot.net/) (Firefox)

2. Click the link below to install the script:
   - [Install from GitHub](https://raw.githubusercontent.com/memoverflow/memoverflow-coursera-transcript-right/main/coursera-transcript-right.user.js)

   Or install from [Greasy Fork](https://greasyfork.org/) (coming soon)

3. Visit any Coursera video lecture page and enjoy!

## Usage

Once installed, the script will automatically:
- Shrink the video player to make room for the transcript on the right
- Display the transcript in a fixed panel on the right side
- Auto-scroll to the highlighted sentence while the video is playing
- Stop auto-scrolling when the video is paused, allowing you to browse freely

## Compatibility

- Tested on Coursera.org video lecture pages
- Works with Tampermonkey on Chrome, Firefox, and Edge

## Known Issues

- The layout may not work perfectly on all Coursera page types (e.g., quizzes, readings)
- If the transcript doesn't appear, try refreshing the page

## Contributing

Issues and pull requests are welcome!

## License

MIT License - see [LICENSE](LICENSE) for details.

## Author

[memoverflow](https://github.com/memoverflow)
