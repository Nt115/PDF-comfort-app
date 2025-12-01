# PDF Comfort App

An intuitive document reader application that transforms PDFs and Word documents into a Kindle-like reading experience. With intelligent text recognition, comfortable typography controls, and powerful annotation tools, PDF Comfort App makes reading documents enjoyable and distraction-free.

## Features

### 📖 Kindle-Like Reading Experience
- **Adjustable Typography**: Resize text dynamically to your preferred reading size
- **Eye-Friendly Display**: Black and white theme optimized for comfortable reading (additional color modes coming soon)
- **Smooth Navigation**: Page-by-page or continuous scroll reading modes
- **Progress Tracking**: Visual reading progress indicator and automatic bookmarking of your current position
- **Distraction-Free Interface**: Minimal UI that focuses on content

### 🖼️ Intelligent Image & Text Recognition
- **Text Extraction from Images**: Automatically identifies and extracts text from embedded images
- **Reader Mode for Images**: Converts image-based text into readable, resizable text format
- **OCR Support**: Recognizes text within document images for seamless reading
- **Smart Document Processing**: Intelligently separates and optimizes text for readability

### 📝 Advanced Annotation Tools
- **Highlighting**: Mark important passages with customizable colors
- **Note Taking**: Add detailed comments and notes directly to your documents
- **Drawing & Markup**: Freehand drawing tools to annotate and emphasize content
- **Text Selection**: Easy selection and copying of text passages

### 🔖 Bookmarking & Organization
- **Smart Bookmarks**: Save important pages and passages for quick reference
- **Bookmark Management**: Organize bookmarks with custom labels
- **Quick Navigation**: Jump to bookmarked pages instantly
- **Bookmark Persistence**: Your bookmarks are saved across reading sessions

### 📂 Document Support
- **PDF Files**: Full support for PDF documents with text and images
- **Word Documents**: Compatible with .docx and other document formats
- **Multi-Document**: Open and switch between multiple documents seamlessly

### 🎨 Personalization
- **Reading Themes**: Black and white mode for optimal comfort (more color modes planned)
- **Text Sizing**: Precise control over font size and scaling
- **Layout Preferences**: Customize line spacing and margins
- **Persistent Settings**: Your preferences are remembered for future sessions

## Getting Started

### Prerequisites
- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Dart SDK](https://dart.dev/get-dart) (included with Flutter)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Nt115/PDF-comfort-app.git
cd PDF-comfort-app
```

2. Install dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

## Usage

### Opening a Document
1. Launch the application
2. Tap the "Open" button
3. Select a PDF or Word document
4. The document loads in reader mode with text automatically optimized

### Resizing Text
- Use the text size controls to increase or decrease font size
- Adjustments apply in real-time across the document
- Your preferred size is saved for future sessions

### Working with Images
- Text within images is automatically detected and extracted
- Image text appears in reader mode for comfortable reading
- Resize extracted text just like regular document text

### Making Annotations
- **Highlight Text**: Select text and apply a highlight
- **Add Notes**: Tap the note icon to add comments
- **Draw Markup**: Use the drawing tool for freehand annotations
- **Create Bookmarks**: Bookmark important pages for quick access

### Managing Your Library
- Switch between open documents easily
- Access all your highlights and notes from the sidebar
- Review and manage bookmarks for quick navigation

## Roadmap

- 🎨 Additional color themes and reading modes
- 🌙 Advanced dark mode with customizable color palettes
- 📱 Cloud sync for bookmarks and notes
- 🔍 Advanced search functionality
- 📊 Reading statistics and analytics

## Project Structure

```
PDF-comfort-app/
├── lib/               # Flutter application source code
├── android/           # Android-specific configuration
├── ios/               # iOS-specific configuration
├── pubspec.yaml       # Project dependencies and metadata
└── README.md          # This file
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Created by [Nt115](https://github.com/Nt115)

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

**Note**: This is an active development project. Features and documentation may be updated regularly.
