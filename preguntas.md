<div align="center">
  ---
<span> </span>
</div>
|---|

---

<details><summary><b> </b></summary>
</details>

---

###### 1. En 2006 se presenta el primer móvil Android

- A: el Galaxy S1 de Samsung
- B: No existía Android
- C: El HTC Desire
- D: Nokia N73

<details><summary><b>Answer</b></summary>
<p>

#### Answer: B

Android se usó por primera vez en septiembre de 2008. El primer móvil comercial con Android fue el HTC Desire. El Nokia N73 fue el móvil más vendido en el último trimestre del 2006 y usaba Symbian, el sistema operativo de Nokia

</p>
</details>

---

###### 2. ¿Cuál era el fabricante con más cuota en el 2006?

- A: Samsung
- B: Apple
- C: Nokia
- D: BlackBerry

<details><summary><b>Answer</b></summary>
<p>

#### Answer: C

Nokia etc. Apple aún no vendía móviles.

</p>
</details>

---

###### 3. ¿Cuál fue la gran innovación en los móviles presentada en el MWC de 2008?

- A: Cámara
- B: Reproductor de música
- C: Pantalla táctil
- D: Pantalla plegable

<details><summary><b>Answer</b></summary>
<p>

#### Answer: C

Cosas

</p>
</details>

---

###### 4. ¿Cuál fue el modelo más vendido en 2006?

- A: Nokia 6070
- B: Nokia 7360
- C: Nokia 2310
- D: Nokia 6300

<details><summary><b>Answer</b></summary>
<p>

#### Answer: A

Es este

<img src="https://m.media-amazon.com/images/I/71FZ7YJwnjS._AC_SY879_.jpg">

</p>
</details>

---

###### 5. Which one is true?

```javascript
const bird = {
  size: 'small',
};

const mouse = {
  name: 'Mickey',
  small: true,
};
```

- A: `mouse.bird.size` is not valid
- B: `mouse[bird.size]` is not valid
- C: `mouse[bird["size"]]` is not valid
- D: All of them are valid

<details><summary><b>Respuesta</b></summary>
<p>

#### Answer: A

In JavaScript, all object keys are strings (unless it's a Symbol). Even though we might not _type_ them as strings, they are always converted into strings under the hood.

JavaScript interprets (or unboxes) statements. When we use bracket notation, it sees the first opening bracket `[` and keeps going until it finds the closing bracket `]`. Only then, it will evaluate the statement.

`mouse[bird.size]`: First it evaluates `bird.size`, which is `"small"`. `mouse["small"]` returns `true`

However, with dot notation, this doesn't happen. `mouse` does not have a key called `bird`, which means that `mouse.bird` is `undefined`. Then, we ask for the `size` using dot notation: `mouse.bird.size`. Since `mouse.bird` is `undefined`, we're actually asking `undefined.size`. This isn't valid, and will throw an error similar to `Cannot read property "size" of undefined`.

</p>
</details>
