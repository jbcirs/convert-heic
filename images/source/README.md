# Source Images Folder

Place your HEIC/HEIF image files in this folder to convert them.

## Supported File Extensions

The converter automatically detects and processes files with these extensions:
- `.heic`
- `.HEIC`
- `.heif`
- `.HEIF`

## Instructions

1. **Copy your HEIC files** from your iPhone, camera, or other sources into this folder
2. **Run the converter** using one of these methods:
   - Windows: `cd src` then `.\convert_heic.bat`
   - Unix/Mac: `cd src` then `./convert_heic.sh`
   - Command line: `cd src` then `python convert_heic.py -f [format]`
3. **Check the output** in the `../output` folder

## Tips

- You can add multiple HEIC files at once - the converter processes them all in one go
- File names are preserved (only the extension changes)
- Original files are never modified or deleted
- Subfolders are not scanned - only files directly in this folder

## Getting HEIC Files

**From iPhone/iPad:**
- Connect device via USB
- Open File Explorer (Windows) or Finder (Mac)
- Navigate to your device's Photos
- Copy HEIC files to this folder

**From iCloud:**
- Download photos from iCloud.com
- Save with original format (HEIC)
- Copy to this folder

**From Email/Cloud Storage:**
- Download attachments
- Ensure they're saved as `.heic` format
- Copy to this folder

## Example

If you add these files:
```
source/
├── IMG_1234.heic
├── IMG_1235.HEIC
├── vacation.heif
└── photo.HEIF
```

After conversion (to PNG), you'll get:
```
output/
├── IMG_1234.png
├── IMG_1235.png
├── vacation.png
└── photo.png
```

Need help? Check the main README.md in the project root.
