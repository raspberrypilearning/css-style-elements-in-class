Soms wil je specifieke elementen binnen een **container** die een bepaalde klasse heeft, opmaken. Om dit te doen, gebruik je de `>` operator.

Het voorbeeld dat je zojuist hebt gebruikt maakt alle `<a>` elementen op binnen een container die de `nav-items` klasse heeft.

Dit stelt je in staat bepaalde links op te maken zonder alle links op je pagina te beïnvloeden. Je hoeft dan niet aan elke afzonderlijke link een klasse toe te kennen.

## --- code ---

language: css
filename: style.css
line_numbers: true
line_number_start: 55
line_highlights: 56-60
-----------------------------------------------------------

.nav-items > a {

}

\--- /code ---
