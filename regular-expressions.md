# Regular Expressions
---------

#### Symbols
***
```jsregexp
$ = end of the sting
\ = escape special symbol
. = any character
+ = one or more character of the previous match
[] = match any character in the set
[^] = not the character in the set
\s = space character
() = matching group
? = optional
| = or
(?:) = no captcharing group
* = 0 or more
(?=) = look ahead



```

#### Flags
****

```regexp
g = global search
i = insensitive

```

### Expressions
***

1. ``My name is $NAME$`` 
    ```regexp
    1. My name is $NAME$ = my name is \$name\$$
 
    2. Visit https://google.com to search
       Visit http://google.com to search
       Visit ftp://google.com to search
    
       /((?:ht|f)tps?:\/\/([^\s]+))/i
    
    3. idot
       idotic
       /idot(ic)?/i
    
    4. Born
       Corn
       Morn
       Horn
    
       /[BCMH]orn/gi
    
    5. My name is @Prince.
       /@(\w+)/gi
    
    6. <a href="google.com">google</a>
       /google(?=<)/gi (find before < sign)
 
    ```
    