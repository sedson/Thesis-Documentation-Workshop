# Thesis Documentation Workshop – pt. 2

## Wesleyan Art Studio 2021

Seamus Edson (he/him) – Graphic Design 2018

sedson@welseyan.edu – if you have questions or issues!

## File Requirements

#### Format and Quantity

- Up to 10 images in a RAW format (CR2, NEF, RAW, DNG are all OK).
- Up to 10 processed JPEGs, 4000 pixels on the long side (Adobe RGB color space preffered)
- If indicated by your advisor, please also submit time-based or interactive work in a format relevant to your particular medium.
- For additional information on supported time-based or interactive work file types, please contact wesscholar@wesleyan.edu

#### Naming Convention

Year_Medium_LastName_ImageNumber

#### Submission Link

[Submit Here](https://docs.google.com/forms/d/e/1FAIpQLSdTEo5e4PZmV98Fhplg8aZ9mg9BBXnt0_P0BGS3t8pmUVqBmw/viewform)


## Overview

1. Managing files with Finder or Bridge
1. Basic Editing and Color Correcting in Photoshop
1. Resizing and Exporting from Bridge


## 1 – Managing Files

Organizing your files will make things go smoother. You can do this with either Finder or Adobe Bridge, but Bridge is faster. The goal here is to have build a folder structure something like this:

```
📁 Thesis_Documentation
├── 📁 Source
    ├── 📷 DSCF0738.RAF
    ├── 📷 IMG_7435.CR2
    ...

└── 📁 2021_GraphicDesign_Edson_Raw
    ├── 📷 2021_GraphicDesign_Edson_01.RAF
    ...
    ├── 📷 2021_GrapicDesign_Edson_10.dng

└── 📁 2021_GraphicDesign_Edson_Processed
    ├── 🖼️ 2021_GraphicDesign_Edson_01.jpg
    ...
    ├── 🖼️ 2021_GraphicDesign_Edson_10.jpg

└── 📁 Working_Files
    ├── 📝️ 2021_GraphicDesign_Edson_01.psd
    ...
    ├── 📝️ 2021_GraphicDesign_Edson_10.psd
```

### With Adobe Bridge

Gather all your raw photos in a single place (on a memory card or external drive if working on a lab machine). I wish had made (at least) two copies of this drive! I put all my thesis photos on one memory card which I lost on move out day – so about half of my orignal photo files are gone.

Create a folder for your raw selects and for your edited selects.

Open Adobe Bridge and navigate to your working location – ex: `Computer > MemoryCard > Thesis > Photos` (Make sure you are in the `Essentials` workspace.)

Drag this folder onto the `Favorites` area so you can access it quickly. Also drag your `RAW` folder into favorites.

Find the `Collections` tab (middle left) and right click to create a new collection.

Add photos to your collection with drag and drop.

Can play around with using the star ratings and filters to narrow down photos.

Once you have the 10ish photos in your collection, copy them into your raw folder by holding `Option` and dragging! **Important that you hold `option` the whole way – or else you'll be moving the files rather than copying them!!!** Another option here (my preference) is creating an export preset – see the section at the bottom.
Now open the RAW folder and you can drag to rearrange the order of your files.Now you can rename them - either one at a time or choose `Batch Rename` and fiddle with the settings to rename them all at once

The RAW folder is now done, provided that you don't plan on adding or removing photos.

## 2 – Processing and Editing Photos
In Bridge (or Finder), duplicate the RAW folder and rename it something like `working_files` – this is where photoshop documents are going to live

To start processing, double click on a photo from Bridge. If it is a RAW file, it will open in the raw Editor. Here are the most important settings:

In the EDIT PANEL (E)

> BASIC AREA
> - `Basic > White Balance` is the best way to adjust the overall color temperature – use the eye-dropper then click on a nuetral pert of the image to get a head start
> - `Basic > Exposure` to set the overall brightness
> - Play around with the rest of the Basic settings to get the image looking how you want

> OPTICS AREA - for dealing with known distortions caused by camera or lens
> - I like to test both `Optics > ✅ Remove Chromatic aberration` and `✅ Use profile corrections` to see if it imporves the image quality

> GEOMETRY AREA - for adjusting perspective distortion
> - I prefer to do these corrections in Photoshop – but this is sometimes quicker

> CURVE AREA - fine tuned image control
>  -The `Targeted adjustment tool (T)` is really good for getting intuitive contol over certain regions of the image.

In the CROP PANEL (C)

> Crop (obviously)
> - But also Straighten – double click the little ruler to do an auto Straighten, or click it once then draw a line on your image where you want it to be straight

If you are happy with these changes, hit `Done`. If you want to edit further in Photoshop hit `Open`.

Once you open the photo in photoshop, save it as a `.PSD` inside the `working_files` folder. That way you can export to the final jpegs all from Bridge.

## 3 – Resizing and Exporting

This is going to be a quick one. In Bridge, find the `Export` area (left middle). Press the `+ Create new Preset Button` and update the settings to match these – make sure to chose `Specific Folder` and select your `...Edited` folder: 

![export jpeg](screenshots/export_jpeg.png)

For the earlier step – you can use these settings to export the raw files to your RAW folder:

![export jpeg](screenshots/export_settings.png)

Then to export, all you have to do is drag your file onto the export preset and click `Export`


