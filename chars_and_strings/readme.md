
# char and strings in cpp
### ctype.h
#### handy in char manipulations
```cpp
#include<ctype.h>
// or cctype
int main()
{
    cout<<islower('a');//1
    cout<<isspace('a');//0
    cout<<isalpha('*');//0
    cout<<isalnum('1');//1
    cout<<isdigit('1');//1

    char c=tolower('A');
    cout<<c;//a

    

}
```

### C-type strings

- contiguous in memory
- implemented as array of chars
- terminated by a null char- ( char with value 0)
- referred to as zero or null terminated strings

### string literal
- seq of chars in double quotes- "arun"
- constant
- terminate with a null char
- c++ inserts null char
- my na is - storted as
| `m` | `n` | ` ` | `n` | `a` | ` ` | `i` | `s` | `0` |




