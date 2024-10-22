
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
```bash
cut -c 1-3
```
Po wklejeniu tekstu terminał wyczyta nam wtedy pierwsze 3 znaki tekstu.
![Zdjęcie](https://github.com/ManiekDus/Komendy-Linux-Cut-Sort/blob/main/file.png)

##


# Komenda Sort 

Komenda `sort` w systemie Linux służy do sortowania zawartości plików tekstowych lub danych wejściowych.

## Skłdania

```bash
sort [opcje] [plik]
```

#### Sortowanie pliku 

```bash
sort plik.txt
```
Istnieje również polecenie.

```bash
sort plik.txt > plik2.txt
```

Komenda ta umożliwia posortowanie pliku `plik.txt` i zapisanie wyniku w nowym pliku `plik2.txt`.

## Opcje polecenia
- `-r` Umożliwia sortowanie w odwrotnej kolejności.
    ```bash 
    sort -r plik.txt
    ```
- `-n` Umożliwia sortowanie według liczb.
    ```bash 
    sort -n plik.txt
    ```
- `-u` Sortuje usuwając duplikaty.
    ```bash 
    sort -r plik.txt
    ```
- `-o` Umożliwia sortowanie i zapisanie efektów odrazu w wykorzystywanym pliku.
    ```bash 
    sort plik.txt -o plik.txt
    ```
- `-t ','` Zamienia separatory (space) w podany znak w cudzysłowiu.
    ```bash 
    sort -t ',' plik.txt
    ```
