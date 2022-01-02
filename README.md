
to build :
./configure --with-java-runtime-library=openjdk8 --disable-zip
make
make install

to run :
/usr/local/jamvm/bin/jamvm xxx

to build & run example :
cd examples
javac -source 1.8 -target 1.8 HelloWorld.java
/usr/local/jamvm/bin/jamvm HelloWorld
