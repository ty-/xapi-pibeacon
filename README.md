# xapi-pibeacon
Exploring xAPI integration possibilities with Raspberry Pi and Beacon technology

Currently includes a proof-of-concept that sends a statement to the ADL LRS when a beacon is recognized by the reader.

Clone this repository to your Raspberry Pi and ensure all your dependencies are installed (`sudo apt-get install hcitool bc`).

To run:

`./ibeacon_scan | ./send-statement`

This will run until the UUID is found, it will send a statement to the LRS with curl, then exit.
