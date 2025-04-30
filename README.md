# GeoIP Browser

A lightweight, dark-themed IP lookup tool that runs entirely in the browser—no backend required! Powered by [ipapi.co](https://ipapi.co), it returns the full JSON geolocation response for any IPv4/IPv6 address (or your own IP).

---

## 🚀 Features

- **Pure Frontend**: Static HTML & vanilla JS—deploy to GitHub Pages in seconds
- **Dark Theme**: Built with Tailwind CSS’s dark mode and a modern color palette
- **FontAwesome Icons**: Clean search button iconography
- **Full JSON Output**: See country, region, city, ASN, ISP, timezone, latitude/longitude, and more
- **Easy to Customize**: Swap out the API URL or tweak the styling via Tailwind config

---

## 📦 Installation

1. **Clone** the repo

   ```bash
   git clone https://github.com/AbdelrahmanBayoumi/geoip-browser.git
   cd geoip-browser
   ```

2. **Serve** locally (optional)

   - Open `index.html` directly in your browser
   - Or, run a simple HTTP server:
     ```bash
     npx serve .
     ```

3. **Deploy** to GitHub Pages
   - Push to a branch named `gh-pages`, or set `main`/`master` as the Pages branch in your repo settings.

---

## 🖥 Usage

1. Enter any IP address (or leave blank to lookup your own).
2. Click the search button or press Enter.
3. View the formatted JSON response below the input.

---

## 🔧 Customization

- **Tailwind Colors**: Edit the `primary`/`accent` colors in the `<script> tailwind.config = {…}` block
- **API Endpoint**: Change the URL in `lookup()` if you want to use a different public geo-IP service
- **Styling**: Tweak classes on the container, input, button, or `<pre>` to match your brand

---

<h4 align="center">سبحَانَكَ اللَّهُمَّ وَبِحَمْدِكَ، أَشْهَدُ أَنْ لا إِلهَ إِلأَ انْتَ أَسْتَغْفِرُكَ وَأَتْوبُ إِلَيْكَ</h4>
