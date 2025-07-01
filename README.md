# OpenFLOW - Isometric Diagramming Tool

OpenFLOW is a powerful, open-source Progressive Web App (PWA) for creating beautiful isometric diagrams. Built with React and the Isoflow library, it runs entirely in your browser with offline support.

![Screenshot_20250630_160954](https://github.com/user-attachments/assets/0e6e1adf-939b-46c6-945c-5bc07ca255ef)


## Features

- 🎨 **Isometric Diagramming** - Create stunning 3D-style technical diagrams
- 💾 **Auto-Save** - Your work is automatically saved every 5 seconds
- 🔒 **Privacy-First** - All data stored locally in your browser
- 📤 **Import/Export** - Share diagrams as JSON files
- 🌐 **Offline Support** - Work without internet connection

## Quick Start

### Run Locally

```bash
# Clone the repository
git clone https://github.com/stan-smith/OpenFLOW
cd openflow-local

# Install dependencies
npm install

# Start development server
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## How to Use

### Creating Diagrams

1. **Add Items**: Drag and drop components from the library onto the canvas
2. **Connect Items**: Use connectors to show relationships between components
3. **Customize**: Change colors, labels, and properties of items
4. **Navigate**: Pan and zoom to work on different areas

### Saving Your Work

- **Auto-Save**: Diagrams are automatically saved to browser storage every 5 seconds
- **Quick Save**: Click "Quick Save (Session)" for instant saves without popups
- **Save As**: Use "Save New" to create a copy with a different name

### Managing Diagrams

- **Load**: Click "Load" to see all your saved diagrams
- **Import**: Load diagrams from JSON files shared by others
- **Export**: Download your diagrams as JSON files to share or backup
- **Storage**: Use "Storage Manager" to manage browser storage space

### Keyboard Shortcuts

- `Delete` - Remove selected items
- `Ctrl/Cmd + Z` - Undo (if supported by browser)
- Mouse wheel - Zoom in/out
- Click and drag - Pan around canvas

## Building for Production

```bash
# Create optimized production build
npm run build

# Serve the production build locally
npx serve -s build
```

The build folder contains all files needed for deployment.

## Deployment

### Static Hosting

Deploy the `build` folder to any static hosting service:
- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Any web server

### Important Notes

1. **HTTPS Required**: PWA features require HTTPS (except localhost)
2. **Browser Storage**: Diagrams are saved in browser localStorage (~5-10MB limit)
3. **Backup**: Regularly export important diagrams as JSON files

## Browser Support

- Chrome/Edge (Recommended) ✅
- Firefox ✅
- Safari ✅
- Mobile browsers with PWA support ✅

## Troubleshooting

### Storage Full
- Use Storage Manager to free space
- Export and delete old diagrams
- Clear browser data (last resort - will delete all diagrams)

### Can't Install PWA
- Ensure using HTTPS
- Try Chrome or Edge browsers
- Check if already installed

### Lost Diagrams
- Check browser's localStorage
- Look for auto-saved versions
- Always export important work

## Technology Stack

- **React** - UI framework
- **TypeScript** - Type safety
- **Isoflow** - Isometric diagram engine
- **PWA** - Offline-first web app

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT - Isoflow community edition is released under the MIT license.
Unlicense - OpenFLOW is released under the unlicense license, you can modify and distribute it however you please, I don't care.

## Acknowledgments

Built with the ISOFLOW (https://github.com/markmanx/isoflow) library.

Check out my website:
x0z.co
