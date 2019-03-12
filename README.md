# software-inatallation-note

ImportError: libcuda.so.1: cannot open shared object file: No such file or directory

cd /usr/lib/x86_64-linux-gnu/
sudo ln -f -s libcuda.so.<yournvidia.version>(in /usr/local/cuda-8.0/lib64) libcuda.so.1(in /usr/lib/x86_64-linux-gnu/)

