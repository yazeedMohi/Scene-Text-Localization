# Scene-Text-Localization

Simple Java implementation for Christian's and Berkeley's algorithms for clock synchronization.

This code was written in a modular fashion that allows easy usage of new architectures and datasets, the reader portion already provides the ability to read from the following datasets
- TotalText
- ICPR part 1
- ICPR part 2
- StreetViewText dataset

Usage:
- Open the file STL.ipynb in colab, mount the drive.
- Upload the dataset that is to be used to your google drive, unzip its folder in colab using the command: !unzip "path/to/file"
- Use the function "Main" to run the code, help with usage for this function is shown in the code as a text block.
- You can add new architectures by openning the "Models" cell and adding your model the same way the model "east" is written.
- You can add new datasets by defining their file structure in the "reader" cell, check the code for the other datasets for reference.
- Enjoy!

Please don't hesitate to contact me regarding issues with this code, peace out!
