---
tag: 📥️/🎥️
status: 🟨
moc:: [[]]
sorted: false
langugue: es
file_creation_date: [[2022-05-13]]

aliases: []
cssclass: 

url: 
keywords:: [ [[LaTeX]], [[Equations]], [[Expressions]], [[Guide]] ]
guests:: [ [[]] ]
---


## + Comprehensive Overview - LaTeX Mathjax Equation In Obsidian
<button class="date_button_today"> Type:: [[+]] </button><button class="date_button_today">Host:: [[Bryan Jenks]] </button>

<button class="date_button_today">Reviewed_date:: [ [[2022-05-03]] , ] </button> <button class="date_button_today">Released_date:: [[2021-01-25]]  </button>

<center><iframe width="820" height="420" src="https://www.youtube.com/embed/FA0z7oR7OWc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>

---


## LaTeX 
Is a high-quality typesetting system; it includes features designed for the production of technical and scientific documentation.
LaTeX is the de-facto standard for the communication and publication of scientific documents.

- All the other packages that come with LaTeX you can create resumes. books, papers, documents, flow-charts 
Is a plain-text extensible type-setting system. **Uses commands and Macros that can then be reprogrammed, remapped and then compiled for extremely granular controlled outputs and results.**
 
**Overleaft.com is like the google docs for LaTeX**

- [[01:08]] MathJax is a tool to write equations as they appears on real paper 

[[05:37]] Two main types of equations.

### Inline Expresions: 
*They are designed to accompany text corpus in a **discrete way***.
They use **only two dollar signs** :  \$...$ -> $...$ 

### Centered Equation:
They divide and go centre in the text as a way of drawing your attention.
They take double dollar signs $$...$$

- [[08:43]] To change the font size you need to use this CSS custom code in the themes file
```css
.MJX-TEX{
    font-size:180 %;
}
```

- [[09:12]] In LaTeX you are going to use again and again the backslash character **\**, with this you can escape them. Turns characters into plain text elements, they don't represent a particular functionality of the program itself 
 
### Syntax
We start the commands with **\*. 
LaTeX uses a lot of the less commonly used symbols for programming.
The principal elements are:
- Backslash **\**
- Curly Braces **{}**

- [[11:44]] **Obligatory inputs takes burly brackets and optional parameters takes square brackets** 
*Often there are several optional parameters that you can provide to the command to have differing changes*

### Basic Operations
- Superscript: ****
- Subscript: **_**
- Square root: \sqrt{}
- Fraction: \frac{}{}
- Summaries: \sum_{}

### How To use Math Calligraphy
Is as easy as inserting \mathcal{}

### Dots for ellypting usage
#### Horizontal Dots
\ldots -> $\ldots$
#### Vertical Dots 
\vdots  -> $\vdots$

### Fencing 
Parenthesis: \( \)
Square Brackets: \[ \]
Curly Brakets: \{ \}
Angle Brackets: \langle \rangle, it is **<>**

- [[26:35]] Creating Arrays:
We need to create an environment
**\begin{array}{rcl}
   0&6&7 \\
   9&7&3 \\
   6&4&1 \\
\end{array}**
$$\Bigg( \; \begin{array}{rcl}
   0&6&7 \\
   9&7&3 \\
   6&4&1 \\
\end{array} \; \Bigg) $$
The rcl indicates how the columns will be rendered.
The first one is to the **right**, the second in the **center **and the third one on the **left**.

### Spacing Command
0- $x\!y$ Gives no separation spac
1- $xy$ Gives the normal space between the characters
2- $x\,y$
3- $x\:y$
4- $x\;$
5- $x \quad y$
6- $x\qquad y$

- [[34:16]] With a preamble you don't have to type stuff in a repetitive fashion, over and over again.
Preamble means that is processed before the rest of your document.

- [[34:40]] Extended MathJax.
The preamble allows you to customise your own macros for LaTeX usage.
I could allow you to create colourful formulas 
