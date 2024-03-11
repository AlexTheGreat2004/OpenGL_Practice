APP_NAME = myApp
BUILD_DIR = ./bin
CPP_FILES = ./src/*.cpp

APP_DEFINES:=
APP_INCLUDES:= -I./src/vendors/GLFW -framework Cocoa -framework OpenGL -framework IOKit
APP_LINKERS:= -L./src/vendors/GLFW/Lib -lglfw3

build:
	clang++ -g -Wall $(CPP_FILES) -o $(BUILD_DIR)/$(APP_NAME) $(APP_INCLUDES) $(APP_LINKERS)
