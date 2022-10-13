---
title: Hello World!
tags: 
- 水
categories:
- 杂项

theme: wave
password: mima
abstract: 这是一篇加密文章，你知道密码是什么吗？
message: 请输入密码，提示：远在天边，近在眼前
---

#### C

```
#include <stdio.h>

int main() 
{
    char str[50] = {0};
    scanf("%s", str);
    printf("Hello %s\n", str);
    return 0;
}
```

#### C++

```
#include <iostream>
#include <cstring>

using namespace std;
/*
using std::cin;
using std::cout;
using std::endl;
*/

int main() 
{
    string str;
    cin >> str;
    cout << "Hello " << str << endl;
    return 0;
}
```

#### Python

```
def main():
    str = input()
    print("hello " + str)
main()
```

#### Java

```
import java.util.Scanner;

public class HelloWorld {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String str = sc.next();
        System.out.println("Hello " + str);
        sc.close();
    }
}
```

#### html

```

```