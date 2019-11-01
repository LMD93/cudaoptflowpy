set(the_description "access opencv cuda methods from Python")

ocv_define_module(cudaoptflowpy opencv_core opencv_imgproc opencv_tracking opencv_cudaoptflow opencv_cudaarithm opencv_cudaimgproc WRAP python)
