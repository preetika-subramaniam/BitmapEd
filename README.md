# BitmapEditor
A program that simulates a basic interactive bitmap editor. Bitmaps are represented as an M(width) x N(height) matrix of pixels with each element representing a color. Pixel co-ordinates may be between 1 and 250. Bitmap starts at coordinates 1,1. Colors are specified by capital letters.

Commands supported are:
1. I M N-   Create a new M x N image with all pixels colored white(O),
2. C-       Clears the table, setting all pixels to white(O),
3. L X Y C- Colors the pixel (X,Y) with color C,
4. S-       Shows the contents of the current image
