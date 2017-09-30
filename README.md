# Array Tools Base  :black_small_square:
|Current Working Status|
|----------------------|
| :white_check_mark:   |

These groups of functions are helpful in working with character arrays. In quick summary, these functions can help
in identifying valid input, getting size, ect.

(Note: The 'getSize' function does the same thing as the strlen() function from C, though 'getSize' is limmited to 256.
It will probably be removed in later versions).

This library is needed as a base for some of my other groups of functions.

###To Do  :heavy_check_mark:
- [ ] Remove getSize as it performs the same function as strlen()

|Function Name|Description|Return|Params|
|:-----------:|:---------:|:----:|:----:|
|isValidint()|Takes in a null terminated cstring and returns a 1(true) or 0(false) depending on if the string contains all numeric characters.|(int)|char pointer|
|isValidalpha()|Takes in a null terminated cstring and returns a 1(true) or 0(false) depending on if the string contains all Alphabetic characters.|(int)|char pointer|
|isValidalphaInt()|Takes in a null terminated cstring and returns a 1(true) or 0(false) depending on if the string is all Alpabetical or Numeric characters.|(int)|char pointer|
|getSize()|Takes in a null terminated cstring and returns an int of that string's size|(int)|char pointer|
|getSizeiConst|Takes in a null terminated constant cstring and returns an int of that string's size|(int)|char pointer|


