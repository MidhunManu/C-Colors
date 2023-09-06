## This is a program which will allow programmers to get coloured output in their terminal.

## Install
# For GNU/Linux and MAC OS

```
git clone https://github.com/MidhunManu/C-Colors
cd C-Colors
```

```
sudo cp colors.h /usr/include/
```

# For Windows

```
git clone https://github.com/MidhunManu/C-Colors
cd C-Colors
copy colors.h C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\VC\Tools\MSVC\14.29.30133\include

```
done, you can now use this header file in any C program

## Example
```
#include <colors.h>
int main() {
  red();
  printf("Hello World\n");
  return 0;
}
```
