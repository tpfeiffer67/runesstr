# What is runesstr?

**runesstr** (**runes str**ing) is a small library to manipulate strings at the rune level.

## Functions

- `Length` - returns the number of Unicode code points (runes) in a string.
- `PadRight` - pads a string on the right side with a fill pattern until it reaches the given width.
- `Left` - returns the leftmost n runes of a string.
- `Right` - returns the rightmost n runes of a string.
- `SplitOnNearestSpace` - splits a string into two parts at the nearest space character to the n-th position.
- `RuneAtPosition` - returns the Unicode code point (rune) at the specified position in a string, or the specified default value if the position is out of bounds.

## Usage

```golang
import (
    "github.com/tpfeiffer67/runesstr"
)
```

## Contributing

If you'd like to contribute to this repository, feel free to submit a pull request. Please include tests for any new functions or changes to existing functions.

## License

This repository is licensed under the MIT License. See the LICENSE file for more information.


## Author

- [@TPfeiffer67](https://www.github.com/TPfeiffer67)
