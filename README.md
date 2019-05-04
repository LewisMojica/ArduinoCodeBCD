# ArduinoCodeBCD

| Function name  | Description |
| ------------- | ------------- |
|`CodeBCD(byte A, byte B, byte C, byte D)`| _Constructor_. `A`, `B`, `C` and `D` are the pins where the bcd code will be written|
| `void write(byte dec)` | write the value of `dec` in the given pins|
| `void writeNeg(byte dec)` | write the value of `dec` in the given pins, but **with negative logic**|
