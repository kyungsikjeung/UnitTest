# Git 세팅

    1. Git hub Repository 생성
    2. git 파일 복사 후 터미널 생성
    3. mkdir unittest
    4. git add .
    5. git commit -m "unit test folder 생성"
    6. git push

# GIT README.MD 프리뷰

    1. 리드미 엠디 작성
    2. ctrl + shift+ V

# C MINGW 세팅(컴파일)

    1. MINGW 다운로드
    2. C\MINGW\Bin 패스에 설정
    3. 터미널에서 gcc --version  으로 패스 잘 설정되었는지 확인

# Visual Studio Code Extension

    1. Meterial Theme
    2. Meterial Thema Icon
    3. FIRA CODE FONT

# GCC 사용하기

    1. cd unittest & type nul > main.c
    2. type nul > calculate.c
    3. type nul > calculate.h

```code
// calculate.c
#include "calculate.h"

int add(int a, int b){
    return a + b;
}
```

````

```code
#ifndef CALCULATE_H
#define CALCULATE_H

int add(int a, int b);

#endif // CALCULATE_H
````

```code
#include <stdio.h>
#include "calculate.h"

int main(){
    printf("Hello World%d\n",add(1,2));
    return 0;
}
```

```code
// terminal GCC
>gcc -o calculate main.c calculate.c & calculate
```
