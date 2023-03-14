% Praesentation in Markdown
% Referent: Ackermann Yannick
% Date: \today

---
theme: "AnnArbor"
header-includes:
colortheme: "seahorse"
fonttheme: "structurebold"
author: Ackermann Yannick
--- 

# Erste Folie
Dies ist eine in Markdown erstellte Präsentation und übersetzt mit Pandoc in einer Beamer-Präsentation als PDF.
````bash
pandoc -t beamer <filename.mc> -o <praesentationname>.pdf
````

# Aufzählung mit Formatierung
- punkt 1 mit *kursivem text*
- punkt 2 mit **fettem text**
- punkt 3 mit ~~durchgestrichenem text~~

# Formeln und Quoting
> **Merke**
> Markdown und Pandoc sind cool und mächtig.

$$ \int_a \limits ^\infty \frac{x^2-a}{e^{x-b}} dx $$
$$ f(x) \approx \sqrt{2-x} $$
$$ a^b $$
$$ U_{eff} = \frac{U}{\sqrt{2}}$$
$$ a_1, a_2, \dots ,a_n$$

# Bilder einbinden

````
![Umlet Screenshot](UMlet_screenshot.PNG)
````
![Umlet Screenshot](UMlet_screenshot.PNG)
