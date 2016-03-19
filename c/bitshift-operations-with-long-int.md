# Bitshift operations with long int

When doing shift operations with long int (or any other type that is not an int) be sure that constants operands like `1` are converted to the right type: `1UL` for example for unsigned long int.