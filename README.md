<div align="center">

## Efficient\_Power\_Of\_2


</div>

### Description

A Highly Efficient C program to Find whether a given number is Power of 2 or not
 
### More Info
 
Input is Integer. (not command line args)

Assuming User will give Integer Input.

Using Bitwise operator makes it more faster and efficient.

Eg ... (8) & (8-1) is always 0 ...

No Return ...

No Side Effects ...


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Balram Reddy Kakani](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/balram-reddy-kakani.md)
**Level**          |Beginner
**User Rating**    |4.8 (72 globes from 15 users)
**Compatibility**  |C, C\+\+ \(general\), Microsoft Visual C\+\+, Borland C\+\+, UNIX C\+\+
**Category**       |[Math](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math__3-12.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/balram-reddy-kakani-efficient-power-of-2__3-7221/archive/master.zip)

### API Declarations

```
#include<stdio.h>
```


### Source Code

```
#include <stdio.h>
int main()
{
int n;
printf( "Enter a number : ");
scanf("%d",&n);
if ( n & (n-1)) printf("\nNo");
else printf("\nYes");
return 0;
}
```

