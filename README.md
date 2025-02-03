
# 📘 The Collatz Bound – Analysis of Central Dynamics and Convergence

_A mathematical paper on the Collatz Conjecture by Stevan Menicanin_

[🔗 Deutsche Version unten](#-die-collatz-schranke--untersuchung-der-zentralen-dynamik-und-konvergenz)

## ✭ Version Note (Version 1.1)

**Current Version:** 1.1 – *Logarithmic instead of exponential reduction*  
After further numerical analysis, it was determined that the number of reduction steps grows on average with \( O(\log_2 n) \), which describes a logarithmic decrease instead of an exponential one. The corresponding textual description has been adjusted in the paper without affecting the mathematical validity of the statements.

## 📜 Abstract

The **Collatz Conjecture** (also known as the (3n+1) problem) is one of the most fascinating unsolved problems in mathematics.  
This paper examines the central mechanisms of the **Collatz transformation** and develops a general bound explaining universal convergence.

Mathematical conclusions:

- Every natural number \( n \) is reduced after a finite number of steps.
- No new stable cycles exist outside {4,2,1}.
- The number of reduction steps grows asymptotically with \( O(\log_2 n) \), meaning a logarithmic rather than an exponential reduction.
- The asymmetry in the transformation plays a key role in number sequences.

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
➡️ [Download (Collatz_Schranke_EN.pdf)](https://github.com/Clickybunty/Collatz/blob/main/27JanuarCollatzSchrankeEn.pdf)

📄 **German Version**  
➡️ [Download (Collatz_Schranke_DE.pdf)](https://github.com/Clickybunty/Collatz/blob/main/27JanuarCollatzSchrankeDe.pdf)

---

## ⚙️ **Usage and LaTeX Compatibility**

If you wish to edit or analyze this work, you can access the **LaTeX source code**.

📜 **English LaTeX Source**:  
➡️ [27JanuarCollatzSchrankeEn.TeX](https://github.com/Clickybunty/Collatz/blob/main/27JanuarCollatzSchrankeEn.TeX)

📜 **German LaTeX Source**:  
➡️ [27JanuarCollatzSchrankeDe.TeX](https://github.com/Clickybunty/Collatz/blob/main/27JanuarCollatzSchrankeDe.TeX)

**Required Packages:**

- `amsmath`, `amssymb`, `hyperref`, `geometry`

---

## 🔏 License & Copyright

This work is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)**.  
This means you are free to share and build upon this work, as long as you credit me as the author.

📜 [View License](https://creativecommons.org/licenses/by/4.0/)

---

# 📘 Die Collatz-Schranke – Untersuchung der zentralen Dynamik und Konvergenz

_Ein mathematisches Paper zur Collatz-Vermutung von Stevan Menicanin_

[English Version below](#-the-collatz-bound--analysis-of-central-dynamics-and-convergence)

## ✭ Versionshinweis (Version 1.1)

**Aktuelle Version:** 1.1 – *Logarithmische statt exponentielle Reduktion*  
Nach weiteren numerischen Analysen wurde festgestellt, dass die Anzahl der Reduktionsschritte im Mittel mit \( O(\log_2 n) \) ansteigt, was eine logarithmische Abnahme beschreibt, anstelle einer exponentiellen. Die entsprechende textliche Beschreibung wurde in der Arbeit angepasst, ohne die mathematische Gültigkeit der Aussagen zu verändern.

## 📜 Abstract

Die **Collatz-Vermutung** (auch bekannt als das (3n+1)-Problem) gehört zu den faszinierendsten ungelösten Problemen der Mathematik.  
Diese Arbeit untersucht die zentralen Mechanismen der **Collatz-Transformation** und entwickelt eine allgemeine Schranke, die die universelle Konvergenz erklärt.

Es wird mathematisch gezeigt, dass:

- Jede natürliche Zahl \( n \) nach einer endlichen Anzahl von Schritten reduziert wird.
- Keine neuen stabilen Zyklen außerhalb von {4,2,1} existieren.
- Die Anzahl der Reduktionsschritte asymptotisch mit \( O(\log_2 n) \) wächst, was eine logarithmische statt einer exponentiellen Reduktion bedeutet.
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
```

---

## 🔏 Lizenz & Urheberrecht

Dieses Werk ist unter der **Creative Commons Attribution 4.0 International (CC BY 4.0)** lizenziert.  
Das bedeutet, dass du es frei teilen und darauf aufbauen kannst, solange du mich als Autor nennst.

📜 [Lizenz anzeigen](https://creativecommons.org/licenses/by/4.0/)

---

---

## 💬 Diskussionen | Discussions

Wir nutzen [GitHub Discussions](https://github.com/Clickybunty/Collatz/discussions) als zentrale Plattform für den Austausch über die **Collatz-Vermutung**.  
We use [GitHub Discussions](https://github.com/Clickybunty/Collatz/discussions) as a central hub for sharing ideas about the **Collatz Conjecture**.

### **📌 Worüber kann hier diskutiert werden? | What can we discuss here?**
✅ **Fragen zur Collatz-Vermutung** | Questions about Collatz  
✅ **Theorien und mathematische Analysen** | Theories and mathematical analysis  
✅ **Vorschläge zur Verbesserung unserer Arbeit** | Suggestions to improve our research  
✅ **Alles rund um Zahlen, Asymmetrie und die Schranke** | Everything related to numbers, asymmetry, and boundaries  

### **💡 Wie kannst du mitmachen? | How to participate?**
1️⃣ **Stell deine Fragen oder teile deine Gedanken.**  
➝ Ask questions and share your thoughts.  

2️⃣ **Antworte auf andere Diskussionen.**  
➝ Reply to ongoing discussions.  

3️⃣ **Respektiere andere Meinungen – wir sind eine lernende Community.**  
➝ Be respectful and open-minded – this is a learning community.  

📄 **Unsere Arbeit auf GitHub:**  
🔗 [Collatz Conjecture Paper](https://clickybunty.github.io/Collatz/)  

📄 **PDF-Downloads | Download the paper as PDF:**  
🔗 **EN:** [Download](https://github.com/Clickybunty/Collatz/blob/main/27JanuarCollatzSchrankeEn.pdf)  
🔗 **DE:** [Download](https://github.com/Clickybunty/Collatz/blob/main/27JanuarCollatzSchrankeDe.pdf)  

💬 **Lass uns tiefer in die Mathematik eintauchen! | Let’s dive deeper into mathematics together!** 🚀



