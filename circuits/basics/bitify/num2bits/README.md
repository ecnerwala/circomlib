# `Num2Bits(n)`

## Description

This template converts a field element (i.e. is there a max of bits)? `in` to its binary representation `out[n]`.

## Schema

```
          _____________________     
         |                     |
in ----> |     Num2Bits(n)     | ----> out[n]
         |_____________________|     
```

## Dependencies

None.


## Expected Inputs

| Input           | Type           |
| -------------   | -------------  | 
| `in`            | Field element  |

## Outputs

| Output           | Type                     | Description     |
| -------------    | -------------            | ----------      | 
| `out[n]`         | Binary array of `n` bits | Binary representation of the field element `in` using the [LSB 0 bit numbering](https://en.wikipedia.org/wiki/Bit_numbering#LSB_0_bit_numbering) encoding. |

## Benchmarks 

## Test