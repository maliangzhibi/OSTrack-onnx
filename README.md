# Joint Feature Learning and Relation Modeling for Tracking: A One-Stream Framework. (onnx)

The official implementation by pytorch:

https://github.com/botaoye/OSTrack

# 0. Download model
[onnx_file](https://www.123pan.com/s/6iArVv-kUAJ.html)

# 1. How to build and run it?

## modify your own CMakeList.txt
modify onnx path as yours

## build
```
$ mkdir build && cd build
$ cmake .. && make -j 
```

## run
```
$ cd build
$ ./ostrack-onnx [videopath(file or camera)]
```

# Acknowledgments

Thanks for the [OSTrack-mnn](https://github.com/Z-Xiong/OSTrack-mnn) and [lite.ai.tookit](https://github.com/DefTruth/lite.ai.toolkit), which helps us to quickly implement our ideas.
