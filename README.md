# cpp-cheatsheet
Cheatsheet de C++

## agregar acentos en c++
Para ello hayque agregar wchar.h y locale.h mas, dentro de la función el setlocale como abajo:

```cpp

#include <wchar.h>
#include <locale.h>


int main(void){

    setlocale(LC_ALL, "");

    printf("ó á");

    return EXIT_SUCCESS;
}
```
