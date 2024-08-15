Photo Organizer is a Python application designed to sort and organize your photo collection based on the date the photos were taken. This tool supports various image formats, including RAW formats from popular camera manufacturers.

Features:
EXIF Data Extraction: Automatically reads EXIF data from JPEG images to determine the date the photo was taken.
RAW Format Support: Handles multiple RAW image formats (e.g., .CR2, .NEF, .ARW) using rawpy to extract date information.
Date-based Organization: Sorts photos into folders named by year, month, and day based on the extracted date.
Fallback Sorting: If EXIF data is not available, the program uses the file’s last modification date as a fallback.
User-Friendly Interface: Provides a simple graphical user interface (GUI) built with Tkinter to select the folder containing your photos and initiate the sorting process.
