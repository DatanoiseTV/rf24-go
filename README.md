# rf24-go
A wrapper for RF24 for Golang.

# Prerequisites
* https://github.com/nRF24/RF24

## Installation

As the go build doesn't prebuild the C wrapper, first you will need to compile the wrapper.

```
git clone https://github.com/DatanoiseTV/rf24go
cd rf24go/rf24c
mkdir build
cd build
cmake ..
make && sudo make install
``

# Example

You can find a working example at https://github.com/DatanoiseTV/rf24-go-example
