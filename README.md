# Advanced Markdown Journal Documentation

## Overview
Advanced Markdown Journal is a sophisticated web-based journaling application that combines the power of Markdown formatting with modern web technologies. It provides users with an intuitive interface for creating, managing, and publishing journal entries while offering advanced features like theme switching, real-time preview, and a comprehensive publication system.

## Core Features

### User Interface Components

#### Header Section
- Editable journal title using the elegant Grey Qo font family
- Theme toggle button (🌓) for switching between light and dark modes
- Persistent title saving across sessions

#### Sidebar Navigation
- "New Entry" button for creating fresh journal entries
- Dynamic entry list showing titles and dates
- Delete functionality for individual entries
- Click-to-load entry selection

#### Content Area
- Dual-pane system with Editor and Preview tabs
- Real-time Markdown preview rendering
- Publishing functionality with HTML export
- Markdown formatting toolbar

### Writing and Editing Features

#### Rich Text Formatting
The application supports comprehensive Markdown syntax with quick-access buttons for:
- **Bold** text formatting
- *Italic* text styling
- Headings (multiple levels)
- Bulleted lists
- Numbered lists
- Links
- Images
- Inline code
- Blockquotes
- Horizontal rules

#### Editor Capabilities
- Auto-saving functionality
- Real-time preview updates
- Content persistence across sessions
- Clean, distraction-free writing environment

### Publication System

#### Publishing Features
- HTML export of entries
- Automatic styling of published content
- Responsive layout for published entries
- Author attribution
- Publication date tracking
- Unique URL generation for each published entry

#### Publication Index
- Collapsible sidebar for published entries
- Hierarchical organization by year and month
- Quick access to published content
- Persistent storage of published entries

### User Experience Features

#### Theme Management
- Light and dark theme options
- Persistent theme preference storage
- Smooth transition animations
- Consistent styling across all components

#### Notifications
- Toast notification system
- Success/error message display
- Temporary notification display
- Interactive notification dismissal

#### Data Management
- Local storage implementation
- Automatic entry saving
- Data persistence across sessions
- Entry organization and management

### Technical Implementation

#### Font System
The application uses a sophisticated font system including:
- Multiple font weights (100-900)
- Italic variants
- Custom font families (Kanit and Grey Qo)
- Responsive typography

#### Visual Design
- Embossed and engraved text effects
- Dotted border styling
- Smooth transitions and animations
- Responsive layout design

#### Security Features
- Content sanitization using DOMPurify
- Safe HTML rendering
- Protected content publishing
- Secure content management

## User Customization

### Author Information
- Author name storage
- Initial setup modal
- Persistent author attribution
- Default anonymous fallback

### Entry Management
- Title extraction from content
- Date stamping
- Entry organization
- Deletion confirmation

### Interface Customization
- Theme preference saving
- Journal title customization
- Publication index visibility toggle
- Layout persistence

## Technical Requirements

### Dependencies
- Marked.js for Markdown parsing
- DOMPurify for content sanitization
- Google Fonts for typography
- Modern web browser with localStorage support

### Browser Support
- Modern browsers with ES6+ support
- LocalStorage API support
- CSS3 features support
- Flexible viewport handling

## Best Practices for Usage

### Writing Workflow
1. Create a new entry using the "New Entry" button
2. Write content using Markdown syntax
3. Use the formatting toolbar for quick formatting
4. Preview content in the Preview tab
5. Publish when ready

### Content Management
1. Regular saving is automatic
2. Use meaningful titles for better organization
3. Preview before publishing
4. Maintain regular backups of important entries

### Publishing Guidelines
1. Review content in preview mode
2. Ensure proper formatting
3. Add appropriate metadata
4. Verify author attribution
5. Use the publication index for organization

## Performance Considerations

### Data Storage
- Efficient use of localStorage
- Automatic garbage collection
- Optimized data structures
- Regular cleanup recommendations

### Rendering Performance
- Efficient DOM updates
- Optimized style calculations
- Smooth animations
- Responsive design principles
