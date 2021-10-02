---
layout: post
title:  "First post!"
date:   2021-10-01 23:30:00 +0900
categories: Update
---

블로그의 첫 포스트 그냥 글을 쭉 쓰면 이렇게 나오는구나.  
Blog First Post  
가나다        라마바  
가나다&nbsp;라마바  
가나다&nbsp;&nbsp;&nbsp;&nbsp;라마바  
'dfsdfsdfasdfasdf'  
이 포스트의 타이틀 : {{ page.title }} 이다.  
{{ page.date }}  
{{ site.title }}  
{{ site.url }}

# <글머리>

# This is \#
## This is \##
### This is \###
#### This is \####
##### This is \#####
###### This is \######
####### This is \#######
<h1>This is h1</h1>
<h2>This is h2</h2>
<h3>This is h3</h3>
<h4>This is h4</h4>
<h5>This is h5</h5>
<h6>This is h6</h6>
<h7>This is h7</h7>

# <강조효과>
*single asterisks*  
**double asterisks**  
_single underscores_  
__double underscores__  

# <인용>
> 인용문1
>> 인용문2
>>> 인용문3
>>>> 인용문4
>>>>> 인용문5
>>>>>> 인용문6
>>>>>>> 인용문7

# <정렬>
1. 1번
2. 2번
3. 3번
4. 4번
5. 5번

* C
    * C++
        - C#
* JAVA
* Objective-C
    - Swift

# <수평선>
* * *
***
*****
- - -
-------------------------

# <링크>
[NAVER](https://www.naver.com) -> \[NAVER](https://www.naver.com)  
[Google](https://www.google.com) -> \[Google](https://www.google.com)  
<https://www.google.com> -> \<https://www.google.com> : 주소 직접 표시


# <코드 인용>

```
func test(a: Int, b: Int) -> Bool {
    return a > b
}
```

```swift
// swift
func test(a: Int, b: Int) -> Bool {
    return a > b
}
```

```java
// java
public class MyClass {
    int num;

    public int getNum() {
        return num;
    }
}
```

```ruby
# ruby
print("!")
```

```c
// c
#include <stdio.h>

int main(void) {
    printf("Hi!");
}
```

```cpp
// cpp
int main() {
    int y = SOME_MACRO_REFERENCE;
    int x = 5 + 6;
    cout << "Hello World! " << x << std::endl();
}
```