# FaceDetector Makefile by Olivia Stone for Code Clinic: C++
CC		= g++
CFLAGS	= -std=gnu++17
TARGET	= FaceDetector
SRC		= FaceDetectorMain.cpp FaceDetector.cpp jsoncpp.cpp
INCLUDES = -I/usr/local/Cellar/giflib/5.2.1/include\
					 -I/usr/local/Cellar/opencv/4.4.0_1/include/opencv4

LDLIBS	= -lgif -lopencv_core -lopencv_imgcodecs -lopencv_highgui -lopencv_imgproc -lopencv_objdetect

$(TARGET): $(SRC)
	$(CC) $(CFLAGS) $(INCLUDES) -o $(TARGET) $(SRC) $(LDLIBS)

.PHONY: clean
clean:
	rm -f $(TARGET)