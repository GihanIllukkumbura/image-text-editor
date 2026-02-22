# Image Text Editor

A powerful web-based image text editor that allows you to easily edit and replace text on images. Features intelligent background color detection and seamless text replacement with no coding required!

![Image Text Editor](images/Screenshot%20(155).png)

## ✨ Key Features

### 🎨 **Automatic Background Color Detection**

- **Smart Color Sampling**: Automatically detects and samples the background color from selected areas
- **Edge Detection**: Intelligently analyzes the edges of your selection to determine the optimal cover color
- **Seamless Blending**: Cover patches blend perfectly with the original image background

### 🖊️ **Text Editing Tools**

- **Select Area Tool**: Draw a selection rectangle over existing text to replace it
  - Automatically covers the original text with matched background color
  - Creates an editable text box with estimated font size
- **Add Text Tool**: Add new text boxes anywhere on the image

- **Eyedropper Tool**: Pick any color directly from the image to use as cover or text color

### 🎯 **Advanced Formatting**

- **Multiple Font Options**:
  - Segoe UI
  - Arial
  - Times New Roman
  - Courier New
  - Georgia
  - Verdana
  - Impact
  - Comic Sans MS
  - Geometric Sans-Serif

- **Text Styling**:
  - Bold, Italic, Underline
  - Custom font sizes (6px - 200px)
  - Color picker for text color
  - Adjustable line height

### 🎭 **Cover Patch Controls**

- **Custom Cover Color**: Pick or manually set the background cover color
- **Opacity Control**: Adjust transparency (0-100%) for perfect blending
- **Visual Preview**: Real-time color preview before applying

### 📐 **Interactive Manipulation**

- **Drag & Drop**: Move text boxes and their cover patches together
- **Resize**: Drag the resize handle to adjust text box dimensions
- **Duplicate**: Clone text boxes with Ctrl+D
- **Delete**: Remove selected text boxes with Delete key or toolbar button
- **Undo**: Ctrl+Z to undo up to 30 actions

## 🚀 How to Use

### Step 1: Load an Image

![Load Image](images/Screenshot%20(156).png)

- Click the **Load** button or drag and drop an image
- Supports JPG, PNG, GIF, and WebP formats

### Step 2: Select the Area to Edit

![Select Area](images/Screenshot%20(157).png)

1. Click the **Select Area** tool (✂️)
2. Click and drag over the text you want to replace
3. The editor will:
   - **Automatically detect the background color** from the selection edges
   - Create a cover patch with the matching color
   - Place an editable text box over the area

### Step 3: Edit the Text

![Edit Text](images/Screenshot%20(158).png)

- The text box automatically enters edit mode
- Type your new text
- Adjust font, size, color, and styling as needed

### Step 4: Fine-tune (Optional)

![Fine-tune](images/Screenshot%20(159).png)

- **Adjust Cover Color**: Use the eyedropper or color picker to perfect the background match
- **Adjust Opacity**: Slide the opacity control for better blending
- **Move & Resize**: Drag text boxes and use resize handles
- **Apply Styles**: Bold, italic, underline, and font changes

### Step 5: Export

![Export](images/Screenshot%20(160).png)

- Click **Save PNG** button (or press Ctrl+S)
- Download your edited image in high quality

## ⌨️ Keyboard Shortcuts

| Shortcut       | Action                                |
| -------------- | ------------------------------------- |
| `Ctrl+S`       | Save image as PNG                     |
| `Ctrl+D`       | Duplicate selected text box           |
| `Ctrl+Z`       | Undo last action                      |
| `Delete`       | Remove selected text box              |
| `Escape`       | Deselect all / Return to pointer tool |
| `Double-click` | Enter edit mode for text box          |

## 🛠️ Tools Overview

### Pointer Tool (👆)

- Default tool for selecting and moving text boxes
- Click on a text box to select it
- Drag to move text boxes along with their cover patches

### Select Area Tool (✂️)

- Draw rectangles over existing text to replace
- **Automatically samples background color** from selection edges
- Creates synchronized text box and cover patch

### Eyedropper Tool (💧)

- Click anywhere on the image to pick a color
- Picked color is set as the cover color
- Real-time color preview as you hover

## 🎨 Technical Highlights

### Intelligent Background Detection

The editor uses a sophisticated edge-sampling algorithm:

1. Captures the selected region from the image
2. Samples pixels from the top, bottom, left, and right edges (3px deep)
3. Calculates the average RGB values
4. Automatically applies the detected color as the cover patch

This ensures that text replacements blend seamlessly with the original image background!

### Synchronized Elements

Text boxes and cover patches are linked together:

- Moving a text box automatically moves its associated cover patch
- Resizing updates both elements simultaneously
- Deleting removes both the text box and cover patch

### High-Quality Export

When exporting:

- Uses the original image resolution (no quality loss)
- Properly scales all text and cover patches
- Renders fonts, colors, and effects accurately
- Hides UI elements for clean output

## 📁 File Structure

```
hansika madam project/
├── README.md
├── image-text-editor.html          # Main application file
└── Image Text editor/
    ├── image-text-editor.html      # Application
    └── images/                     # Screenshots
        ├── Screenshot (155).png
        ├── Screenshot (156).png
        ├── Screenshot (157).png
        ├── Screenshot (158).png
        ├── Screenshot (159).png
        └── Screenshot (160).png
```

## 🌐 Browser Compatibility

Works in all modern browsers:

- ✅ Chrome/Edge (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

## 🎯 Use Cases

Perfect for:

- **Meme Creation**: Replace text in meme templates
- **Image Localization**: Translate text in images
- **Quick Edits**: Fix typos in screenshots
- **Social Media**: Create custom graphics
- **Presentations**: Update slides without source files
- **E-commerce**: Edit product images
- **Marketing**: Customize promotional materials

## 💡 Tips & Tricks

1. **Better Color Matching**: If the auto-detected color isn't perfect, use the Eyedropper tool to sample a nearby area
2. **Opacity Adjustment**: Reduce opacity slightly (95-98%) for more natural blending
3. **Font Selection**: Try to match the original font style for seamless replacements
4. **Multiple Edits**: You can create multiple text boxes and edit different areas simultaneously
5. **Undo is Your Friend**: Don't be afraid to experiment - you can undo up to 30 actions

## 🔒 Privacy

- 100% client-side processing
- No data sent to any server
- Your images never leave your device
- No tracking or analytics

## 📝 License

This project is open source and available for personal and commercial use.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 👨‍💻 Author

Created with ❤️ for easy image text editing

---

**⭐ If you find this tool useful, please consider giving it a star on GitHub!**
