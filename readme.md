# INSTALL

copy this
```sh
git clone https://github.com/lexBenji/pydex
cd pydex
```
and paste it to your terminal

# SYNTAX

```pydx
main() begin
print "hello world\n" endl;
end
```
to print **hello world**.<br>
semi-colon is required at the end of each line.<br>
use the `.pydx` extension to compile to C language.

# IMPORT

```pydx
import "test.h"

main() begin
test();
end
```

use C header file for importing.<br>
use the `.pydh` extension to compile to C header.

# COMPILE

```sh
./pydex FILE.pydx
```
to compile to a C file
```sh
./pydex FILE.pydh
```
to compiler to C header file.

# TYPES

the types `char`,`int` and `float` are supported, `bool` isn't supported.

# ISSUES

if you have a bug or a new thing you want me to code into the language, you can go to the [issue page](https://github.com/lexBenji/pydex/issues)
