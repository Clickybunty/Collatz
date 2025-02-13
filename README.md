# 📘 The Collatz Bound – Analysis of Central Dynamics and Convergence

_A mathematical paper on the Collatz Conjecture by Stevan Menicanin_

[🔗 Deutsche Version unten](#-die-collatz-schranke--untersuchung-der-zentralen-dynamik-und-konvergenz)


### **Current Status of the Investigation (February 13, 2025)**  

The previously established **growth boundary of \( d(n) \) cannot currently be considered confirmed**. A 145-digit number has fallen below the expected threshold, necessitating a reassessment of the methodology.  

To verify this anomaly, nearby numbers within a range of ±500,000 around this value were tested. Additional numbers exhibiting the same growth rate were identified, raising questions about whether the discrepancy is due to a **measurement error, a methodological flaw, or a fundamental invalidity of the boundary**.  

Special attention is being given to potential **rounding errors** and the **precision of calculations**, especially when dealing with extremely large numbers. Since numerical inaccuracies or methodological inconsistencies cannot be ruled out as influencing factors, the analysis is ongoing. The goal is to **identify the root cause and establish a reliable conclusion regarding the stability of the boundary**.


## ✭ Version Note (Version 3.1)

**Current Version:** 3.1 – *Refined Asymmetry Analysis, Structural Constraint of \( d(n) \), and Multiplication-Division Ratio*  
This version strengthens the deterministic approach by eliminating probabilistic assumptions. The distance function \( d(n) \) proves that \( 2n \) never appears in the Collatz sequence of \( n \), making alternative cycles structurally impossible.

## 📜 Abstract

The **Collatz Conjecture** (also known as the (3n+1) problem) is one of the most intriguing open problems in mathematics.  
This paper presents a new structural analysis of the **Collatz transformation**, proving that universal convergence is inevitable.

### Key mathematical conclusions:

- Every natural number \( n \) enters the cycle \( \{4,2,1\} \) after a finite number of steps.
- No alternative stable cycles exist outside \( \{4,2,1\} \).
- The number of reduction steps follows \( O(\log_2 n) \), confirming logarithmic rather than exponential reduction.
- The distance function \( d(n) \) grows strictly monotonically and ensures that \( 2n \) never appears in the Collatz sequence.
- Structural asymmetry in multiplication and division fundamentally prevents alternative cycles.

---

## 📂 Table of Contents

- [📜 Abstract](#-abstract)
- [📥 Download PDFs](#-download-pdfs)
- [⚙️ Usage and LaTeX Compatibility](#️-usage-and-latex-compatibility)
- [🛠️ LaTeX Compilation](#️-latex-compilation)
- [🔏 License & Copyright](#-license--copyright)

---

## 📥 **Download PDFs**

Download the full paper as a PDF:

📄 **English Version**  
➡️ [Download (Collatz_Bound_EN.pdf)](https://github.com/Clickybunty/Collatz/blob/main/27JanuarCollatzSchrankeEn.pdf)

📄 **German Version**  
➡️ [Download (Collatz_Bound_DE.pdf)](https://github.com/Clickybunty/Collatz/blob/main/27JanuarCollatzSchrankeDe.pdf)

📊 **Filtered Collatz Results Data**  
➡️ [Download (filtered_collatz_results.csv)](https://github.com/Clickybunty/Collatz/blob/main/filtered_collatz_results.csv)

---

## ⚙️ **Usage and LaTeX Compatibility**

If you wish to edit or analyze this work, you can access the **LaTeX source code**.

📜 **English LaTeX Source**:  
➡️ [Collatz_Bound_EN.TeX](https://github.com/Clickybunty/Collatz/blob/main/27JanuarCollatzSchrankeEn.TeX)

📜 **German LaTeX Source**:  
➡️ [Collatz_Bound_DE.TeX](https://github.com/Clickybunty/Collatz/blob/main/27JanuarCollatzSchrankeDe.TeX)

**Required Packages:**

- `amsmath`, `amssymb`, `hyperref`, `geometry`, `pgfplots`, `tikz`

---

## 🛠️ **LaTeX Compilation**

To compile the PDF yourself, use the following commands:

```sh
pdflatex Collatz_Bound_EN.TeX
pdflatex Collatz_Bound_DE.TeX
```

---

## 🔏 License & Copyright

This work is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)**.  
This means you are free to share and build upon this work, as long as you credit me as the author.

📜 [View License](https://creativecommons.org/licenses/by/4.0/)

---

# 📘 Die Collatz-Schranke – Untersuchung der zentralen Dynamik und Konvergenz

_Ein mathematisches Paper zur Collatz-Vermutung von Stevan Menicanin_

[English Version below](#-the-collatz-bound--analysis-of-central-dynamics-and-convergence)



### Aktueller Stand der Untersuchung (13. Februar 2025)
Die bisherigen Ergebnisse zur 
# Wachstumsgrenze von d(n) sind derzeit nicht als bestätigt anzusehen. 
Eine 145-stellige Zahl hat die **Schranke unterschritten**, 
was eine erneute Prüfung der Methodik erforderlich macht.

Zur Verifikation wurden naheliegende Zahlen im Bereich von ±500.000 um diesen Wert herum getestet. 
Dabei wurden weitere Zahlen mit **identischer Wachstumsrate** gefunden. 
Dies wirft Fragen auf, 
ob ein **Messfehler, ein methodischer Fehler oder eine grundsätzliche Ungültigkeit der Schranke** vorliegt.

Besondere Aufmerksamkeit gilt möglichen **Rundungsfehlern** sowie der Genauigkeit der Berechnungen, 
insbesondere im Umgang mit extrem großen Zahlen. 
Da nicht ausgeschlossen werden kann, 
dass numerische Ungenauigkeiten oder eine **fehlerhafte Methodik** das Ergebnis beeinflusst haben, 
wird die Analyse fortgesetzt. 
Ziel ist es, 
die Ursachen zu klären und 
eine belastbare Aussage zur Stabilität der Schranke zu treffen.

## ✭ Versionshinweis (Version 3.1)

**Aktuelle Version:** 3.1 – *Präzisierte Asymmetrieanalyse, strukturelle Schranke von \( d(n) \) und Multiplikations-Divisions-Verhältnis*  
Diese Version stärkt den deterministischen Ansatz, indem sie probabilistische Annahmen eliminiert. Die Distanzfunktion \( d(n) \) zeigt, dass \( 2n \) niemals in der Collatz-Folge von \( n \) auftritt, wodurch alternative stabile Zyklen strukturell ausgeschlossen sind.

## 📜 Abstract

Die **Collatz-Vermutung** (auch bekannt als das (3n+1)-Problem) gehört zu den faszinierendsten offenen Problemen der Mathematik.  
Diese Arbeit präsentiert eine neue strukturelle Analyse der **Collatz-Transformation** und zeigt, dass die universelle Konvergenz unausweichlich ist.

### Zentrale mathematische Schlussfolgerungen:

- Jede natürliche Zahl \( n \) erreicht nach einer endlichen Anzahl von Schritten den Zyklus \( \{4,2,1\} \).
- Keine alternativen stabilen Zyklen existieren außerhalb von \( \{4,2,1\} \).
- Die Anzahl der Reduktionsschritte folgt \( O(\log_2 n) \), was eine logarithmische statt einer exponentiellen Reduktion belegt.
- Die Distanzfunktion \( d(n) \) wächst streng monoton und stellt sicher, dass \( 2n \) niemals in der Collatz-Folge erscheint.
- Die strukturelle Asymmetrie der Multiplikation und Division verhindert alternative stabile Zyklen.

---

## 📂 Inhaltsverzeichnis

- [📜 Abstract](#-abstract)
- [📥 Download der PDFs](#-download-der-pdfs)
- [⚙️ Nutzung und LaTeX-Kompatibilität](#️-nutzung-und-latex-kompatibilität)
- [🛠️ LaTeX-Kompilierung](#️-latex-kompilierung)
- [🔏 Lizenz & Urheberrecht](#-lizenz--urheberrecht)

---

## 📥 **Download der PDFs**

Die vollständige Arbeit kann hier als PDF heruntergeladen werden:

📄 **Englische Version**  
➡️ [Download (Collatz_Bound_EN.pdf)](https://github.com/Clickybunty/Collatz/blob/main/27JanuarCollatzSchrankeEn.pdf)

📄 **Deutsche Version**  
➡️ [Download (Collatz_Bound_DE.pdf)](https://github.com/Clickybunty/Collatz/blob/main/27JanuarCollatzSchrankeDe.pdf)

---

## 🛠️ **LaTeX-Kompilierung**

Falls du die PDF selbst kompilieren möchtest, kannst du folgende Befehle nutzen:

```sh
pdflatex Collatz_Bound_EN.TeX
pdflatex Collatz_Bound_DE.TeX
