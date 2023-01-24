0x11. C - printf (Team project, Kingsley Chinedu and Ejemai Moses), 

Description

The C library function int printf(const char *format, ...) sends formatted output to stdout.
Declaration

Following is the declaration for printf() function.

int printf(const char *format, ...)

Parameters

    format − This is the string that contains the text to be written to stdout. It can optionally contain embedded format tags that are replaced by the values specified in subsequent additional arguments and formatted as requested. Format tags prototype is %[flags][width][.precision][length]specifier, which is explained below −

Sr.No. 	Specifier & Output
1 	

c

Character
2 	

d or i

Signed decimal integer
3 	

e

Scientific notation (mantissa/exponent) using e character
4 	

E

Scientific notation (mantissa/exponent) using E character
5 	

f

Decimal floating point
6 	

g

Uses the shorter of %e or %f
7 	

G

Uses the shorter of %E or %f
8 	

o

Signed octal
9 	

s

String of characters
10 	

u

Unsigned decimal integer
11 	

x

Unsigned hexadecimal integer
12 	

X

Unsigned hexadecimal integer (capital letters)
13 	

p

Pointer address
14 	

n

Nothing printed
15 	

%

Character
