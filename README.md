Original file[https://drive.google.com/file/d/1DvB7giKe5sbD-8FTDv9h0OmYDKv5v6V0/view?usp=sharing] error: Used deprecated vertex_colors API in Blender 4.2, causing removal error due to empty names.
Refinement: Replaced with color_attributes API, and set temporary name "temp" for empty attributes before removal to avoid the error.
