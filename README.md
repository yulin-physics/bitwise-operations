# Bit Operations in Go

This bit operations library mimicks the functions of Go strings library.

For learning purposes only, use at your own risk.

## Contains

`func ContainsOne(b uint)`

`func ContainsZero(b uint)`

Checks if the argument has at least one bit that is one (or zero)

palindrome symmetry checker

## Last Index

`func LastIndexOfOne(b uint)`

`func LastIndexOfOne(b uint)`

Finds the index of the last bit one (or zero) of the argument counting from left to right

## Split

`func SplitAt(b uint, index int)`

Splits the binary in two at the index, returns the 2 sub-binaries

## Join

## Trim

`func TruncateFromRight(b uint, index int) `

`func TruncateFromLeft(b uint, index int)`

Truncate functions trim off bits from left (or right), up to but not including the index

`func ClearFromRight(b uint, index int) `

Clear preserves the binary length and resets the bits from right to zero, up to but not including the index

`func RemoveBit(b uint, index int)`

RemoveBit removes the bit at the index from the binary.

`func Join(bs []uint, sep uint)`
Join combines the binary values into one, separated by the given delimiter

`func ColumnJoin(rows []uint, colLen int)`
ColumnJoin combines the binary values in each corresponding bit position, forming array of columns
colLen is usually the bit length of an element in rows, but since leading zeroes are ommited, user needs to specify the bit length.

## Repeat

## Replace
