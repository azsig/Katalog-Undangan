# Wedding Invitation Website Demo

## Live Website Features

### 🎨 Design Highlights
- **Modern gradient background** (purple to pink)
- **Elegant serif fonts** (Playfair Display & Cormorant Garamond)
- **Smooth scroll animations** with AOS.js
- **Fully responsive** design for all devices

### 📱 How to Use

1. **Open the website:**
   ```
   Open index.html in your browser
   ```

2. **Personalize for guests:**
   ```
   index.html?to=John%20Doe
   index.html?to=Maria%20Silva
   ```

### ✨ Interactive Features

1. **Countdown Timer** - Updates every second
2. **Music Player** - Click the floating button to play/pause
3. **Photo Gallery** - Hover over images for zoom effect
4. **Google Maps** - Click buttons to open location
5. **RSVP Form** - Fill and submit (shows success message)
6. **Smooth Scrolling** - Click "Lihat Undangan" to scroll down

### 🔧 Customization Guide

**Change Wedding Date:**
Line 390: `const weddingDate = new Date('2026-02-15T08:00:00')`

**Update Couple Names:**
Line 95: `<h1 class="font-heading text-5xl md:text-7xl font-bold mb-4">Your Names</h1>`

**Modify Event Details:**
- Lines 195-230: Akad Nikah details
- Lines 235-265: Resepsi details

**Replace Gallery Images:**
Replace URLs in lines 150-175 with your own wedding photo URLs or download free images from:
- Unsplash.com (search: "wedding couple")
- Pexels.com (search: "anime wedding" or "wedding")
- Pixabay.com (search: "wedding illustration")

**Change Theme Colors:**
- Purple classes: `bg-purple-600`, `text-purple-600`
- Pink classes: `bg-pink-600`, `text-pink-600`
- Gradient: `.hero-bg` in the `<style>` section

### 📊 Technical Stack

- HTML5 (semantic markup)
- Tailwind CSS 3.x (CDN)
- Alpine.js 3.x (reactivity)
- AOS.js 2.3 (animations)
- Google Fonts (typography)

### 🌐 Browser Compatibility

✅ Chrome, Firefox, Safari, Edge (latest versions)
✅ Mobile browsers (iOS Safari, Chrome Mobile)
✅ Tablet browsers

### 📸 Screenshot

See the full website screenshot in the PR description!

---

**Note:** The website uses CDN resources which may be blocked in some testing environments. 
For production use, consider downloading and hosting these libraries locally for better performance and reliability.
