**Sprawdzian z podstaw PHP i MySQL**

**Imię i nazwisko:____________________________ Data:___________**

---

### **Zadanie 1: Tworzenie bazy danych (20 punktów)**

Utwórz bazę danych MySQL o nazwie **`biblioteka`**. W tej bazie utwórz tabelę **`ksiazki`** z następującymi polami:

- **`id`** – typ `INT`, klucz główny, auto_increment
- **`tytul`** – typ `VARCHAR(100)`
- **`autor`** – typ `VARCHAR(100)`
- **`rok_wydania`** – typ `INT`

---

### **Zadanie 2: Dodawanie rekordów (20 punktów)**

Dodaj do tabeli **`ksiazki`** trzy rekordy z przykładowymi danymi książek.

---

### **Zadanie 3: Połączenie z bazą i wyświetlenie danych (30 punktów)**

Napisz skrypt PHP, który:

a) Połączy się z bazą danych **`biblioteka`**.

b) Pobierze wszystkie rekordy z tabeli **`ksiazki`**.

c) Wyświetli dane książek w postaci punktowanej listy (tytuł i autor).

d) Wyświetli te same dane w tabeli HTML, pokazując wszystkie pola: **`id`**, **`tytul`**, **`autor`**, **`rok_wydania`**.

---

### **Zadanie 4: Formularz dodawania danych (30 punktów)**

Utwórz formularz HTML zawierający pola:

- **Tytuł**
- **Autor**
- **Rok wydania**

Napisz skrypt PHP, który:

a) Odbierze dane z formularza.

b) Zapisze nowy rekord do tabeli **`ksiazki`** w bazie danych **`biblioteka`**.

---

**Punktacja łączna: 100 punktów**

Powodzenia!
