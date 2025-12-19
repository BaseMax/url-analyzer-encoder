# URL Analyzer & Encoder

A powerful web-based utility for parsing, analyzing, and editing URLs with real-time encoding/decoding capabilities.

## Features

- 🔍 **URL Parsing**: Break down URLs into their components (protocol, host, port, path, hash)
- 🔐 **Query Parameter Decoding**: Automatically decode URL-encoded query parameters (e.g., `%20` → space)
- ✏️ **Live Editing**: Edit query parameters in real-time with instant URL recomposition
- 🔄 **Automatic Encoding**: See both decoded and encoded versions of parameter values
- ➕ **Add Parameters**: Add new query parameters dynamically
- 🗑️ **Delete Parameters**: Remove unwanted query parameters
- 📋 **Copy to Clipboard**: One-click copy of the reconstructed URL
- 🎨 **Modern UI**: Clean, responsive interface built with TailwindCSS

## Usage

Simply open `index.html` in your web browser. No build process or dependencies required!

### Example Workflow

1. Enter or paste a URL (e.g., `https://example.com/search?q=Hello%20World&category=tech`)
2. Click "Analyze URL" to parse the URL
3. View the broken-down components and decoded query parameters
4. Edit parameter keys and values directly in the interface
5. Add new parameters with the "+ Add Parameter" button
6. Delete unwanted parameters with the "Delete" button
7. Copy the reconstructed URL with proper encoding

## Technology Stack

- **HTML5**: Semantic markup
- **TailwindCSS**: Utility-first CSS framework (via CDN)
- **Vanilla JavaScript**: No frameworks, pure JavaScript for URL manipulation

## Features Demonstration

### URL Components
The tool extracts and displays:
- Protocol (e.g., `https:`)
- Host (e.g., `example.com`)
- Port (if specified)
- Path (e.g., `/search`)
- Hash/Fragment (e.g., `#results`)

### Query Parameter Handling
- **Decoded View**: Shows human-readable values (e.g., "Hello World")
- **Encoded Display**: Shows URL-encoded version (e.g., "Hello%20World")
- **Live Updates**: Changes reflect immediately in the reconstructed URL
- **Special Characters**: Properly handles spaces, ampersands, slashes, and other special characters

## License

This project is available under the MIT License - see the [LICENSE](LICENSE) file for details.
