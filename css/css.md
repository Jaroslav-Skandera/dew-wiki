
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
| Vlastnost    | Popis                              |
|--------------|------------------------------------|
| `width`      | Šířka (např. `100px`, `50%`)       |
| `height`     | Výška                              |
| `padding`    | Vnitřní odsazení                   |
| `margin`     | Vnější odsazení                    |
| `border`     | Okraj (např. `1px solid black`)    |
| `box-sizing` | Chování box modelu (`border-box`)  |

---

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
