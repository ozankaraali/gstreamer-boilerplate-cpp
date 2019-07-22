# name of your binary
bin_PROGRAMS = gst-app

# list of source files
# the prefix is the name of the binary
gst_app_SOURCES = main.cpp play.cpp

# list of headers we're not going to install
noinst_HEADERS = gst-app.h play.h

# our CXXFLAGS and LDFLAGS used for compiling and linking
# make sure you prefix these with the name of your binary
gst_app_CXXFLAGS = $(GST_CXXFLAGS)
gst_app_LDFLAGS = $(GST_LIBS)
