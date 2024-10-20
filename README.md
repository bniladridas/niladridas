<a id="readme-top"></a>

<div align="center">

![Astro](https://astro.build/assets/press/astro-icon-light-gradient.svg)

[![Available on my social bio](https://img.shields.io/badge/Available%20on%20my-Social%20Bio-purple?style=for-the-badge&logo=x&logoColor=white)](https://x.com/bniladridas)

<p><a href="https://niladridas.vercel.app">Live Demo</a></p>
</div>

<h1 align="center">niladridas</h1>

<p align="center">
  A customizable open-source link page built with Astro, easy to update via JSON.
</p>

<div align="center">

![Astro](https://img.shields.io/badge/Astro-0C1222?style=for-the-badge&logo=astro&logoColor=FDFDFE)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

Open source links page, customizable via JSON. Made with Astro 4.

</div>

![Preview Image](/public/fullpage.png)

## Table of Contents

1. [About The Project](#about-the-project)
2. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
3. [JSON Customization](#json-customization)
   - [Icons](#icons)
4. [Contributing](#contributing)
5. [License](#license)

## About The Project

Link pages have become essential for both companies and individuals, but many "free" solutions come with unwanted branding and self-promotion. **AstroLinkHub** offers a sleek, customizable, and self-hosted alternative.

**Key Features:**
- 🚀 Build your personal or professional link page without any third-party branding.
- 🎨 Fully customizable appearance with support for gradient colors and more.
- 🔄 Simple JSON configuration for effortless updates.

<p align="right"><a href="#readme-top">Back to top ⬆️</a></p>

## Getting Started

> [!IMPORTANT]
> I'm glad to announce that this project is available on [Astro Themes!](https://astro.build/themes/details/astrolinkhub/) 🚀

### Prerequisites

- **Node.js** -> `v18.17.1` or `v20.3.0` or higher. (`v19` is not supported)
- **Visual Studio Code** -> with the [Official Astro Extension](https://marketplace.visualstudio.com/items?itemName=astro-build.astro-vscode).

Personally, I prefer using `pnpm` instead of `npm`. To install it, use the following command:

```bash
npm install -g pnpm
```

### Installation

1. Clone this repo to your computer:
   ```bash
   git clone git@github.com:bniladridas/niladridas.git
   ```
2. Install Astro dependencies:
   ```bash
   cd niladridas
   npm install
   ```
3. Run the Astro dev server:
   ```bash
   npm run dev
   ```

<p align="right"><a href="#readme-top">Back to top ⬆️</a></p>

## JSON Customization

The best part of AstroLinkHub is that you can modify every aspect of the website very easily by editing the `index.json` file. This JSON contains the following sections:

```json
{
  "html": {
    "language": "en",
    "title": "Your Name",
    "description": "Welcome to my links page!"
  },
  "header": {
    "image": "/path/to/your-image.png",
    "name": "Your Name",
    "description": "A brief description about you."
  },
  "socials": [
    {"network": "GitHub", "url": "https://github.com/yourusername"},
    {"network": "LinkedIn", "url": "https://linkedin.com/in/yourprofile"}
  ]
}
```

### Icons

Just edit the key `network` with any of the following values (case-sensitive):

- Discord
- Facebook
- GitHub
- Instagram
- Link
- LinkedIn
- Mail
- Map
- Medium
- Spotify
- TikTok
- Twitch
- WhatsApp
- X
- YouTube

> [!NOTE]
> If you need more open-source icons, visit: [Tabler Icons](https://tabler.io/icons)

<p align="right"><a href="#readme-top">Back to top ⬆️</a></p>

## Contributing

Contributions make open source awesome! If you have ideas to improve this project, feel free to fork the repo and submit a pull request, or open an issue with your suggestions.

**Ways to Contribute:**
- Suggest new features
- Report bugs or issues
- Improve documentation

**Don't forget to give the project a star!** ⭐

<p align="right"><a href="#readme-top">Back to top ⬆️</a></p>

## License

Distributed under the MIT License. `Open Source` is pretty self-descriptive.

<p align="right"><a href="#readme-top">Back to top ⬆️</a></p>