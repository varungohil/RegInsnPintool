# MyPintools
This repo is the collection of pintools I made for various research projects. 

## How to build?
- Download [Intel Pin](https://software.intel.com/en-us/articles/pin-a-dynamic-binary-instrumentation-tool).
```bash
# Download the MyPintools repo
git clone https://github.com/varungohil/MyPintools.git

# Copy the pintools folder inside Pin's tools folder
# $PIN_HOME is set to the root directot of Intel Pin
cp -r MyPintools/pintools/ $(PIN_HOME)/source/tools/

#Build the pintools
cd $(PIN_HOME)/source/tools/pintools
make
```


