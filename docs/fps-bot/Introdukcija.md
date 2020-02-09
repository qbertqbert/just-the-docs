---
layout: default
title: Introdukcija
parent: Fps bot
nav_order: 1
published: true
---

## Introdukcija

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.

---

## Testing

### Testing[testing]

```c
/*
	Revision history:
    	Revised by Qbert 2020
*/

#include <iostream>	// highlight[test]
#include <vector>   // highlight[test]

//      constructs the Token out of following members respectively
struct Token {
        char kind;
        double value;
        string name;

        Token(char ch) : kind(ch), value(0.0) {}
        Token(char ch, double val) : kind(ch), value(val) {}
        Token(char ch, string val) : kind(ch), name(val) {}  
};
```
