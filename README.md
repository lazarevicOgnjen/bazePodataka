# Lab 1 - <mark> prosti upiti <mark>

<details> 
<summary> zadaci za samostalni rad </summary> 

```sql 
-- 1. zadatak
SELECT IME, PREZIME, GODINA_ROD, MESTO_ROD
FROM GLUMAC
WHERE BROJ = 50;
```

```sql
-- 2. zadatak
SELECT IME, PREZIME
FROM GLUMAC
WHERE GODINA_ROD > 1920;
```

```sql
-- 3. zadatak
SELECT GLUMAC
FROM IGRA
WHERE FILM BETWEEN 85 AND 91;
```

```sql
-- 4. zadatak
SELECT BROJ, NASLOV
FROM FILM
WHERE TIP = 'comedy' AND (AA_NAGRADE IS NOT NULL AND AA_NAGRADE > 0);
```

```sql
-- 5. zadatak
SELECT COUNT(*)
FROM IZNAJMLJIVANJE
WHERE CLAN = 3;
```

```sql
-- 6. zadatak
SELECT BROJ, NASLOV
FROM FILM
WHERE TIP = 'comedy' AND (AA_NAGRADE IS NOT NULL AND AA_NAGRADE > 0) AND LOWER(NASLOV) NOT LIKE '%uncle%' AND GODINA > 1970;
```

</details>

<br>
<hr>
<br>

# Lab 2 - <mark> slozeni upiti </mark>

<details>

<summary> zadaci za samostalni rad </summary>

```sql
-- 1. zadatak
```

</details>