# To Normalise audio

$ ffmpeg -y -i movie.mp4  -filter:a loudnorm=print_format=summary -f ogv /dev/null

Supply the measured values below from the input values in the output above:

$ ffmpeg -i movie.mp4 -filter:a loudnorm=measured_I=-24.4:measured_TP=-2.1:measured_LRA=6.5:linear=true nmovie.mp4

# To Increase the Volume of a Movie

$ ffmpeg -i nmovie.mp4 -af "volume=3" lmovie.mp4
