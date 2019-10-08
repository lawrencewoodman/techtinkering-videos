To convert a movie to an animated gif:

$ ffmpeg -i movie.mpg -filter_complex "[0:v] fps=12,scale=480:-1,split [a][b];[a] palettegen [p];[b][p] paletteuse" movie.gif

