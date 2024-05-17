Key Components
Setup:
Updated the development container to the latest version.
Created a new directory named ex07_compstagram.
Copied provided support files (support.py and compstagram.py) into the directory.

Support Code:
Color Class: Represents a digital color with red, green, and blue components.
Bitmap Class: Represents a digital image as a 2D list of Color objects.
Filter Protocol: Defines the structure of filter classes.
Request Class: Captures user requests to apply filters to images.

Filters Implemented:
Invert Filter (Provided): An example filter that inverts image colors.
Border Filter: Adds a colored border around the image. The thickness of the border is determined by a user-defined amount.
Brightness Filter: Adjusts the brightness of the image. The amount controls how much lighter or darker the image becomes.
Saturation Filter: Adjusts the color intensity of the image. A lower amount desaturates the image, making it grayscale.
Stacking Filters:

Modified the main function to apply multiple filters sequentially, allowing for complex image transformations.
