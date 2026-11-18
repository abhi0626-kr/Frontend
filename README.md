# Frontend HTML and CSS Examples

This repository is a small collection of standalone HTML and CSS practice examples. It is intended for learning and experimenting with common frontend concepts rather than for running as a framework-based application.

## What is included

- HTML document structure and language metadata
- Links and embedded pages with `<a>` and `<iframe>`
- Images, lists, tables, and forms
- Select elements, multiple selections, datalists, and textareas
- HTML5 audio and video elements
- CSS selectors, colors, borders, spacing, and typography
- Text alignment, text decoration, text transformation, and background properties
- A shared stylesheet used by the main example page

## Project structure

```text
Frontend/
├── HTML/
│   ├── index.html
│   ├── Anchortagredirecthtml.html
│   ├── BackgroundpropertiesusingCss.html
│   ├── FormtagHtml.html
│   ├── Iframe.html
│   ├── ImageExamplehtmlsimple.html
│   ├── Languageinhtml.html
│   ├── ListTagExample.html
│   ├── MultiselectionDropdown.html
│   ├── Tableformat.html
│   ├── TextAllignpropertieslastincss.html
│   ├── TextDecorationpropertiesusingcss.html
│   ├── Textpropertiesexamplecss.html
│   ├── VideoAudioExampleinHtml.html
│   └── VideoAudioWithAutoplay.html
└── CSS/
    └── Style.css
```

## Getting started

No package manager, build tool, or server is required.

1. Clone or download the repository.
2. Open the project in an editor such as Visual Studio Code.
3. Open any HTML file in a browser.

For a better editing workflow, install a local static-server extension such as **Live Server** in Visual Studio Code and open the desired HTML file with **Open with Live Server**. A local server is optional; the examples are static files.

The main page is [HTML/index.html](HTML/index.html). It demonstrates a table, ordered and unordered lists, a description list, inline CSS, and an external stylesheet.

## Example files

| File | Demonstrates |
| --- | --- |
| [index.html](HTML/index.html) | Tables, lists, inline CSS, and external CSS |
| [Anchortagredirecthtml.html](HTML/Anchortagredirecthtml.html) | Links and the `href` attribute |
| [BackgroundpropertiesusingCss.html](HTML/BackgroundpropertiesusingCss.html) | Fixed, positioned, non-repeating background images |
| [FormtagHtml.html](HTML/FormtagHtml.html) | Form controls, validation attributes, radio buttons, checkboxes, and dates |
| [Iframe.html](HTML/Iframe.html) | Embedded YouTube videos and external pages |
| [ImageExamplehtmlsimple.html](HTML/ImageExamplehtmlsimple.html) | Local, remote, and inline images |
| [Languageinhtml.html](HTML/Languageinhtml.html) | `lang`, `details`, `select`, `optgroup`, and `progress` |
| [ListTagExample.html](HTML/ListTagExample.html) | Ordered, unordered, and description lists |
| [MultiselectionDropdown.html](HTML/MultiselectionDropdown.html) | Multiple-select controls, `textarea`, and `datalist` |
| [Tableformat.html](HTML/Tableformat.html) | Table styling with element, class, ID, and inline selectors |
| [TextAllignpropertieslastincss.html](HTML/TextAllignpropertieslastincss.html) | The `text-align-last` property |
| [TextDecorationpropertiesusingcss.html](HTML/TextDecorationpropertiesusingcss.html) | Text decoration and text transformation |
| [Textpropertiesexamplecss.html](HTML/Textpropertiesexamplecss.html) | Justified text alignment |
| [VideoAudioExampleinHtml.html](HTML/VideoAudioExampleinHtml.html) | HTML5 video and audio controls |
| [VideoAudioWithAutoplay.html](HTML/VideoAudioWithAutoplay.html) | Audio autoplay and muted playback |
| [Style.css](CSS/Style.css) | Shared CSS selectors and common styling examples |

## Important notes

- This repository does not currently contain a `package.json`, JavaScript application, automated test suite, or production build.
- Some examples reference files that are not included, such as `IndianFlag.jpg`, `ImageJif.Gif`, `.mp4`, `.mp3`, and `.ogg` files. Add matching assets beside the relevant HTML file or update the source paths before testing those examples.
- A few examples contain absolute Windows paths from the original author’s computer. These paths will not work on another machine and should be replaced with relative paths, for example `../CSS/Style.css`.
- Autoplay may be blocked by browser policy. Muted media is more likely to autoplay.
- `Iframe.html` loads external websites and videos, so it requires an internet connection and may be affected by third-party embedding restrictions.

## Learning workflow

1. Start with `index.html` and inspect the page structure.
2. Open one focused example at a time in the browser.
3. Change the markup or CSS and refresh the page to observe the result.
4. Replace hard-coded or absolute asset paths with files stored in the repository.
5. Keep each example focused on one HTML or CSS concept while experimenting.

## License

No license file is currently included. Add a license before distributing or reusing this project.
