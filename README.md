# YOLO-for-table-detection
This file contains the code used to build a YOLO (version 4) object detection model which was used detect tables in images of PDF pages. The image coordinates can then be extracted, converted to PDF coordinates and used to guide libraries like Camelot to accurately locate tables nested within text. The model has mainly been trained on tables nested within text, and may not perform well on large, full page tables.

The code follows the tutorial shared by the youtube channel "The AI Guy" which is available at https://www.youtube.com/watch?v=mmj3nxGT2YQ.
