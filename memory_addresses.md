
These memory addresses are related to the NTSC version of the Spyro 2 game using the BizHawk emulator and can probably not be directly ported to other emulators.

If not specified differently all addresses are 'Little Endian' and in the 'MainRAM' Memory Domain.

If an address is used as a boolean value (true/false) it generally uses the concept that the value 0 (zero) means false and all other (non-zero) values mean true.
https://en.wikipedia.org/wiki/Boolean_data_type#C,_C++,_Objective-C,_AWK

| Address: |  Note:  | Size:  |  Type:   | Info: |
| -------- | ------- | ------ | -------- | ----- |
| `069FF0` | Spyro X | 4 Byte |          |       |
| `069FF4` | Spyro Y | 4 Byte |          |       |
| `069FF8` | Spyro Z | 4 Byte | Probably 'Signed', but not confirmed |       |
| `060288` | Winter Tundra death barrier Z | 4 Byte | Signed | Default value of 19500 |
| `060258` | Autumn Plains death barrier Z | 4 Byte | Signed | Default value of 21000 |
