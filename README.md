# image_scraper
An image scraper module to collect images with the given query.
  TODO: use ArgParse
  TODO: Duplicate check
  TODO: Params from config file

# image_prep
Image preprocessor for Image database suite.
  TODO: #LoG
  TODO: Split for Tiles
  TODO: Contrast?
  Optional TODO: Make a Cpp/CUDA version with tf

# manual_tool
Manual labeling script for image datasets
  -Binary option
  -take in input folder
  -Assign key to each class name
  -Skip option to decide later

# auto_label
Automatically label images (patches) based on bitmask population

# bitmask_tool
Label image regions using edge detection and image markup

# tile_maker
Extract image patches and save to folders using scikit-learn

# seg_to_bitmask
Create bitmasks and merge them to images using .seg files that contain the labeled row
data

# folders
  take the functions out of @label_tool and @tile_maker (or maybe others)
  organize them into a Folder class
