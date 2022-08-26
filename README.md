# librgbd-binaries

## For Mac

mkdir build
cd build
../scripts/configure-mac.sh
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
../scripts/configure-linux.sh
make -j8
make install
