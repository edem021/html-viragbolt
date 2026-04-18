# 1. Feladat: képek betöltése az oldalon

Az `index.html` fájlban a **Szolgáltatásaink** szekció első három kártyájánál az `<img>` elemek `src` attribútuma üres (`src=""`), ezért a böngésző nem tud képet megjeleníteni.

**Hol dolgozz:** keresd a `<!-- FELADAT 1:` megjegyzéseket a három kép mellett.

**Teendő:**

1. Mindhárom kártyánál írd be a helyes útvonalat az `src=""` helyére (ahol a képek ténylegesen vannak).
2. Töltsd ki az `alt=""` attribútumokat: a kommentben lévő javasolt szöveget használhatod, vagy nagyon hasonló, rövid leírást.

Ha az útvonal helyes, a képek megjelennek a kártyákon.

---

# 2. Feladat: hangsúly a főcímben (`strong`, `em`)

A **`<strong>`** elem fontos, kiemelt szöveget jelöl (a böngésző alapból félkövérrel jeleníti meg). Az **`<em>`** hangsúlyt vagy másmilyen hangnemű olvasást jelez (alapból gyakran dőlt betű).

**Hol dolgozz:** `<!-- FELADAT 2 (README):` megjegyzés a hero szekcióban, a fő `<h1>` felett. A mondat szövege már meg van adva — csak a megfelelő részeket kell elemekbe tenni.

**Teendő:**

1. A főcímben tedd **`<strong>`** elembe a **„Friss”** szót.
2. Ugyanebben a címben tedd **`<em>`** elembe az **„minden alkalomra”** részt (szóközök nélkül, pontosan ez a kifejezés).
3. Nyisd meg az oldalt: a két rész vizuálisan elkülönül (félkövér / dőlt), a szöveg egyben továbbra is olvasható.

---

# 3. Feladat: számozott lista (`ol`, `li`)

A **`<ol>`** (ordered list) számozott felsorolást jelöl, a listaelemeket **`<li>`** (list item) elemekbe tesszük. A böngésző automatikusan 1., 2., 3. számozást ad.

**Hol dolgozz:** `<!-- FELADAT 3 (README):` megjegyzés alatti blokk, a hero szekció és a Valentin-napi akció között. A három mondat szövege már meg van adva.

**Teendő:**

1. A **„Hogyan rendelsz tőlünk?”** cím maradhat `<h2>` elemben.
2. A három `<p>` elemben lévő mondatot cseréld le egy **`<ol>`** listára: mindegyik mondat legyen külön **`<li>`** elemben, a megfogalmazás változatlan maradjon.
3. Nyisd meg az oldalt: a három lépés számozva jelenik meg.

---

# 4. Feladat: „Kapcsolat” szekció — szerkezet (section, div, lista)

**Hol dolgozz:** `<!-- FELADAT 4 (README):` megjegyzés alatti blokk. A cím, bevezető és elérhetőségek szövege már meg van adva.

**Teendő:**

1. Cseréld a külső `<div>`-et **`<section id="kapcsolat">`** elemre.
2. Tagold **`<div>`** elemekkel, ahol logikus (pl. szövegblokk külön, elérhetőségek külön).
3. A cím, telefon és e-mail kerüljön **`<ul>` / `<li>`** listába vagy más, átlátható HTML szerkezetbe — a megjelenő szöveg maradjon ugyanaz, mint a fájlban.

---

# 5. Feladat: kiemelt üzenet (saját osztály + CSS)

**Hol dolgozz:** `<!-- FELADAT 5 (README):` megjegyzés alatti `<aside>` blokk. A cím és a bekezdés szövege már meg van írva.

**Teendő:**

1. Adj az elemnek egy **saját osztálynevet** (pl. `kiemelt-uzenet`).
2. A `style.css`-ben állítsd be a hátteret (background), szegélyt(border) vagy szövegszínt(color), hogy elkülönüljön a többi résztől.

---

# 6. Feladat: negyedik szolgáltatás kártya — kép

**Hol dolgozz:** `<!-- FELADAT 6 (README):` megjegyzés alatti kártya (Koszorúk és megemlékezés). A cím és a leíró szöveg már meg van adva.

**Teendő:**

1. Ellenőrizd, hogy a kártya szerkezete megegyezik a másik hároméval; ha valami hiányzik, egészítsd ki.
2. Töltsd ki az `img` **`src`** és **`alt`** mezőit; az alt-hoz használhatod a kommentben javasolt szöveget.

---

# 7. Feladat: háttérkép a felső blokk szülő `div`-jén

A navigáció alatt van egy **szülő `div`**, ami a **hero szekciót**, a **„Hogyan rendelsz?”** blokkot és a **Valentin-napi akció** `<aside>` részt együtt fogja. Erre a szülőre kerül a **háttérkép** (CSS `background-*` tulajdonságokkal), nem külön minden belső elemre.

**Hol dolgozz:** `<!-- FELADAT 7 (README):` megjegyzés a szülő `div` mellett; a stílus a `style.css` fájlban a **`.fejlec-hatter`** szabályban van.

**Teendő:**

1. Nézd meg a `style.css`-ben a **`.fejlec-hatter`** szabályt: már szerepel példa **`background-image`** (URL-lel). Cseréld le **saját képed útvonalára** (pl. `images/sajat-hero.jpg`), ha a kép a projekt mappájában van — vagy hagyd a minta URL-t, ha csak a tulajdonságokat gyakorlod.
2. Ellenőrizd, hogy szerepeljen **`background-size: cover`**, **`background-position: center`** és **`background-repeat: no-repeat`** (így a kép kitölti a sávot, nem csempézi).
3. Nyisd meg az oldalt: a háttér a teljes felső blokk mögött látszik; a hero szövege továbbra is a **`.hero`** szabályoktól kap színt és árnyékot.

---

*Tipp a diáknak:* az [MDN HTML](https://developer.mozilla.org/hu/docs/Web/HTML) és [MDN CSS](https://developer.mozilla.org/hu/docs/Web/CSS) oldalain megtalálod az elemeket, attribútumokat és a stílusok alapjait.
