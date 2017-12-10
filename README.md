# Catena4450-PIR
Additional PIR sensor to Catena

## Setup

Follow the directions [here](https://github.com/mcci-catena/Catena4410-Sketches/tree/master/catena4450m101_sensor) and make sure all the sensors are working and in your TTN dashboard.

Modify the [Catena_TxBuffer.h](https://github.com/mcci-catena/Catena4410-Arduino-Library/blob/master/src/Catena_TxBuffer.h) file in your local library to the one included in this repo.

Add the `payload-format.js` contents to the payload format decoder in the Applications > application name > PayLoad Formats > decoder.
