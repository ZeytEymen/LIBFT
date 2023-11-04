# LIBFT
Make your own C Library - Kendi Kütüphanenizi Yazın

ENGLISH

For use that library;

* insert the library in your code (#include "libft.h")
* $> make
* $> gcc myprogram.c -L. -lft -o myprogram(if your .c file is the same directory with libft.a file)

TURKISH

Kütüphaneyi kullanmak için;

* #include "libft.h" şeklinde kütüphaneyi .c dosyanıza ekleyin
* $> make   "make komutu ile kütüphaneyi oluşturun"
* $> gcc myprogram.c -L. -lft -o myprogram (eğer dosyanız libft.a ile aynı dizinde ise)

## **LIBFT SÖZLÜĞÜ**

### _**isalpha**_

*   Prototip : `int ft_isalpha(int c);`
*   Gönderilen değer, eğer _**Alfabetik**_ bir karakter ise **1** eğer değilse **0** döndürür.

### _**isdigit**_

*   Prototip : `int ft_isdigit(int c);`
*   Gönderilen değer, eğer bir _**Rakam**_  ise **1** eğer değilse **0** döndürür.

### _**isalnum**_

*   Prototip : `int ft_isalnum(int c);`
*   Gönderilen değer, eğer bir _**Alfa Numerik(Rakam veya Alfabetik)**_ karakter  ise **1** eğer değilse **0** döndürür.

### _**isascii**_

*   Prototip : `int ft_isascii(int c);`
*   Gönderilen değer, eğer _**ASCII**_ karakter  ise **1** eğer değilse **0** döndürür.
*   Örneğin fonksiyona “ç | ü | ğ” gibi ASCII tablosuna ait olmayan karakterler için 0 döner.

### _**isprint**_

*   Prototip : `int ft_isprint(int c);`
*   Gönderilen değer, eğer _**Printable(Yazdırılabilir)**_ karakter  ise **1** eğer değilse **0** döndürür.
*   Örneğin  ‘\\0’ gibi yazdırılamayan karakterler için 0 döner.

### _**toupper**_

*   Prototip : `int ft_toupper(int c);`
*   Gönderilen değer _**küçük harf ise büyük harfe**_ çevirir.

### _**tolower**_

*   Prototip : `int ft_tolower(int c);`
*   Gönderilen değer _**büyük harf ise küçük harfe**_ çevirir.

### _**strlen**_

*   Prototip : `size_t ft_strlen(const char *s);`
*   Gönderilen _**string dizisinin uzunluğunu size\_t tipinde**_ döndürür.

## DEVAM EDECEK…
