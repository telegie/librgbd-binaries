# librgbd-binaries

## For Windows

mkdir build
cd build
..\scripts\configure-windows.sh
Run INSTALL of librgbd.sln

avcodec-58.dll, avutil-56.dll, libwinpthread-1.dll are copied from other places.

## For Mac

mkdir build
cd build
../scripts/configure-mac.sh {path_to_librgbd}
make -j8
make install

## For Linux

apt install cmake
apt install build-essential
apt install zlib1g-dev

mkdir build
cd build
../scripts/configure-linux.sh
make -j8
make install
