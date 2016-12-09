Title: Pirma naujiena

Pagalbininkas šios internetinės svetainės turinio rašymui.

## Įžanga

Turinys talpinamas `content` direktorijoje.

Turinys gali būti dviejų rūšių: įrašai ir puslapiai.

#### įrašai

   Įrašai - tai įvairi rašliava, kuri su laiku pildosi (t.y. kuriami nauji įrašai). Įrašai prisikiriami kategorijoms (pvz. "Naujienos", "Blog'as" ir pan.). Įrašus būdinga rikiuoti pagal sukūrimo datą. Įrašų kategorijos įtraukiamos į navigacijos juostą. Kategorijos - direktorijos talpinamos `content` viduje. Įrašai - failai kategorijų direktorijose.


#### puslapiai

   Puslapiai tai toks turinys, kuris skirtas ilgalaikei, svarbiai, su laiku nesusijusiai informacijai. *Puslapio* pavyzdys: "Kontaktai" - tai tokia informacija, kuri tiesiog turi būti pasiekiama viena nuoroda (arba net fasadiniame svetainės vaizde). Puslapiai dedami specialioje `content/pages` direktorijoje.

## Antraštės

```
# Pirmo lygio antraštė (didelė)
## Antro lygio
### Trečio lygio
#### Ketvirto lygio
##### Penkto lygio
###### Šešto lygio (maža)
```
# Pirmo lygio antraštė (didelė)
## Antro lygio
### Trečio lygio
#### Ketvirto lygio
##### Penkto lygio
###### Šešto lygio (maža)

## Naudingi išsidirbinėjimai

```
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

```

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

## Sąrašai

```
**numeruoti:**

1. First ordered list item
2. Another item
1. Actual numbers don't matter, just that it's a number
4. And another item.

**nenumeruoti:**

* Unordered list can use asterisks
- Or minuses
+ Or pluses

**mandresni sąrašai kažkodėl pagal Markdown taisykles nesigauna. jei labai reikia, galima HTML sintaksę panaudoti:**
<ol>
  <li>asdf asdf asdf</li>
  <li>asdf asdf asdf</li>
  <ul>
    <li>asdf asdf asdf</li>
    <li>asdf asdf asdf</li>
  </ul>
</ol>

`ol` - numeruotas sąrašas

`ul` - nenumeruotas sąrašas

`li` - sąrašo elementas
```
**numeruoti:**

1. First ordered list item
2. Another item
1. Actual numbers don't matter, just that it's a number
4. And another item.

**nenumeruoti:**

* Unordered list can use asterisks
- Or minuses
+ Or pluses

**mandresni sąrašai kažkodėl pagal Markdown taisykles nesigauna. jei labai reikia, galima HTML sintaksę panaudoti:**
<ol>
  <li>asdf asdf asdf</li>
  <li>asdf asdf asdf</li>
  <ul>
    <li>asdf asdf asdf</li>
    <li>asdf asdf asdf</li>
  </ul>
</ol>

`ol` - numeruotas sąrašas

`ul` - nenumeruotas sąrašas

`li` - sąrašo elementas
## Nuorodos

```
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference ](../pages/about.html)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links.
http://www.example.com or <http://www.example.com>

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
```
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference ](../pages/apie.html)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links.
http://www.example.com or <http://www.example.com>

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

## Paveikslai

```
![something about image](../konsnafta-horiz.png)
```
![something about image](../konsnafta-horiz.png)

## Lentelės

```
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

## Skirtuvai

```
Three or more...

---
Hyphens

***
Asterisks

___
Underscores
```
Three or more...

---
Hyphens

***
Asterisks

___
Underscores
