# exif-viewer

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple, client-side web tool for viewing EXIF metadata from JPEG files. Drag and drop an image to see its data—no files are ever uploaded.

## Demo

**[Live Demo](https://code4fukui.github.io/exif-viewer/)**

The interface is minimal. Drag a JPEG file onto the drop zone, and the page will display a table with all the extracted EXIF data.


![Screenshot of exif-viewer UI showing a table of EXIF data for an image](https://code4fukui.github.io/exif-viewer/ogp.jpg)


## Features

-   **Client-Side Processing:** Images are processed directly in your browser. Your files are never uploaded to a server.
-   **Simple Table Display:** EXIF data is presented in a clean, two-column table of tags and their values.
-   **Smart Formatting:** Correctly formats rational numbers (e.g., shutter speed, aperture) and converts URLs found in metadata into clickable links.
-   **File Validation:** Accepts `.jpg` and `.jpeg` files and provides clear alerts for invalid file types or corrupted data.

## Usage

1.  Open the [demo page](https://code4fukui.github.io/exif-viewer/).
2.  Drag and drop a `.jpg` or `.jpeg` file onto the page.
3.  The EXIF data will instantly appear in a table.

## Credits

This tool is built using the following open-source projects:

-   **EXIF Parsing:** [exif-js](https://github.com/taisukef/exif-js/)
-   **UI Framework:** [Bootstrap](https://getbootstrap.com/)
-   **Related Project:** [jpgbeauty](https://code4fukui.github.io/jpgbeauty/)

## License

MIT License — see [LICENSE](LICENSE).