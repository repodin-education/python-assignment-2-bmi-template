# Painoindeksilaskuri · BMI-kalkylator · BMI Calculator

Python-ohjelmointi 1 · tehtävä 2 · uppgift 2 · assignment 2

## Suomeksi: Painoindeksilaskuri

### Tehtävä

Kirjoita ohjelma, joka lukee painon (kg) ja pituuden (m), laskee painoindeksin kaavalla `BMI = paino / (pituus * pituus)` ja tulostaa sen yhden desimaalin tarkkuudella. Tulosta sen jälkeen painoluokka: alle 18.5 `Underweight`, alle 25.0 `Normal weight`, alle 30.0 `Overweight`, muuten `Obese`.

### Syöte

Kaksi riviä: paino ja pituus desimaalilukuina.

### Tuloste

Kaksi riviä: `BMI: <arvo>` ja painoluokka.

### Esimerkit

Syöte 1:

```text
70
1.75
```

Tuloste 1:

```text
BMI: 22.9
Normal weight
```

Syöte 2:

```text
50
1.80
```

Tuloste 2:

```text
BMI: 15.4
Underweight
```

Syöte 3:

```text
95
1.80
```

Tuloste 3:

```text
BMI: 29.3
Overweight
```

### Työskentely

Kirjoita ratkaisu tiedostoon `main.py`. Testaa ohjelma esimerkkisyötteillä komennolla `python3 main.py`, commitoi kun jokin osa toimii ja pushaa viimeisin versio GitHubiin ennen palautusaikaa.

## På svenska: BMI-kalkylator

### Uppgift

Skriv ett program som läser vikt (kg) och längd (m), beräknar BMI med formeln `BMI = vikt / (längd * längd)` och skriver ut det med en decimal. Skriv sedan ut viktklassen: under 18.5 `Underweight`, under 25.0 `Normal weight`, under 30.0 `Overweight`, annars `Obese`.

### Indata

Två rader: vikt och längd som decimaltal.

### Utskrift

Två rader: `BMI: <värde>` och viktklassen.

### Exempel

Indata 1:

```text
70
1.75
```

Utskrift 1:

```text
BMI: 22.9
Normal weight
```

Indata 2:

```text
50
1.80
```

Utskrift 2:

```text
BMI: 15.4
Underweight
```

Indata 3:

```text
95
1.80
```

Utskrift 3:

```text
BMI: 29.3
Overweight
```

### Arbetssätt

Skriv lösningen i filen `main.py`. Testa programmet med exempelindata med kommandot `python3 main.py`, gör en commit när en del fungerar och pusha den senaste versionen till GitHub före inlämningstiden.

## In English: BMI Calculator

### Task

Write a program that reads weight (kg) and height (m), calculates BMI with `BMI = weight / (height * height)` and prints it to one decimal place. Then print the category: below 18.5 `Underweight`, below 25.0 `Normal weight`, below 30.0 `Overweight`, otherwise `Obese`.

### Input

Two lines: weight and height as decimal numbers.

### Output

Two lines: `BMI: <value>` and the category.

### Examples

Input 1:

```text
70
1.75
```

Output 1:

```text
BMI: 22.9
Normal weight
```

Input 2:

```text
50
1.80
```

Output 2:

```text
BMI: 15.4
Underweight
```

Input 3:

```text
95
1.80
```

Output 3:

```text
BMI: 29.3
Overweight
```

### How to work

Write your solution in `main.py`. Test the program with the example inputs using `python3 main.py`, commit whenever a part works, and push the latest version to GitHub before the due date.
