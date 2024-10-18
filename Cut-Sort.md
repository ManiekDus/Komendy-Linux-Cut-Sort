## p
cos
cos


# Komenda Cut
>Print selected parts of lines from each FILE to standard output.
>With no FILE, or when FILE is -, read standard input.
>Mandatory arguments to long options are mandatory for short
 options too.

Tak właśnie komenda **cut** opisana jest przez zawartą w systemie Linux instrukcje. Służy ona więc do wycinana części tekstu zwartej w danym pliku. Co stanie się jednak jeśli takiego pliku nie dodamy? Zostanie użyte wtedy standardowe wejście, zostaniemy wtedy poproszeni o wpisanie tekstu, a dana komenda **cut** zostaje na nim wykonana. Dla przykładu weźmy tekst:
```
Tak właśnie komenda "cut" opisana jest przez zawartą w systemie Linux instrukcje.
```
Następnie zastosujmy na niej komendę **cut**.
```
cut -c 1-3
```
Po wklejeniu tekstu terminał wyczyta nam wtedy pierwsze 3 znaki tekstu.
![Zdjęcie](https://github.com/ManiekDus/Komendy-Linux-Cut-Sort/blob/main/file.png)
