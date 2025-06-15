
# 🎨 Základy CSS – Přehled Syntaxe a Použití

## 🧾 Základní zápis CSS
```css
selector {
  vlastnost: hodnota;
}
```

### Příklad:
```css
p {
  color: blue;
  font-size: 16px;
}
```

---

## 📦 Typy selektorů
| Selektor        | Popis                              |
|------------------|------------------------------------|
| `*`              | Všechny prvky                      |
| `element`        | Konkrétní tag (např. `p`, `h1`)    |
| `.trida`         | Prvky s danou třídou               |
| `#id`            | Prvek s konkrétním ID              |
| `div p`          | Vnořený prvek `p` uvnitř `div`     |
| `div > p`        | Přímý potomek `p` v `div`          |
| `a:hover`        | Stav při přejetí myší              |

---

## 🖌️ Vlastnosti textu
| Vlastnost         | Příklad                   |
|-------------------|---------------------------|
| `color`           | `color: red;`             |
| `font-size`       | `font-size: 18px;`        |
| `font-family`     | `font-family: Arial;`     |
| `text-align`      | `text-align: center;`     |
| `font-weight`     | `font-weight: bold;`      |
| `text-decoration` | `text-decoration: none;`  |

---



## 📐 Rozměry a rámečky

### Základní vlastnosti
| Vlastnost       | Popis                                    |
|------------------|-----------------------------------------|
| `width`          | Šířka (např. `100px`, `50%`)            |
| `height`         | Výška                                   |
| `padding`        | Vnitřní odsazení                        |
| `margin`         | Vnější odsazení                         |VZOR:padding: 20px;
| `border`         | Okraj (např. `1px solid black`)         |      margin: 20px; 
| `box-sizing`     | Chování box modelu (`border-box`)       |

```padding-top: 20px;
padding-right: 20px;
padding-bottom: 20px;
padding-left: 20px;

margin-top: 20px;
margin-right: 20px;
margin-bottom: 20px;
margin-left: 20px;```

padding: 20px 20px 20px 20px;
margin: 20px 20px 20px 20px;

padding: 20px 20px;
margin: 20px 20px;

### Pokročilé vlastnosti

| Vlastnost                                | Popis                                                                 |
|-----------------------------------------|-----------------------------------------------------------------------|
| `box-shadow: 2px 2px 7px #1c2228;`      | Vytvoří stín kolem prvku (např. `h1`)                                |
| `<div class="cistic"></div>`            | Ukončení obtékání — v CSS: <br> `.cistic { clear: both; }`           |
| `border-width: 3px;`                    | Nastaví šířku rámečku na 3px                                          |
| `border-style: solid;`                  | Styl čáry: plná                                                       |
| `border-color: green;`                  | Barva rámečku: zelená                                                 |
| `border-top: 3px solid green;`          | Horní okraj: 3px, plná čára, zelená                                  |
| `border-right: 3px solid green;`        | Pravý okraj: 3px, plná čára, zelená                                   |
| `border-bottom: 3px solid green;`       | Spodní okraj: 3px, plná čára, zelená                                  |
| `border-left: 3px solid green;`         | Levý okraj: 3px, plná čára, zelená                                    |

---

### Styl rámečků (`border-style`)
- `none` – Bez rámečku  
- `hidden` – Rámeček se nevykreslí, ale zabírá místo  
- `dotted` – Tečkovaný  
- `dashed` – Čárkovaný  
- `solid` – Plná čára  
- `double` – Dvojitý  
- `groove` – 3D efekt „vyryté“ čáry  
- `ridge` – 3D efekt „vystouplé“ čáry  
- `inset` – 3D efekt vnoření  
- `outset` – 3D efekt vystoupení  
- `inherit` – Zdědí styl z nadřazeného prvku  


---

### Styl rámečků (`border-style`)
- `none` – Bez rámečku  
- `hidden` – Rámeček se nevykreslí, ale zabírá místo  
- `dotted` – Tečkovaný  
- `dashed` – Čárkovaný  
- `solid` – Plná čára  
- `double` – Dvojitý  
- `groove` – 3D efekt „vyryté“ čáry  
- `ridge` – 3D efekt „vystouplé“ čáry  
- `inset` – 3D efekt vnoření  
- `outset` – 3D efekt vystoupení  
- `inherit` – Zdědí styl z nadřazeného prvku  






## 🎨 Barvy a pozadí
| Vlastnost       | Příklad                        |
|-----------------|--------------------------------|
| `color`         | Barva textu                    |
| `background`    | Krátký zápis pro pozadí        |
| `background-color` | `background-color: yellow;` |
| `background-image` | `url("obrazek.jpg")`        |

---

## 🎛️ Zobrazení a zarovnání
| Vlastnost    | Příklad                          |
|--------------|----------------------------------|
| `display`    | `block`, `inline`, `flex`, `none`|
| `position`   | `static`, `relative`, `absolute`, `fixed` |
| `top/right/bottom/left` | Umístění při použití `position` |
| `z-index`    | Vrstevní pořadí (čím vyšší, tím navrchu) |
| `float`      | `left`, `right`                  |
| `clear`      | Zrušení obtékání (`clear: both;`) |
| `<pre> </pre>| je kod psany tak jak je opravdu na psany a chceme zobrazit.

---

## ⚙️ Flexbox základy
```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

| Vlastnost             | Popis                              |
|-----------------------|------------------------------------|
| `display: flex`       | Aktivuje flex kontejner            |
| `justify-content`     | Zarovnání na hlavní ose            |
| `align-items`         | Zarovnání na vedlejší ose          |
| `flex-direction`      | Směr: `row`, `column`              |
| `flex-wrap`           | Zalomení řádků                     |

---

## 🎯 Přechody a animace
```css
.button {
  transition: background 0.3s ease;
}
```

```css
@keyframes myAnimation {
  from { opacity: 0; }
  to   { opacity: 1; }
}
```

---

## 📌 Tipy
- CSS může být **inline**, **interní** (`<style>` v `<head>`), nebo **externí** (`style.css`).
- Kódy barev: `red`, `#ff0000`, `rgb(255,0,0)`.
- Měřicí jednotky: `px`, `em`, `rem`, `%`, `vh`, `vw`.
