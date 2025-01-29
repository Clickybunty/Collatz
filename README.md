# 📘 Die Collatz-Schranke – Untersuchung der zentralen Dynamik und Konvergenz
*Ein mathematisches Paper zur Collatz-Vermutung von Shimon Ben Abraham (alias Stevan Menicanin)*

[English Version below](#-the-collatz-bound--analysis-of-central-dynamics-and-convergence)

## 📜 Abstract
Die **Collatz-Vermutung** (auch bekannt als das (3n+1)-Problem) gehört zu den faszinierendsten ungelösten Problemen der Mathematik.  
Diese Arbeit untersucht die zentralen Mechanismen der **Collatz-Transformation** und entwickelt eine allgemeine Schranke, die die universelle Konvergenz erklärt.

Es wird mathematisch gezeigt, dass:
- Jede natürliche Zahl \( n \) nach einer endlichen Anzahl von Schritten reduziert wird.
- Keine neuen stabilen Zyklen außerhalb von {4,2,1} existieren.
- Die Asymmetrie in der Transformation eine Schlüsselrolle bei der Abfolge der Zahlen spielt.

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
➡️ [Download (Collatz_Schranke_EN.pdf)](https://github.com/Clickybunty/Collatz/blob/main/27JanuarCollatzSchrankeEn.pdf)

📄 **Deutsche Version**  
➡️ [Download (Collatz_Schranke_DE.pdf)](https://github.com/Clickybunty/Collatz/blob/main/27JanuarCollatzSchrankeDe.pdf)

---

## ⚙️ **Nutzung und LaTeX-Kompatibilität**
Falls du die Arbeit bearbeiten oder nachvollziehen möchtest, findest du hier den **LaTeX-Quellcode**.

📜 **Englischer LaTeX-Quelltext**:  
➡️ [27JanuarCollatzSchrankeEn.TeX](https://github.com/Clickybunty/Collatz/blob/main/27JanuarCollatzSchrankeEn.TeX)

📜 **Deutscher LaTeX-Quelltext**:  
➡️ [27JanuarCollatzSchrankeDe.TeX](https://github.com/Clickybunty/Collatz/blob/main/27JanuarCollatzSchrankeDe.TeX)

**Erforderliche Pakete:**  
- `amsmath`, `amssymb`, `hyperref`, `geometry`

---

## 🛠️ **LaTeX-Kompilierung**
Falls du die PDF selbst kompilieren möchtest, kannst du folgende Befehle nutzen:

```sh
pdflatex 27JanuarCollatzSchrankeEn.TeX
pdflatex 27JanuarCollatzSchrankeDe.TeX
