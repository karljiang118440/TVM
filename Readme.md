
# 1、



wget http://releases.llvm.org/x.x.x/clang+llvm-x.x.x-x86_64-linux-gnu-ubuntu-xx.xx.tar.xz

tar -xf clang+llvm-x.x.x-x86_64-linux-gnu-ubuntu-xx.xx.tar.xz


export TVM_HOME=/media/jcq/Work/TVM
export PYTHONPATH=$TVM_HOME/python:$TVM_HOME/topi/python:$TVM_HOME/nnvm/python:${PYTHONPATH}








cmake -S llvm -B build -G <generator> [options]# TVM
