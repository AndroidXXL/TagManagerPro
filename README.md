# TagManagerPro

[![Version](https://img.shields.io/badge/Version-3.0-blue.svg)](https://github.com/tagManagerPro)
[![Python](https://img.shields.io/badge/Python-3.8+-green.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

TagManagerPro is a comprehensive tag management application for image files, designed to help you organize, edit, and manage tags across single images or entire collections. It integrates with online booru databases for tag insights, offers AI-powered tag suggestions, and provides powerful batch operations.

## Table of Contents

- Features Overview
- Interface Guide
- Tag Management
- Image Browser
- AI Tagging
- Tag Information
- Keyboard Shortcuts
- Advanced Features
- Settings

## Features Overview

### Core Functionality

- **Tag Management**: Add, edit, remove, and reorder tags for image files
- **Dual Operation Modes**: Work with single images or perform operations across entire directories
- **Tag Visualization**: See tag frequencies and generate word clouds
- **Online Integration**: Auto-complete tags from Gelbooru and retrieve tag information from Danbooru
- **AI Tagging**: Get automatic tag suggestions using AI image recognition

### Key Features

- **Smart Tag Operations**:

  - Add/remove/edit tags on individual or multiple files
  - Conditional tag operations ("if this tag exists, add that tag")
  - Find files with specific tags or missing tags
  - Add tags to all files in a directory at once
  - Reorder tags within files
- **Image Management**:

  - Browse images with thumbnail previews
  - Zoom mode for detailed examination of thumbnails
  - View and edit image metadata
  - Resize images without leaving the application
  - Resize thumbnails for customized viewing
  - Intuitive navigation between images
- **AI and Online Integration**:

  - AI-powered automatic tag suggestions
  - Tag autocompletion from Gelbooru database
  - Tag information lookup via Danbooru
  - Post examples for tags with preview images
- **Visual Analysis**:

  - Interactive word cloud generation
  - Tag frequency analysis
  - Tag relationship exploration

## Interface Guide

### Main Tabs

TagManagerPro features a tabbed interface with three main sections:

1. **Tag Operations**: Global operations on all files in a directory
2. **Image Browser**: View and edit tags for individual images
3. **Options**: Configure application settings and keyboard shortcuts

### Console Output

The bottom section displays a console with operation logs and results:

- See which files were modified
- Track tag changes
- View operation summaries
- Adjust console font size with dedicated buttons

## Tag Management

### Global Tag Panel

The global tag panel allows you to perform operations on all files in a directory:

- **Tag Display**: See all unique tags across your files with their frequency counts
- **Tag Sorting**: Toggle between alphabetical sorting, file order, and booru count sorting
- **Search**: Filter tags by name to quickly find what you need
- **Improved Layout**: Better reflow of tags for improved visibility and organization
- **Tag Operations**:

  - Add new tags
  - Edit existing tags
  - Move tags to specific positions
  - Remove tags
  - Add a tag to all files
  - Find files containing a specific tag (now directly linked to image browser display)
  - Convert escaped parentheses with the "Convert \\( to (" button

### Single Image Tag Panel

When working with individual images:

- Edit tags for the current image
- View tag counts from booru databases
- Toggle visibility of tag occurrence counts
- Add, edit, move and remove tags
- Sort tags in different ways
- Commit changes to save to disk

### Tag Information

Right-click on a tag to access detailed information:

- **Wiki Information**: View wiki descriptions from Danbooru
- **Example Images**: See sample posts featuring the tag
- **Related Tags**: Discover commonly co-occurring tags
- **Usage Statistics**: See how frequently the tag is used

## Image Browser

### Browsing Features

- **Thumbnail View**: See a grid of image previews with filenames
- **Zoom Mode**: Middle-click on thumbnails to open a zoomable view in a new window
- **Thumbnail Resizing**: Adjust thumbnail size directly in the interface
- **Image Navigation**: Use arrow keys to move between images
- **Search**: Filter images by filename or use OR operator (||) to display multiple specific images
- **Image Details**: View dimensions, format, and other metadata
- **Direct Opening**: Open images in your system's default viewer

### Image Operations

- **Resize Images**: Change image dimensions while maintaining aspect ratio
- **Tag Management**: Edit tags directly from the browser
- **Cache Management**: Efficient thumbnail caching for improved performance

## AI Tagging

### Automatic Tag Suggestions

- **AI Recognition**: Get tag suggestions using neural network image recognition
- **Tag Comparison**: See suggested tags compared to existing tags
- **Selective Application**: Choose which AI tags to apply
- **Batch Processing**: Apply AI tagging to all images in a directory

### Tag Comparison Window

When using AI tag suggestions, a comparison window shows:

- **Current Tags**: Tags already in the image's text file
- **Common Tags**: Tags present in both the file and AI suggestions
- **AI Tags**: New tags suggested by the AI
- **Operations**: Apply selected tags or replace all existing tags

## Tag Information

### Detailed Tag Insights

Access comprehensive information about any tag:

- **Wiki Entries**: Detailed descriptions from booru wikis
- **Example Posts**: Browse sample images using the tag
- **Tag Statistics**: View usage count and popularity
- **Related Tags**: Discover frequently co-occurring tags
- **External Links**: Quick links to search for the tag on various booru sites

## Keyboard Shortcuts

TagManagerPro features fully customizable keyboard shortcuts:

### Default Global Panel Shortcuts

- **Ctrl+A**: Add tag
- **Ctrl+D**: Edit selected tag
- **Ctrl+R**: Remove selected tag
- **Ctrl+M**: Move selected tag
- **Ctrl+S**: Commit changes
- **Ctrl+W**: Add selected tag to all files
- **Ctrl+F**: Find files with selected tag
- **Ctrl+Q**: Show tag information
- **Ctrl+Z**: Toggle tag sorting
- **Ctrl+C**: Refresh/reset tags

### Default Image Panel Shortcuts

- **Ctrl+A**: Add tag
- **Ctrl+D**: Edit selected tag
- **Ctrl+R**: Remove selected tag
- **Ctrl+M**: Move selected tag
- **Ctrl+S**: Commit changes
- **Ctrl+Q**: Show tag information
- **Ctrl+Z**: Toggle tag sorting
- **Ctrl+C**: Refresh/reset tags

### Navigation

- **Left/Right Arrows**: Navigate between images
- **Up/Down Arrows**: Navigate between tabs
- **Enter**: Submit in Conditional and Find Missing widgets

## Advanced Features

### Word Cloud Generation

- **Visual Tag Analysis**: Generate word clouds based on tag frequency
- **Interactive View**: Zoom and pan to explore the word cloud
- **Custom Sizing**: Adjust size and scale

### Conditional Tag Operations

Add tags based on the presence of other tags:

- If a specific tag exists in a file, automatically add another tag
- Great for maintaining tag hierarchies or relationships
- Submit operations with Enter key for faster workflow

### Finding Missing Tags

Search for files that have one tag but are missing another:

- Useful for finding inconsistently tagged files
- Helps maintain tag standards across collections
- Enter key support for quick searching

### Batch Operations

- **Enhanced Batch Processing**: Improved "Batch All Images" functionality with dedicated window
- **Multiple Options**: Choose between appending, overwriting, or creating new tag files
- **Batch AI Tagging**: Apply AI suggestions to multiple images at once

## Settings

### Application Settings

- **File Matching**: Choose how text files are matched to images (by name or alphabetically)
- **Tag Sorting**: Set default tag sorting behavior (alphabetical, file order, or booru count)
- **Font Size**: Adjust console font size for better readability
- **Keyboard Shortcuts**: Customize all shortcut keys
- **Custom Themes**: Select from various visual themes for the application
- **Tag Display**: Toggle visibility of tag occurrence counts in the image panel

### Cache Management

- **Tag Count Cache**: Store and manage booru tag counts for faster operation
- **Image Cache**: Efficient thumbnail caching for improved browsing performance

---

## System Requirements

- Python 3.8 or later
- Required packages: tkinter, ttkbootstrap, pillow, wordcloud, requests, beautifulsoup4, platformdirs, gradio_client

## Installation

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run the application: `python main.py`

---

TagManagerPro is designed to help you efficiently manage tags for your image collection, whether you're organizing a small set of personal images or maintaining a large library of tagged content.
