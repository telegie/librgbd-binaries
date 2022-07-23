# librgbd-binaries

## For Mac

mkdir build
cd build
cmake ../librgbd -DCMAKE_INSTALL_PREFIX="../1.0.0/arm64-mac"
make -j8
make install

## For Linux

mkdir build
cd build
cmake ../librgbd -DCMAKE_INSTALL_PREFIX="../1.0.0/x64-linux"
make -j8
make install
