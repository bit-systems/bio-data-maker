# Bio Data Maker

Create beautiful, professional-looking marriage biodata in minutes. This web-based application allows you to generate customizable biodata with various elegant themes, dynamic fields, and easy export options.

## 🌟 Features

- **8 Beautiful Templates**: Choose from a variety of handcrafted templates including Traditional (with Ganesha theme), Floral Pink, Gold Classic, Minimal, Art Deco, Royal Maroon, Peacock Blue, and Elegant Lavender.
- **Dynamic Fields**: Add, remove, edit, and reorder fields using drag-and-drop. Easily customize sections for Personal, Family, and Contact details.
- **Top Icon Decoration**: Add decorative icons (like Lord Ganesha) to the top of your biodata, with the ability to toggle or select custom styles.
- **Photo Upload**: Easily upload and preview a profile photo directly on the biodata.
- **JSON Data Import**: Load pre-filled data using a `.json` file to instantly populate all your details and configurations.
- **Save Draft**: Save your progress locally in the browser so you don't lose your work.
- **Export Options**: 
  - **Download as Image**: Generates a high-quality PNG image of your biodata.
  - **Print / PDF**: Use the browser's built-in print dialog to print directly or save as a PDF.
- **Live Preview**: See changes in real-time as you type, toggle themes, or reorganize fields.

## 🚀 How to Use

1. **Open the Application**: Simply open `index.html` in any modern web browser. No installation or server required.
2. **Fill Details**: Use the left panel to input your personal, family, and contact information.
3. **Customize**: 
   - Choose a template from the "Choose Template" grid.
   - Upload a photo if desired.
   - Reorder fields by dragging them up or down using the `☰` handle.
4. **Import/Export Data**: 
   - Click the **JSON** button to load details from a `.json` file.
   - Click **Save Draft** to store your progress in your browser.
5. **Download**: Once you're satisfied with the live preview, click **Download as Image** to save it to your computer, or click **Print** to generate a PDF.

## 📁 JSON Import Format

You can load your details automatically using a JSON file. The application accepts a JSON file structured with `personal`, `family`, and `contact` arrays:

```json
{
    "personal": [
        { "id": "p1", "label": "Full Name", "value": "Your Name" },
        { "id": "p2", "label": "Date of Birth", "value": "DD/MM/YYYY" }
    ],
    "family": [
        { "id": "f1", "label": "Father's Name", "value": "Father Name" }
    ],
    "contact": [
        { "id": "c1", "label": "Contact No.", "value": "9876543210" }
    ]
}
```

## 🛠️ Built With
- **HTML5 / CSS3**: Vanilla HTML and CSS for structure and elegant styling.
- **Vanilla JavaScript**: Pure JS for state management, drag-and-drop, and dynamic UI rendering.
- **html2canvas**: Used to capture the DOM and export the biodata as a high-quality image.

## 📝 License
This project is intended for personal use and utility purposes.
