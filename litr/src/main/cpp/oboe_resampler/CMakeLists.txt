cmake_minimum_required(VERSION 3.22.1)

project("OboeResampler")

add_library(oboe-resampler STATIC
        IntegerRatio.cpp
        LinearResampler.cpp
        MultiChannelResampler.cpp
        PolyphaseResampler.cpp
        PolyphaseResamplerMono.cpp
        PolyphaseResamplerStereo.cpp
        SincResampler.cpp
        SincResamplerStereo.cpp
)