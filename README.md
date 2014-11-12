# Advanced Slicing for 3D Printing

This is a workshop we hold at Solid State Depot.  It covers the file conversion process to transform STL files into GCode files that are ready for 3D printing.  We focus on Slic3r here.

This is an S5 presentation.  There is a printer-friendly version.

## Demo Parts and GCode
There are a growing number of parts that provide samples of how different parameters change the GCode output.  They are zipped in lets_slice/lets_slice.zip.  Extract this file to use them.  The GCode files are in lets_slice/gcode (unzipped).  Actually, there are subfolders that contain the GCode - the names of these folders correspond to the version of GCode that generated the file.  Each subfolder should have an Open Office Spreadsheet (.ODS file) with a legend for _each_ GCode file.

## Contribute
If you want to contribute more parts and/or sample GCode files, please follow these guidelines:
+ Follow the naming convention for GCode folders, i.e. version of Slic3r.
+ Use a very verbose name for the GCode file, as has been attempted.
+ Update or create a new Open Office Spreadsheet legend file with a better description of the parameters used for the GCode.  Even verbose names will be forgotten.