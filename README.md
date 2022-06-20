## 1.3 types

`[` and `]` means inclusive, `(` and `)` means exclusive;
1. primitive type
    1. numeric type
        1. integral type
            - byte (8 bits signed two's-complement, `[-128, 127] / [-2^7, 2^7 - 1]`, default value `0`); 
            - short (16 bits signed two's-complement, `[-32768, 32767] / [-2^15, 2^15 - 1]`, default value `0`); 
            - int (32 bits signed two's-complement, `[-2147483648, 2147483647] / [-2^31, 2^31 - 1]`, default value `0`); 
            - long (64 bits signed two's-complement, `[-9223372036854775808, 9223372036854775807] / [-2^63, 2^63 - 1]`, default value `0`); 
            - char (16 bits unsigned represents unicode BMP's code points, utf-16 encoding, `[0, 65535]`, default value `\u0000`/`null`);
        1. floating point type
            - float (32bits, IEEE 754 standard, default value `+0`);
            - double (64bits, IEEE 754 standard, default value `+0`);
    1. boolean type
1. reference type
1. null type: no name, can not direct declare; we can simply treat null as a special literal;
    1. strictly speak, null is not reference type;
