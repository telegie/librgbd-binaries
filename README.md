# librgbd-binaries

## For Mac

mkdir build
cd build
cmake ../librgbd -DCMAKE_INSTALL_PREFIX=../1.2.0/arm64-mac
make -j8
make install

## For Linux

apt install git
apt install cmake
apt install build-essential

git clone {repo}
cd librgb-binaries

mkdir build
cd build
cmake ../librgbd -DCMAKE_INSTALL_PREFIX=../1.2.0/x64-linux
make -j8
make install
