cmake_minimum_required(VERSION 3.15)
project(VideoFormatParser)
include_directories(${CMAKE_CURRENT_SOURCE_DIR})


set(CMAKE_CXX_STANDARD 11)

add_executable(video_stream_parser

        NalParse.cpp

        h264_sei.cpp
        h264_avcc.cpp
        h264_sei.cpp
        h264_stream.cpp
        h264_analyze.cpp

        h265_avcc.cpp
        h265_sei.cpp
        h265_stream.cpp
        )
