# Imposer v0.4.0-beta Release Notes

**Release Date:** December 6, 2025  
**Status:** Beta Release (Pre-Production)  
**Platform:** Windows (32-bit & 64-bit)

---

## Overview

Imposer is a professional desktop application for PDF imposition and print layout management. This beta release includes comprehensive multi-format file support, advanced imposition modes, and a polished user interface.

**Version:** 0.4.0-beta  
**License:** Proprietary  
**Author:** Leondas Paul, III (Galilee Gallery)  
**Contact:** leondaspaul3@gmail.com

---

## What's New in v0.4.0-beta

### Core Features ✅

**1. N-up Imposition**
- Arrange single pages into grids (2-up, 4-up, 8-up, 16-up, or custom)
- Configurable page arrangement (row-major and column-major layouts)
- Automatic page numbering with position and color customization
- Margin and gutter control for professional layouts

**2. Resize Mode**
- Scale individual pages or page ranges to new dimensions
- Maintain aspect ratio or stretch to specific sizes
- Apply to entire document or selected pages
- Custom size input (1-200 inches supported)

**3. Multi-up File Merging**
- Combine multiple PDF/image files into a single document
- Automatic page arrangement into grid layout
- Perfect for combining signatures or sections

**4. Advanced Preview System**
- Real-time preview with container-responsive scaling
- Zoom range: 25% to 200% (25% increments)
- Toggle between original and modified versions
- Split-view comparison mode
- Responsive to window resize

**5. File Format Support**
- **PDF** - Native support, full editing capabilities
- **Word Documents** (.doc, .docx) - Automatic conversion to PDF with formatting preservation
- **Images** (JPG, PNG) - Auto-conversion to PDF
- **Publisher Files** (.pub) - Manual conversion guidance included
- **Multi-page Documents** - Full support for all formats

### UI/UX Improvements ✅

- **Reorganized Toolbar** - Save/Load Profile buttons, universal Preview button, zoom controls
- **Responsive Design** - Automatic scaling based on window size with ResizeObserver
- **Intuitive Layout** - Page numbering in N-up section, focused sidebar
- **Professional Icons** - Custom Imposer icon throughout application
- **Keyboard Shortcuts:**
  - `Ctrl+O` - Open file
  - `Ctrl+S` - Save imposed PDF
  - `Ctrl+Z` / `Ctrl+Y` - Undo/Redo
  - `F5` - Refresh preview
  - `Ctrl++` / `Ctrl+-` - Zoom in/out
  - `Ctrl+0` - Reset zoom

### File Handling ✅

- Robust file type detection with extensions and MIME types
- Async file operations for non-blocking I/O
- Proper error handling with user-friendly messages
- Profile system for saving/loading imposition settings (JSON format)

### Print Functionality ✅

- System print dialog integration
- Support for multiple printers
- Custom paper sizes and margins
- Print preview compatibility
- Fallback to Electron's native print method

### Undo/Redo System ✅

- Full action history tracking
- Unlimited undo/redo (configurable stack size)
- Keyboard and menu shortcuts
- Automatic state management

---

## System Requirements

### Minimum Requirements
- **OS:** Windows 7 SP1 or newer
- **Architecture:** 32-bit (x86) or 64-bit (x64)
- **RAM:** 2 GB minimum
- **Disk Space:** 300 MB for installation
- **Processor:** Intel/AMD dual-core, 1.6 GHz or higher

### Recommended Requirements
- **OS:** Windows 10/11 (latest builds)
- **RAM:** 4 GB or more
- **Disk Space:** 500 MB
- **Processor:** Modern multi-core processor
- **Internet:** For file conversion features

### Supported Formats
- **Input:** PDF, DOC, DOCX, JPG, JPEG, PNG, PUB
- **Output:** PDF
- **Max Document Size:** 1000 pages (memory dependent)
- **Custom Page Sizes:** 1 to 200 inches supported

---

## Installation

### Option 1: Full Installer (Recommended)
- **File:** `Imposer Setup 0.4.0-beta.exe` (213 MB)
- **Features:**
  - Professional installation wizard
  - Desktop and Start Menu shortcuts
  - Automatic uninstaller
  - Runs on both 32-bit and 64-bit Windows
- **Installation Steps:**
  1. Download `Imposer Setup 0.4.0-beta.exe`
  2. Double-click to launch installer
  3. Follow the installation wizard
  4. Choose installation directory (customizable)
  5. Select shortcut options
  6. Application launches automatically on completion

### Option 2: Portable Executable
- **File:** `Imposer 0.4.0-beta.exe` (212 MB)
- **Features:**
  - No installation required
  - Run directly from any location
  - USB portable installation
  - Includes both 32-bit and 64-bit binaries
- **Usage:**
  1. Download `Imposer 0.4.0-beta.exe`
  2. Place anywhere (Desktop, USB, folder)
  3. Double-click to run
  4. Settings stored in application directory

### Uninstallation

**Via Installer:**
1. Windows Settings → Apps → Apps & features
2. Find "Imposer"
3. Click "Uninstall"
4. Follow uninstaller wizard

**Via Start Menu:**
1. Start Menu → Imposer → Uninstall

**Portable Version:**
- Simply delete the executable; no system changes made

---

## Known Limitations

### File Locking ⚠️
- **Issue:** Files opened in Imposer are locked while the application runs
- **Workaround:** Close Imposer or load a different file to release the lock
- **Impact:** Minor; acceptable for typical workflows
- **Status:** Known limitation in PDF.js; may be addressed in future versions

### Publisher File Support ⚠️
- **Issue:** .PUB files cannot be directly imported
- **Workaround:** Convert Publisher files to PDF using Microsoft Publisher first
- **Instructions:** Open file in Publisher → File → Export as PDF → Import to Imposer
- **Status:** Requires external conversion tool

### Word Formatting ⚠️
- **Limitation:** Complex Word formatting (tables, floating elements, advanced styles) may not convert perfectly
- **Impact:** Basic documents convert well; complex layouts may need manual adjustment
- **Workaround:** Simplify formatting in Word before conversion, or export as PDF first

### Memory Usage ⚠️
- **Issue:** Very large documents (1000+ pages) may consume significant memory
- **Workaround:** Split large documents into sections
- **Recommendation:** Monitor system RAM when processing large files

### Custom Page Sizes
- **Limit:** Supports 1 to 200 inches (2.54 to 508 cm)
- **Outside Limits:** Use standard page sizes or resize within limits

---

## Architecture Support

✅ **64-bit (x64)** - Full support (native performance)  
✅ **32-bit (x86)** - Full support (slightly reduced memory capacity)

**Automatic Detection:**
The installer automatically selects the appropriate architecture for your system.

---

## Troubleshooting

### Application won't open
- **Solution:** Ensure Windows 7 SP1 or newer is installed
- **Check:** Windows Settings → System → About (view OS version)
- **Verify:** Administrator rights may be required on first launch

### Blank preview window
- **Solution:** Ensure file is a valid PDF format
- **Check:** Try opening a different PDF file
- **Verify:** File size (check file isn't corrupted)

### Word conversion fails
- **Solution:** Ensure file is saved in DOCX format (not macro-enabled XLSM)
- **Check:** Try saving in LibreOffice or Google Docs first
- **Verify:** Complex formatting may cause issues; simplify document

### Print shows blank pages
- **Solution:** Check print settings (margins, scaling)
- **Verify:** Ensure printer has adequate memory for large documents
- **Workaround:** Reduce page size or use multiple print jobs

### Files locked after use
- **Solution:** Close Imposer to release file locks
- **Why:** PDF.js maintains file references for rendering
- **Workaround:** Keep file locations accessible or copy to new location

---

## Documentation

Comprehensive user guide available at: `USER_GUIDE.md`

**Topics covered:**
- Getting started guide
- Feature walkthroughs with examples
- Common print industry workflows
- Tips & best practices
- Keyboard shortcuts reference
- Troubleshooting section

---

## What's Changed Since Previous Versions

### v0.4.0-beta (Current)
- ✨ Added multi-format file support (Word, Images, Publisher guidance)
- ✨ Implemented responsive preview scaling tied to window size
- ✨ Fixed print functionality with native system dialog
- ✨ Fixed Word multi-page conversion (all pages now included)
- ✨ Reorganized UI for better usability
- ✨ Added comprehensive user documentation
- ✨ Created professional installer with uninstaller
- ✨ Added 32-bit architecture support
- 🎨 Designed custom application icon
- 🔒 Updated license to proprietary

### v0.3.x (Previous)
- Basic N-up imposition
- PDF-only file support
- Simple preview system

---

## Performance Notes

| Task | Time | Performance |
|------|------|-------------|
| Open 10-page PDF | ~1-2 sec | Excellent |
| Render N-up layout (50 pages) | ~3-4 sec | Good |
| Convert Word document (5 pages) | ~2-3 sec | Good |
| Print 20-page document | ~5-8 sec | Excellent |
| Resize large document (500 pages) | ~15-20 sec | Fair* |

*Large documents dependent on available RAM and CPU

---

## Getting Help

**Issues or Questions?**
Contact: leondaspaul3@gmail.com

**Include in support requests:**
- Windows version and architecture (32-bit/64-bit)
- File format and size
- Exact steps to reproduce
- Error messages (if any)

---

## Future Roadmap (Post-Release)

- 🔲 Trial/licensing system with product key activation
- 🔲 Batch processing for multiple files
- 🔲 Advanced watermarking and stamping
- 🔲 Barcode and QR code generation
- 🔲 Template system for common layouts
- 🔲 Cloud document support
- 🔲 Keyboard shortcut customization
- 🔲 Dark mode theme option

---

## License & Legal

**License:** Proprietary (See LICENSE file)

This software is proprietary and confidential. Unauthorized copying, modification, distribution, or use is strictly prohibited. See LICENSE file for complete terms.

**Copyright © 2025** Leondas Paul, III (Galilee Gallery)

---

## Support & Contact

**Email:** leondaspaul3@gmail.com  
**Business:** Galilee Gallery  
**Location:** Print Industry Solutions

For technical support, feature requests, or licensing inquiries, please contact the email above.

---

**Version Information:**
- **Build:** 0.4.0-beta
- **Release Date:** December 6, 2025
- **Status:** Beta (Not for production use yet)
- **Next Release:** TBD (pending testing feedback)
