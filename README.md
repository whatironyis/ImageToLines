# ImageToLines
Convert grayscale image to one dark line.

[TODO]
1. Find best technology stack to convert image to lines (C++ and QT, or JavaScript or Python or maybe something else)

[Algorithm]
1. Convert image to matrix of pixels in RGB?
2. Take first point p0 and find in image matrix the darkest line (mean of pixels in image matrix)
3. Draw this line
4. Weakean (brighten) line in image matrix.
5. Repeat from step 2.

[Bibliography]
1. https://mathematica.stackexchange.com/questions/183617/converting-image-to-full-length-lines
2. https://mathematica.stackexchange.com/questions/45753/bresenhams-line-algorithm/45806#45806
3. https://pl.wikipedia.org/wiki/Algorytm_Bresenhama
4. http://linify.me/
5. 
