# librgbd-binaries

## For Mac

mkdir build
cd build
../scripts/configure-mac.sh
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
