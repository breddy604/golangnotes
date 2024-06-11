# golangnotes

export GOWORK=off - to run go lang in non workspace mode

You can specify numbers as 1_2_3_4 for better readability.

You can also specify prefixed numbers in their base format like 0b111 = 7 or 0xF = 15. This is nice.
Single quotes cannot be interchanged with double quotes. Single quote is for character literals
Use backquote(`) for string literals with special characters , multiline etc

byte = uint8

int - behaves differently on differen CPU archs
use explicit types like unit32 or unit64 etc.

+=, -=, *=, /=, and %= --- are all supported.

bitwise operators &,|, ^ , shif operators << and >> supported

dont compare floats. Just check for mean difference.

rune = int32
byte = uint8

x = float4(100) --- type conversion explicitly

other languages, non zero is treated as True - boolean, but, in GoLang, explicit bool True alone is accepted.
Go's motto is simplicity and clarity.

Literals are untyped.

var x float64 = 100 -- valid

x := 10
x, y := 30, "hello" --- Valid, atleast one new variable on left side

maps cannot be compared for equality and maps, slices cannot be used as keys for maps.

GO does not allow you to write you own equal and hashing algorithms
