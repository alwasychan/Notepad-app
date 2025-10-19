# Simple Notepad in Python

## Overview
A lightweight, cross-platform notepad application built with Python and Tkinter. This simple text editor provides essential features for basic text editing with an intuitive graphical interface.

## Features

### File Operations
- **New File**: Create a new text document (Ctrl+N)
- **Open File**: Open existing text files (Ctrl+O)
- **Save File**: Save current document (Ctrl+S)
- **Save As**: Save document with a new name (Ctrl+Shift+S)
- **Exit**: Quit the application with confirmation

### Edit Operations
- **Cut**: Cut selected text (Ctrl+X)
- **Copy**: Copy selected text (Ctrl+C)
- **Paste**: Paste text from clipboard (Ctrl+V)
- **Select All**: Select all text in the document (Ctrl+A)

### User Interface
- **Scrolling Text Area**: Comfortable text editing with scrollbars
- **Status Bar**: Real-time cursor position tracking (line and column)
- **Keyboard Shortcuts**: All major operations have keyboard shortcuts
- **Font**: Uses Ubuntu Mono font for better readability

## Requirements

### Python Dependencies
- Python 3.x
- Tkinter (usually included with Python standard library)

### System Requirements
- Windows, macOS, or Linux
- Python 3.6 or higher

## Installation

1. Ensure Python is installed on your system
2. Save the provided Python code as `notepad.py`
3. Run the application using:
   ```bash
   python notepad.py
   ```

## Usage

### Starting the Application
```bash
python notepad.py
```

### Basic Operations
1. **Creating a new file**: Use File → New or Ctrl+N
2. **Opening a file**: Use File → Open or Ctrl+O
3. **Saving files**: Use File → Save or Ctrl+S for existing files, Ctrl+Shift+S for new names
4. **Text editing**: Use standard editing shortcuts or the Edit menu

### Supported File Formats
- Text files (.txt)
- All file types (with .txt as default extension)

## Keyboard Shortcuts

| Operation | Shortcut |
|-----------|----------|
| New File | Ctrl+N |
| Open File | Ctrl+O |
| Save File | Ctrl+S |
| Save As | Ctrl+Shift+S |
| Cut | Ctrl+X |
| Copy | Ctrl+C |
| Paste | Ctrl+V |
| Select All | Ctrl+A |

## Technical Details

### Class Structure
- `NotepadApp`: Main application class handling all functionality
- Uses Tkinter for GUI components
- Implements scrolled text widget for content area

### Key Components
- **Menu System**: File, Edit, and Help menus
- **Text Area**: Scrollable text editing widget
- **Status Bar**: Displays current cursor position
- **File Dialogs**: Native system dialogs for file operations

## Error Handling
- File read/write error messages
- Graceful exit confirmation
- Exception handling for file operations

## Customization
The application can be easily modified by:
- Changing the font in the `text_area` initialization
- Modifying window dimensions in the `geometry` call
- Adding new menu items to the existing structure

## Limitations
- Basic text editing only (no rich text formatting)
- No syntax highlighting
- No multiple document interface (MDI)
- Limited to system's default text encoding

## Development
Created by Xperia1iichan  
Contact: @Xperia1iichan (X)

## License
This is a simple educational project. Feel free to modify and distribute.

## Future Enhancements
Potential improvements could include:
- Tabbed interface for multiple files
- Syntax highlighting for code
- Find and replace functionality
- Theme support (light/dark mode)
- Print functionality
- Auto-save feature

---

*Note: This application is designed for basic text editing needs and demonstrates Python GUI programming with Tkinter.*

