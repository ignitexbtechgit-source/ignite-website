# Event Images Setup Guide

## Folder Structure
```
ignite-website/
├── images/
│   └── events/
│       ├── idea-pitching.jpg
│       ├── iedc-orientation.jpg
│       ├── technical-talk.jpg
│       └── power-bi-workshop.jpg
├── index.html
└── ...
```

## How to Add Event Images

### Step 1: Upload Images via GitHub Web Interface
1. Navigate to the `images/events/` folder in the repository
2. Click **"Add file"** → **"Upload files"**
3. Select your event photos and upload them
4. Name your files exactly as follows:
   - `idea-pitching.jpg` - for Idea Pitching event
   - `iedc-orientation.jpg` - for IEDC Orientation event
   - `technical-talk.jpg` - for Technical Talk event
   - `power-bi-workshop.jpg` - for Power BI Workshop event
5. Commit with message: **"Add event images"**

### Step 2: Recommended Image Specifications
- **Format**: JPG, PNG, or WebP
- **Dimensions**: 600x400px minimum (recommended)
- **File Size**: Keep under 500KB for faster loading
- **Quality**: High-quality, well-lit event photos
- **Content**: Show participants, speakers, activities, or venue setup

### Step 3: How It Works
- Images are stored locally in the `images/events/` folder
- If a local image fails to load, it automatically falls back to CDN backup URLs
- This ensures your site works even if images haven't been uploaded yet

### Step 4: Supported Image Formats
- JPEG (.jpg, .jpeg)
- PNG (.png)
- WebP (.webp)

## Fallback System (CDN Backups)
If images don't load from the local folder, these backup images are automatically used:
- Idea Pitching: https://i.postimg.cc/QtG16kLw/idea.jpg
- IEDC Orientation: https://i.postimg.cc/vTJRfrFs/Orientation.jpg
- Technical Talk: https://i.postimg.cc/vBfMN3rc/Technical-talk.jpg
- Power BI Workshop: https://i.postimg.cc/T2cW31Cg/MSME.jpg

## Example Images
Great event photos to upload:
- Students participating in the workshop
- Presenter/Speaker during the event
- Group photos of attendees
- Awards or certificates being distributed
- Classroom or venue setup
- Hands-on activities or demonstrations

## Testing After Upload
1. Clear your browser cache (Ctrl+Shift+Delete or Cmd+Shift+Delete on Mac)
2. Refresh the website page
3. Click on the "Past Events" tab under "Tech Events"
4. Verify all 4 event images display correctly

## Current Events Listed
1. **Idea Pitching** - 21-03-2025
2. **IEDC Orientation** - 29-07-2025
3. **Technical Talk** - 02-08-2025
4. **Power BI Workshop** - 11-08-2025

## Troubleshooting
- **Images not showing?** Check that file names exactly match the list above (case-sensitive)
- **Slow loading?** Compress images to reduce file size
- **Wrong image displayed?** Clear browser cache and refresh
- **Need to update an image?** Simply re-upload with the same filename to replace it

## Next Steps
1. ✅ Folder structure created (`images/events/`)
2. ✅ HTML updated to reference local images
3. ⏳ **TODO**: Upload actual event photos to the `images/events/` folder
4. ⏳ **TODO**: Merge the `add-event-images` branch to `main`
