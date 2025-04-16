Il arrive que l'on veuille styliser des éléments particuliers à l'intérieur d'un **conteneur** ayant une certaine classe. Pour cela, tu utilises l'opérateur `>`.

L'exemple que tu viens d'utiliser a stylisé tous les éléments `<a>` à l'intérieur du conteneur qui a la classe `nav-items`.

Cela te permet de styliser certains liens sans affecter tous les liens de ta page. Cela t'évite de devoir donner une classe à chaque lien individuel.

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 55
line_highlights: 56-60
---

.nav-items > a {

}

--- /code ---
