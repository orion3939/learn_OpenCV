FLAGS = -Wall -O2 -std=c++11
INCLUDES = -I/usr/local/include/opencv -I/usr/local/include  
LIBS = -lm -L/usr/local/lib -lopencv_shape -lopencv_stitching -lopencv_objdetect -lopencv_superres -lopencv_videostab -lopencv_calib3d -lopencv_features2d -lopencv_highgui -lopencv_videoio -lopencv_imgcodecs -lopencv_video -lopencv_photo -lopencv_ml -lopencv_imgproc -lopencv_flann -lopencv_core -lopencv_hal

squares:squares.cpp
	g++ -o squares squares.cpp ${FLAGS} ${INCLUDES} ${LIBS}
