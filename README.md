# Convert images to .webp format for faster images on the web
This script has two functions: convert_to_webp(filename) and convert_all().

Use convert_to_webp to convert a single file to webp or use convert_all to crawl the folders and subfolders specified and convert every .png or .jpg to .webp format.

The original images will not be overwritten, rather, a new file with the same name as the original, but the .webp extension will appear.

The function, convert_to_webp, differentiates between .jpg and .png files and uses settings that provide the [best results for the filetype](https://www.youtube.com/watch?v=1lRNkyHTtR8). Some adjustments may be needed for individual images if the quality doesn't seem right, but these are the default settings I use as a professional marketing web dev.

Watch a full walkthrough here: https://youtu.be/wWd4Cg-cZ1w

If you prefer text walkthroughs, head over to the NDT blog: https://notdefined.tech/blog/auto-convert-all-images-to-webp-format-instant-load-time-improvement/

## Requirements
- Ideally, use a [virtual environment](https://www.youtube.com/watch?v=Kt2CbgwfJlE), python3
- Install Pillow ```pip install Pillow```

## How to Use
1. Put this script in a folder that also has a folder called 'images' (this can be changed, but out-of-the box defaults refer to a relative 'images' folder)
2. Put some .jpg or .png images in your /images folder
3. Create/activate your virtual environment
4. Make sure you have Pillow installed (see above)
5. Run the script! ```python convert-webp.py```
