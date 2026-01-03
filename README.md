# DoomCharts 2025 Number One Albums

![DoomCharts 2025](https://img.shields.io/badge/DoomCharts-2025-ff0000?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-green? style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26? style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

An interactive web app showcasing the top 12 doom metal, stoner rock, and heavy psych albums of 2025, as featured on [DoomCharts.com](https://doomcharts.com).

🔗 **Live Demo:** [https://lrrecords.github.io/doomcharts-2025/](https://lrrecords.github.io/doomcharts-2025/)

---

## 🎸 Features

- **12 Monthly #1 Albums** - Chronologically organized from January to December 2025
- **Embedded Bandcamp Players** - Listen to every album directly in the app
- **Expert Reviews** - Curated reviews from top doom/stoner rock critics
- **Doom Metal Theme** - Dark, atmospheric UI with blood-red accents
- **Fully Responsive** - Optimized for desktop, tablet, and mobile
- **Social Sharing** - Share albums on Twitter, Facebook, and Reddit
- **Scroll-Friendly** - Scrollable album cards for easy navigation

---

## 📋 Table of Contents

- [Featured Albums](#-featured-albums)
- [Technologies](#-technologies)
- [Installation](#-installation)
- [Usage](#-usage)
- [Embedding](#-embedding)
- [Data Source](#-data-source)
- [Contributing](#-contributing)
- [License](#-license)
- [Credits](#-credits)

---

## 🎵 Featured Albums

The app features the following DoomCharts #1 albums from 2025:

1. **DUNES** - Land of the Blind (January 2025)
2. **NAXATRAS** - V (February 2025)
3. **KRYPTOGRAF** - Kryptonomicon (March 2025)
4. **TEMPLE FANG** - Lifted from the Wind (April 2025)
5. **KAL-EL** - Astral Voyager Vol. 1 (May 2025)
6. **GOYA** - In the Dawn of November (June 2025)
7. **MARGARITA WITCH CULT** - Strung Out in Hell (July 2025)
8. **BORRACHO** - Ouroboros (August 2025)
9. **WARCOE** - Upon Tall Thrones (September 2025)
10. **HOWLING GIANT** - Crucible & Ruin (October 2025)
11. **WINDS OF NEPTUNE** - Winds of Neptune (November 2025)
12. **PALM DESERT** - Rays of the Gold and Grays (December 2025)

---

## 🛠️ Technologies

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Flexbox, responsive design
- **Vanilla JavaScript** - No frameworks or dependencies
- **Google Fonts** - Cinzel & Metal Mania typefaces
- **Bandcamp Embed API** - Integrated music players

---

## 📦 Installation

### Option 1: Clone the Repository

```bash
# Clone this repository
git clone https://github.com/lrrecords/doomcharts-2025.git

# Navigate to the project directory
cd doomcharts-2025

# Open index.html in your browser
open index.html
```

### Option 2: Download ZIP

1. Click the green **"Code"** button above
2. Select **"Download ZIP"**
3. Extract the ZIP file
4. Open `index.html` in your web browser

---

## 🚀 Usage

### Running Locally

Simply open `index.html` in any modern web browser. No build process or server required! 

### Updating Album Data

Album data is stored in the JavaScript object `albumData` within `index.html`. To update:

1.  Locate the `<script>` section near the bottom of `index.html`
2. Edit the `doomcharts_number_one_albums` array
3. Each album object contains:
   - `album_title` - Album and artist name
   - `album_title_citation` - Source URL
   - `bandcamp_link` - Bandcamp album URL
   - `bandcamp_embed_code` - Bandcamp iframe embed code
   - `doomcharts_review_text` - Full review text

Example:
```javascript
{
  "album_title": "ARTIST NAME – ALBUM TITLE",
  "album_title_citation": "https://doomcharts.com/.. .",
  "bandcamp_link": "https://artist. bandcamp.com/album/.. .",
  "bandcamp_embed_code": "<iframe>...</iframe>",
  "doomcharts_review_text":  "Review text here..."
}
```

---

## 🌐 Embedding

### Embed on Your Website

Use an iframe to embed the app on any webpage:

```html
<iframe 
  src="https://lrrecords.github.io/doomcharts-2025/" 
  style="width: 100%; height:  1200px; border: none;" 
  title="DoomCharts 2025 Number One Albums"
  loading="lazy">
</iframe>
```

### Responsive Embed

For a fully responsive embed: 

```html
<div style="position: relative; padding-bottom: 100%; height: 0; overflow: hidden;">
  <iframe 
    src="https://lrrecords.github.io/doomcharts-2025/" 
    style="position:  absolute; top: 0; left: 0; width: 100%; height: 100%; border: none;"
    title="DoomCharts 2025 Number One Albums"
    loading="lazy">
  </iframe>
</div>
```

---

## 📊 Data Source

All album data was scraped from [DoomCharts.com](https://doomcharts.com) using [Firecrawl](https://firecrawl.dev/).

### Data Extraction Process

1. Scraped monthly DoomCharts posts (January - December 2025)
2. Extracted #1 albums, reviews, and Bandcamp links
3. Compiled into structured JSON format
4. Integrated into the web app

**Data Attribution:** All reviews and rankings © DoomCharts. com and respective contributors. 

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Reporting Issues

- Found a bug? [Open an issue](https://github.com/lrrecords/doomcharts-2025/issues)
- Have a feature request? Let us know! 

### Submitting Changes

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

### Code Style

- Use semantic HTML5
- Follow existing CSS naming conventions
- Keep JavaScript vanilla (no frameworks)
- Comment complex logic
- Test on multiple browsers

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### Third-Party Content

- **Album Reviews:** © DoomCharts.com and respective contributors
- **Bandcamp Players:** © Bandcamp
- **Fonts:** Google Fonts (Open Font License)

---

## 🙏 Credits

### Built By

**LRRecords** - [lrrecords.com. au](https://lrrecords.com.au)

### Data & Reviews From

- **[DoomCharts](https://doomcharts.com)** - Rankings and editorial content
- **Stoner HiVe** - Album reviews
- **DoomCakes** - Album reviews
- **Musipedia of Metal** - Album reviews
- **Denpa Fuzz** - Album reviews
- **Les chroniques d'Eddy** - Album reviews
- And many more amazing contributors to the doom/stoner scene!

### Special Thanks

- The entire DoomCharts community
- All the bands featured in 2025
- Heavy Psych Sounds, Ripple Music, Small Stone Records, and all the labels keeping doom alive

---

## 🎯 Roadmap

- [ ] Add filtering by genre/subgenre
- [ ] Implement search functionality
- [ ] Add "Album of the Year" voting feature
- [ ] Create 2026 version
- [ ] Dark/Light theme toggle
- [ ] Export as playlist (Spotify, Apple Music)

---

## 📞 Contact

**Questions?  Feedback?**

- 🌐 Website: [lrrecords.com.au](https://lrrecords.com.au)
- 📧 Email: contact@lrrecords.com. au
- 🐦 Twitter: [@lrrecords](https://twitter.com/lrrecords)

---

## ⭐ Show Your Support

If you dig this project, give it a ⭐️ on GitHub! 

**Share the heavy music:**
- [Tweet about it](https://twitter.com/intent/tweet?text=Check%20out%20the%20DoomCharts%202025%20Top%20Albums! &url=https://lrrecords.github.io/doomcharts-2025/)
- Share on your favorite doom/stoner communities
- Embed on your website

---

**Keep it heavy!  🤘**

---

*Last Updated: January 2026*
