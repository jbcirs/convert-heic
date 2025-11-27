# Output Images Folder

Converted images are automatically saved in this folder.

## What You'll Find Here

After running the converter, you'll see your converted images here with the same base filename as the source files, but with a new extension based on the output format you chose.

**Note**: The output folder is automatically cleared before each conversion to ensure fresh results. Only the README.md file is preserved. If you want to keep previous conversions, move them elsewhere first or use the `--no-clear` option.

## Output Formats

The output format depends on the conversion option you selected:

### PNG Format (`.png`)
- **Lossless quality** - No loss of image data
- **Transparency preserved** - If source has transparency
- **Larger file sizes** - Typically 2-5 MB per image
- **Best for**: Editing, archival, images with transparency

### JPG Format (`.jpg`)
- **Lossy compression** - Slight quality loss (usually imperceptible at high quality)
- **Adjustable quality** - 1-100 scale (default: 95)
- **Smaller file sizes** - Typically 0.5-2 MB per image
- **Best for**: Sharing via email, web use, social media

### PDF Format (`.pdf`)
- **Document format** - Each image becomes a one-page PDF
- **Print-ready** - Properly sized for standard paper
- **Page sizes**: Letter (8.5" × 11") or A4 (210mm × 297mm)
- **Best for**: Printing, document archival, professional use

## File Naming

Output files maintain the same base name as the source file:

```
Source: IMG_1234.heic  →  Output: IMG_1234.png
Source: vacation.HEIC  →  Output: vacation.jpg
Source: photo.heif     →  Output: photo.pdf
```

## File Organization

- Files are saved with **alphabetical ordering** matching source files
- **No subdirectories** are created - all outputs are in this folder
- If a file with the same name exists, it will be **overwritten**

## What to Do Next

### Viewing Your Files
- **PNG/JPG**: Open with any image viewer or web browser
- **PDF**: Open with Adobe Reader, web browser, or system PDF viewer

### Sharing Your Files
- **Email**: JPG format at quality 85-90 recommended
- **Social media**: JPG format works best
- **Cloud storage**: Any format works; PNG for archival
- **Printing**: PDF format recommended

### Further Processing
- **Photo editing**: Use PNG format for maximum quality
- **Batch operations**: All files are ready for further processing
- **Archival**: Keep both HEIC originals and PNG/PDF copies

## File Sizes (Typical)

For a 12-megapixel image (4000×3000 pixels):
- **HEIC original**: ~1.5 MB
- **PNG output**: ~10-15 MB (lossless)
- **JPG output (quality 95)**: ~2-3 MB
- **JPG output (quality 85)**: ~1-1.5 MB
- **PDF output**: ~2-4 MB (depends on compression)

## Troubleshooting

**No files appearing here?**
- Check that source files are in `../source/` folder
- Verify conversion completed without errors
- Check the log files in `../../logs/` folder

**Files look low quality?**
- For JPG: Increase quality setting (use `-q 95` or `-q 100`)
- For PNG: Quality is always lossless
- For PDF: Try different page size setting

**Can't open files?**
- Ensure you have appropriate software installed
- Try opening in a web browser
- For PDF, install Adobe Reader or use built-in PDF viewer

**Files too large?**
- Use JPG format with lower quality (70-85 range)
- PNG is always lossless and larger
- Consider if you really need maximum quality

## Cleaning Up

- You can safely **delete converted files** to free up space
- **Original HEIC files** in `../source/` are never touched
- You can **reconvert** anytime by running the converter again

## Need Help?

- Check the main **README.md** in the project root
- Review **log files** in the `../../logs/` folder
- Run with `-v` flag for verbose debugging output

---

**Your converted images are ready to use! 🎉**
