
# 📘 HTML Wikipedie pro Začátečníky

Ucelený přehled základních HTML prvků, jejich význam a použití.

---

## 📄 Základní Struktura HTML

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Název stránky</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <!-- Obsah stránky -->
  </body>
</html>
```

---

## 🧱 Struktura a Text

| Tag              | Popis                                         |
|------------------|-----------------------------------------------|
| `<html>`         | Kořenový element celé HTML stránky            |
| `<head>`         | Metadata stránky (např. název, odkazy, CSS)   |
| `<meta>`         | Metadata – např. kódování (UTF-8)             |
| `<title>`        | Titulek stránky (v záložce prohlížeče)        |
| `<body>`         | Viditelný obsah stránky                       |
| `<h1>`–`<h6>`     | Nadpisy úrovní 1–6                            |
| `<p>`            | Odstavec                                      |
| `<br>`           | Zalomení řádku (line break)                   |
| `<hr>`           | Vodorovná čára (oddělovač)                    |
| `<strong>`       | Silný důraz (tučně)                           |
| `<em>`           | Zdůraznění (kurzíva)                          |
| `<s>`            | Přeškrtnutý text                              |
| `<u>`            | Podtržený text                                |
| `<span>`         | Inline kontejner pro stylování části textu    |
| `<div>`          | Blokový kontejner                             |
| `<!-- ... -->`   | Komentář  
| `<div class="cistic"></div>: `| ukončení optekani v css ".cistic {
                                                         clear: both;
                                                         }"
|
                                   |

---

## 🔗 Odkazy a Navigace

| Tag         | Popis                                                                   |
|-------------|-------------------------------------------------------------------------|
| `<a>`       | Odkaz (atribut `href="..."`)                                            |
| `target="_blank"` | Otevře odkaz v novém okně                                         |
| `<nav>`     | Navigační menu (HTML5)                                                  |

---

## 🖼️ Obrázky

| Tag          | Popis                                          |
|--------------|------------------------------------------------|
| `<img>`      | Vložení obrázku                                |
| `src`        | Cesta k obrázku (např. `src="img.jpg"`)        |
| `alt`        | Alternativní text                              |
| `width` / `height` | Šířka a výška obrázku v pixelech         |

```html
<img src="obrazek.jpg" alt="Popis obrázku" width="150" height="200">
```

---

## 📋 Seznamy

| Tag             | Popis                                   |
|------------------|-----------------------------------------|
| `<ul>`          | Nečíslovaný seznam (s odrážkami)         |
| `<ol>`          | Číslovaný seznam (1, 2, 3…)              |
| `<li>`          | Položka seznamu                          |
| `<dl>`          | Definiční seznam (slovníček)             |
| `<dt>`          | Termín (název položky)                   |
| `<dd>`          | Definice položky                         |

```html
<ol reversed start="4" type="I">
  <li>Čtvrtý</li>
  <li>Třetí</li>
</ol>
```

---

## 📊 Tabulky

| Tag           | Popis                                               |
|---------------|-----------------------------------------------------|
| `<table>`     | Vytváří tabulku                                     |
| `<thead>`     | Hlavička tabulky                                    |
| `<tbody>`     | Tělo tabulky                                        |
| `<tfoot>`     | Patička tabulky                                     |
| `<tr>`        | Řádek tabulky                                       |
| `<td>`        | Buňka v řádku                                       |
| `<th>`        | Nadpisová buňka (tučně, zarovnaná na střed)         |
| `colspan`     | Sloučení více sloupců v jedné buňce                 |
| `rowspan`     | Sloučení více řádků v jedné buňce                   |

### 🧪 Ukázka:

```html
<table border="1">
  <thead>
    <tr>
      <th>Náhled</th>
      <th>Typ</th>
      <th>Procesor</th>
      <th>Graf. karta</th>
      <th>Skladem</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img src="notebook.png" width="100"></td>
      <td>AB8AC9</td>
      <td>Intel Atom</td>
      <td>Nvidia</td>
      <td rowspan="2">Ano</td>
    </tr>
    <tr>
      <td colspan="2">Neznámo</td>
      <td colspan="2">Neuvedeno</td>
    </tr>
  </tbody>
</table>
```

---

## 🧭 Iframe, Skripty a Styly

| Tag          | Popis                                             |
|---------------|---------------------------------------------------|
| `<iframe>`   | Vkládání cizího obsahu (např. YouTube)             |
| `<style>`    | Vložené CSS (méně vhodné, doporučeno externě)      |
| `<script>`   | JavaScript kód                                     |

---

## ✅ Uživatelské formuláře *(základ)*

| Tag         | Popis                                     |
|-------------|-------------------------------------------|
| `<form>`    | Formulář                                  |
| `<input>`   | Vstupní pole (text, checkbox, atd.)       |
| `<label>`   | Popisek vstupu                            |
| `<textarea>`| Víceřádkový vstup                         |
| `<button>`  | Tlačítko                                  |
| `<select>`  | Rozbalovací nabídka                       |
| `<option>`  | Jedna položka v `<select>`                |

---

## 🧠 Tipy

- ✅ **Používej semantické HTML** – např. `<header>`, `<footer>`, `<main>`, `<section>`, `<article>`, `<aside>`.
- 📐 **Značkuj kód správně** – atributy piš do uvozovek: `href="..."`.
- 🌐 **Používej UTF-8** v `<meta charset="UTF-8">`.
- 🎯 **Validační nástroje**: [validator.w3.org](https://validator.w3.org/)

---

## 📌 Licence

Tento materiál můžeš volně používat i upravovat pro vlastní projekty.

---
