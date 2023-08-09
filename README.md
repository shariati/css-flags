# CSS Country Flags

CSS Country Flags is a delightful project that aims to bring the flags of the world to life using nothing but HTML and CSS. Whether you're a vexillology enthusiast like [Sheldon Cooper](https://en.wikipedia.org/wiki/Sheldon_Cooper) or a web development hobbyist, this project offers an exciting opportunity to explore the unique designs of various national flags.

Starting with the Singapore flag in honor of Singapore National Day, this project will expand to include flags from different countries, each carefully crafted with simple code.

<img src="./image/sg/Singapore Flag.jpg" width="280">
<br />*Preview of the Singapore flag created with CSS*

## 🌏 Flags Collection

Here's a list of flags currently available:

### 🇸🇬 Singapore

The Singapore flag consists of two equal horizontal sections, red above white. A white crescent moon occupies the upper left red section. Next to the moon are five white stars arranged in a circle.
Each feature of the Flag bears a unique symbolic meaning. Red stands for universal brotherhood and equality of man. White symbolizes pervading and everlasting purity and virtue. The crescent moon represents a young nation on the ascendant, and the five stars depict Singapore's ideals of democracy, peace, progress, justice, and equality. [Read More](https://www.nhb.gov.sg/what-we-do/our-work/community-engagement/education/resources/national-symbols/national-flag)

*More flags will be added soon!*

## File Structure
```
.
├── LICENSE.md
├── README.md
├── build
├── image
│   └── sg
└── src
    ├── css
    │   └── sg.css
    └── index.html
```

### Root Directory
- `LICENSE.md`: Contains the license details for your project, specifying the terms under which the project can be used, modified, and distributed.
- `README.md`: The main documentation file that explains the purpose of the project, how to use it, and other essential information.
- `build`: This folder is commonly used to store compiled or minified versions of source code, ready for deployment.
- `image`: A folder containing images related to the project. Inside the `images/` folder, you'll find subfolders named with ISO 3166 alpha-2 country codes. 
- Each subfolder contains:
  - `sg`: A subdirectory containing files related to the Singapore flag.
  - `Singapore Flag.ai`: An Adobe Illustrator file containing a vector design of the Singapore flag.
  - `Singapore Flag.jpg`: A raster image file (JPEG) of the Singapore flag.
  - `Singapore Flag.svg`: An SVG (Scalable Vector Graphics) file of the Singapore flag, ideal for web use.

- `src`: The source directory, containing the main HTML and CSS files that make up the project.
- `css`: Contains the CSS files for the project.
- `sg.css`: The specific CSS file for styling the Singapore flag.
- `index.html`: The main HTML file that contains the structure of the web page, including the flag's HTML representation.

## Usage

### CSS Version

Simply include the specific CSS file for the flag you wish to use and refer to the corresponding HTML structure.

```html
<link rel="stylesheet" href="src/css/sg.css">
<div class="flags singapore">
  <!-- Content goes here -->
</div>
```

This CSS version is great for learning and understanding CSS better. Please note that this CSS version is **NOT** recommended for actual web implementations due to potential compatibility and computational issues.

### SVG Version
For real websites, please use the SVG files found in the images/ folder. These provide a more reliable and scalable solution for displaying flags.

## Contributing
Want to add a flag or improve an existing one? Feel free to open an issue or submit a pull request. Check the CONTRIBUTING.md for guidelines.

## License
This project is separated into two parts with different licensing terms:

### CSS Version
The CSS version of the flags is licensed under the MIT License. This means you are free to use, modify, and distribute the code as long as the original copyright and license notice are included. See the LICENSE.md file for details.

### Images
All images in the `image` folder, including `.ai`, `.jpg`, and `.svg` files, are under the Creative Commons License. You are free to share, use, and even modify these images for your projects as long as you follow the license terms. Please make sure to provide appropriate credit, a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

For more details on the Creative Commons License, please visit the [Creative Commons website](https://creativecommons.org/licenses/).

Please ensure that you understand and comply with the respective licensing terms before using any part of this project.

## Acknowledgements
Thanks to all the creative minds who find joy in crafting visual art with code. Special thanks to [Rodion](https://github.com/rodionlim) for inspiring the beginning of this journey. Join us in this creative endeavor as we explore more flags from around the world. Happy coding!