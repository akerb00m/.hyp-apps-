# Bio-Links - Hyperfy V2 App

A customizable screenspace UI system for creating bio links and download sections in your Hyperfy V2 world. This app creates a toggleable interface that can display multiple buttons with custom text and links.

## What it does

When you drop this app into your Hyperfy world, it will:
- Create a small toggle button in the top-right corner of the screen
- Display a header section with customizable text
- Show multiple configurable buttons that can link to external URLs
- Allow users to toggle the entire interface on/off
- Hide the original GLB model (optional)

Perfect for creating download sections, bio links, social media links, or any other external link collection in your world.

## UI Configuration Options

### Number of Buttons
- **What it does**: Controls how many clickable buttons are created
- **Range**: 1 to 14 buttons
- **Default**: 8 buttons
- **Tip**: More buttons create a longer scrollable interface

### Header Text
- **What it does**: Sets the text displayed in the header section
- **Type**: Text input
- **Default**: "Download Section"
- **Tip**: Use this to explain what the buttons are for (e.g., "My Links", "Downloads", "Social Media")

### Cube Visible
- **What it does**: Controls whether the original GLB model is visible in the world
- **Options**: Show/Hide
- **Default**: Show
- **Tip**: Hide the cube if you only want the UI interface without a visible object

### Button Configuration (Dynamic)
For each button (1-14), you can configure:

#### Button Text
- **What it does**: Sets the text displayed on each button
- **Type**: Text input
- **Default**: "link 1", "link 2", etc.
- **Tip**: Use descriptive text like "Download App", "Visit Website", "Follow on Twitter"

#### Link URL
- **What it does**: Sets the URL that opens when the button is clicked
- **Type**: Text input (URL)
- **Default**: Empty
- **Tip**: Must be a complete URL including "https://" or "http://"

## How it works

1. **Toggle Button**: A small arrow button (▲/▼) in the top-right corner
2. **Header Section**: A larger button displaying your header text
3. **Link Buttons**: Individual buttons stacked vertically below the header
4. **Hover Effects**: Buttons change color when hovered over
5. **Click Actions**: Clicking a button opens the configured URL in a new tab

## Usage Tips

1. **URL Format**: Always include the full URL with protocol (https://example.com)
2. **Button Text**: Keep button text short and descriptive
3. **Performance**: More buttons may impact performance on slower devices
4. **Placement**: The UI is screenspace, so it appears on the screen regardless of where you place the app in the world
5. **Customization**: Use the header text to explain what the section contains

## Technical Details

- **UI Position**: Top-right corner of the screen
- **Button Size**: 300px wide, 50px tall (header is 70px tall)
- **Colors**: Dark background with white text, hover effects included
- **Responsive**: Automatically adjusts to screen size
- **External Links**: Opens URLs in new browser tabs

## Author

**Gert-Jan Akerboom**
- Twitter: [@GertJanAkerboom](https://x.com/GertJanAkerboom)
- License: MIT
- Copyright (c) 2025 Gert-Jan Akerboom 