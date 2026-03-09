# YouTube Clone

A front-end clone of YouTube's homepage built with HTML and CSS. This project replicates the core UI components of YouTube including the header, sidebar, content filters, and video grid layout.

![YouTube Clone Preview](screenshot-placeholder.jpg)

## 📋 Overview

This project is a static YouTube clone that focuses on replicating the visual design and layout of YouTube's main interface. It includes a responsive header with search functionality, a comprehensive sidebar navigation menu, content filter chips, and a grid of video cards.

## ✨ Features

- **Fixed Header**: Contains YouTube logo, search bar with microphone, and action buttons (Create, Notifications, User profile)
- **Expandable Sidebar**: Includes navigation items like Home, Shorts, Subscriptions, Library, and more
- **Content Filter Chips**: Horizontal scrollable category filters
- **Video Grid**: Responsive grid layout displaying video thumbnails with channel info, titles, and metadata
- **Responsive Design**: Adapts to different screen sizes (mobile, tablet, desktop)
- **Hover Effects**: Interactive elements with visual feedback

## 🛠️ Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling and responsive design
- **Font Awesome 6.4.0** - Icons and visual elements
- **Google Fonts** - Roboto font family
- **CSS Flexbox** - Layout management
- **CSS Grid** - Video card grid system
- **Media Queries** - Responsive breakpoints

## 📁 Project Structure

```
youtube-clone/
│
├── index.html          # Main HTML document
├── style.css           # All styling rules
├── favicon.png         # Browser tab icon
│
├── images/             # (Expected folder)
│   ├── menu bar.svg
│   ├── mic.svg
│   ├── shorts.svg
│   ├── sub.png
│   ├── user.png
│   ├── note.png
│   ├── game.png
│   ├── newsfeed.svg
│   ├── trophy.png
│   ├── ytpremium.svg
│   ├── ytmusic.svg
│   ├── ytkids.svg
│   ├── setting.svg
│   ├── flag.png
│   ├── help.png
│   ├── feedback.png
│   ├── video_thumb_1.jpg through video_thumb_6.jpg
│   ├── profile_1.jpg through profile_6.jpg
│   └── profile_2.jpg
```

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/kliscene/youtube-clone.git
```

2. Navigate to the project directory:
```bash
cd youtube-clone
```

3. Open `index.html` in your browser:
```bash
# On macOS
open index.html

# On Windows
start index.html

# On Linux
xdg-open index.html
```

## 💻 Usage

Simply open the HTML file in any modern web browser. The page is fully static and doesn't require any build process or server setup.

### Responsive Breakpoints

- **Mobile**: < 768px - Simplified header, hidden sidebar, single column video grid
- **Tablet**: 768px - 1280px - 2-column video grid
- **Desktop**: > 1280px - Full layout with multi-column video grid

## 🎯 Key Components

### Header
- Left: Menu icon and YouTube logo
- Center: Search input with search button and microphone
- Right: Create button, notifications (with counter), and user profile

### Sidebar
- Primary navigation (Home, Shorts, Subscriptions)
- User section (You, History)
- Sign-in prompt
- Explore section (Trending, Music, Games, News, Sports)
- YouTube products section (Premium, Music, Kids)
- Settings and footer links

### Main Content
- Filter chips for content categories
- Video cards with thumbnails, channel logos, titles, and metadata

## 👤 Author

Touqeer Asim

## 📄 License

This project is for educational purposes only. All trademarks and copyrights belong to their respective owners (Google/YouTube).

## 🙏 Acknowledgments

- Inspired by YouTube's official design
- Icons provided by [Font Awesome](https://fontawesome.com/)
- SVG icons sourced from various free resources

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 🔮 Future Improvements

- Add JavaScript for interactive features
- Implement working search functionality
- Add video player page
- Create dark mode theme
- Add smooth scrolling for filter chips
- Implement lazy loading for images

---

**Note**: This is a front-end clone created for learning purposes. It does not include any backend functionality or actual video playback capabilities.
