# Imposer - User Guide

## Overview

Imposer is a desktop imposition tool designed for the print industry. It allows you to arrange multiple pages onto single sheets for efficient printing, resize pages, and combine multiple documents.

**Version:** 1.0  
**Developer:** One Stop Vape and Print Shop, LLC  
**Contact:** osprintshops@gmail.com

---

## Getting Started

### Installation

1. Download the installer for your operating system
2. Run the installer and follow the prompts
3. Launch Imposer from your applications menu

### Supported File Formats

Imposer supports the following file types:
- **PDF files** (.pdf) - Direct loading
- **Word Documents** (.doc, .docx) - Automatically converted to PDF
- **Images** (.jpg, .jpeg, .png) - Automatically converted to PDF
- **Publisher files** (.pub) - Must be manually converted to PDF in Microsoft Publisher first

---

## Main Features

### 1. Opening Files

**To open a file:**
1. Click the **📁 Open** button in the toolbar (or press Ctrl+O)
2. Select your file from the dialog
3. The file will load and display in the preview area

**Important Note:** Files remain locked while open in Imposer. If you need to edit the original file in another application, close Imposer first or open a different file to release the lock.

### 2. N-up Imposition

Arrange multiple pages onto a single sheet in a grid layout.

**Steps:**
1. Open your source document
2. In the **N-up** section, select the layout:
   - 2-up, 4-up, 8-up, 16-up, or Custom
3. Configure page size:
   - **Letter** (8.5" × 11")
   - **Tabloid** (11" × 17")
   - **A4** (210mm × 297mm)
   - **A3** (297mm × 420mm)
4. Set orientation (Portrait or Landscape)
5. Adjust margins and gaps between pages
6. Enable **Page Numbering** if desired:
   - Choose position: Top-left, Top-right, Bottom-left, Bottom-right, or Center
   - Adjust font size and color
7. Click **Preview** to see the result
8. Click **💾 Save** to export the imposed PDF

**What it does:** Creates signature sheets with multiple pages arranged in reading order.

### 3. Resize Pages

Scale or resize individual pages or all pages to a new size.

**Steps:**
1. Open your source document
2. In the **Resize** section, choose:
   - **All Pages** - Resize the entire document
   - **Specific Pages** - Enter page numbers (e.g., "1,3,5" or "1-10")
3. Select target page size (Letter, Tabloid, A4, A3, or Custom)
4. Choose scale mode:
   - **Fit to Page** - Scales to fit while maintaining aspect ratio
   - **Stretch** - Fills the entire page (may distort)
   - **Center** - Places at original size, centered
5. Click **Preview** to see the result
6. Click **💾 Save** to export

**Use cases:**
- Converting between page sizes (Letter to A4)
- Scaling documents for different printers
- Creating thumbnails or enlargements

### 4. Multi-up (Merge Multiple Files)

Combine multiple documents and arrange them on sheets.

**Steps:**
1. In the **Multi-up** section, click **Select Files**
2. Choose multiple PDF, Word, or image files
3. Select layout (2-up, 4-up, etc.)
4. Choose output page size and orientation
5. Adjust margins and gaps
6. Click **Generate Multi-up** to create the imposed document
7. Click **💾 Save** to export

**Use cases:**
- Combining multiple flyers onto one sheet
- Creating booklets from separate chapters
- Batch processing multiple documents

---

## Toolbar Features

### File Operations
- **📁 Open** - Open a PDF, Word doc, or image file (Ctrl+O)
- **💾 Save** - Save the current output (available after generating)
- **🖨️ Print** - Print the imposed document

### Edit Operations
- **↶ Undo** - Undo the last operation (Ctrl+Z)
- **↷ Redo** - Redo an undone operation (Ctrl+Y)

### Preview & Zoom
- **🔄 Preview** - Refresh the preview (F5)
- **−** - Zoom out (decreases preview size by 25%)
- **+** - Zoom in (increases preview size by 25%)
- **Reset** - Reset zoom to 100%
- Zoom range: 25% to 200%

### Profiles
- **💾 Save Profile** - Save current settings for later use
- **📂 Load Profile** - Load previously saved settings

### Help
- **ℹ️ About** - View application information and contact details

---

## Preview Window

### Features
- **Original Preview** - Shows the source document
- **Sheet Preview** - Shows the imposed output
- **Toggle Display** - Show/hide the original preview
- **Split/Column View** - View both previews side-by-side or stacked
- **Zoom Controls** - Scale preview for detailed inspection
- **Page Navigation** - Browse through pages with ← and → buttons

### Tips
- Use zoom to inspect fine details
- The preview automatically scales to fit your window size
- Scroll when zoomed beyond 100% to see all content

---

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| Ctrl+O | Open file |
| Ctrl+S | Save output |
| Ctrl+Z | Undo |
| Ctrl+Y | Redo |
| F5 | Refresh preview |
| Ctrl++ | Zoom in |
| Ctrl+- | Zoom out |
| Ctrl+0 | Reset zoom |

---

## Common Workflows

### Creating a Booklet
1. Open your PDF
2. Select **4-up** in N-up section
3. Choose **Tabloid** page size
4. Set orientation to **Landscape**
5. Enable **Page Numbering** (bottom-center recommended)
6. Click **Preview** and verify page order
7. **Save** and print double-sided

### Printing Multiple Business Cards
1. Create one business card as a PDF or image
2. Use **Multi-up** and select the same file multiple times
3. Choose **8-up** or **16-up** layout
4. Select **Letter** size
5. Adjust margins to fit your card stock
6. Generate and save

### Converting Word Documents
1. Click **Open** and select your .docx file
2. Wait for automatic conversion (may take a few seconds)
3. All pages will be converted to PDF format
4. Proceed with any imposition operations

---

## Tips & Best Practices

### For Best Results
- **Use high-quality source files** - Low resolution PDFs will remain low quality
- **Check bleeds** - If your design has bleeds, ensure margins account for them
- **Test print one sheet first** - Verify alignment before printing large batches
- **Save profiles** - Create profiles for frequently used settings
- **Preview before saving** - Always check the preview to avoid mistakes

### Performance
- Large files (100+ pages) may take longer to process
- Word document conversion depends on document complexity
- Close other applications if processing is slow

### Troubleshooting
- **File won't open elsewhere** - Close Imposer to release the file lock
- **Preview looks blurry** - Use zoom controls to see fine details
- **Word conversion failed** - Ensure the document isn't corrupted; try opening in Word first
- **Print dialog is blank** - This is a known issue with some PDF viewers; the fix uses the system print dialog

---

## Known Limitations

1. **File Locking**: Files opened in Imposer cannot be edited in other applications until Imposer is closed or a different file is opened.

2. **Publisher Files**: Microsoft Publisher (.pub) files cannot be directly converted. Please use Publisher's "Save as PDF" feature first.

3. **Complex Formatting**: Some advanced Word document formatting may not convert perfectly. For critical documents, save as PDF in Word first.

4. **Page Size Limits**: Custom page sizes must be between 1 inch and 200 inches.

5. **Memory Usage**: Very large files (1000+ pages) may require significant RAM.

---

## Support

### Getting Help
- **Email:** osprintshops@gmail.com
- **Include:** 
  - Version number (found in About dialog)
  - Description of the issue
  - Steps to reproduce
  - Sample files if relevant (and permissible)

### Feedback
We welcome feedback and feature requests! Please email with your suggestions.

---

## License & Copyright

**Imposer** v1.0  
Copyright © 2025 One Stop Vape and Print Shop, LLC  
All rights reserved.

This software is licensed for use by authorized customers only. Redistribution, reverse engineering, or modification is prohibited without written permission.

---

## Version History

### Version 1.0 (December 2025)
- Initial release
- N-up imposition (2, 4, 8, 16-up)
- Page resizing with multiple modes
- Multi-up file merging
- Word document conversion
- Image to PDF conversion
- Page numbering
- Preview with zoom
- Profile save/load
- Undo/Redo support
- Print functionality

---

*Thank you for choosing Imposer!*
