# Beamer Slide Creation with AI Assistance

## 📌 Introduction
This guide explains how to use AI assistance to generate **Beamer slides** using the **ANU LaTeX slide template**. The AI formats content into a structured **LaTeX presentation**, making slide creation efficient and professional.

---

## 🛠 Prerequisites
Before generating slides, ensure you have the following:

### ✅ Required Files:
- **LaTeX installation** (TeX Live, MiKTeX, Overleaf, etc.)
- **ANU Slide Template Files**:
  - `anu-slide.cls` (for ANU-specific branding)
  - `anu.sty` (style configurations)
  - `logo/anu.png` and `logo/anu_crest_gold.png` (branding assets)
  - `slide.tex` (example Beamer slide template)
- A **LaTeX editor** (Overleaf, TeXworks, VS Code with LaTeX Workshop, etc.)

---

## ⚙️ How to Use AI Assistance for Slide Creation

### 1️⃣ **Provide Content for Slides**
You can request slides by providing:
- **Title of the presentation**
- **Sections and slide titles**
- **Bullet points or text content**
- **Equations (if needed)**
- **Figures (optional, using TikZ or images)**

#### Example request:
\`\`\`plaintext
"Generate Beamer slides on Quantum Mechanics, covering wave functions, 
Schrödinger's equation, and quantum states."
\`\`\`

---

### 2️⃣ **Generating Slides**
The AI formats your content into **LaTeX Beamer** slides using the ANU template. The structure includes:
- **Title slide**
- **Section headers**
- **Bullet-point slides**
- **Equations using LaTeX math syntax**
- **Figures using TikZ or `\includegraphics{}`**

#### 📌 Example Output (LaTeX):
\`\`\`latex
\begin{frame}{Wave Functions in Quantum Mechanics}
    A wave function $\Psi(x,t)$ describes the quantum state of a particle:
    
    \begin{equation}
    i\hbar \frac{\partial}{\partial t} \Psi(x,t) =
    \left[ -\frac{\hbar^2}{2m} \nabla^2 + V(x,t) \right] \Psi(x,t)
    \end{equation}
\end{frame}
\`\`\`

---

### 3️⃣ **Using Overleaf for Compilation**
Overleaf is an online LaTeX editor that simplifies compilation:

#### ✅ Steps to Use Overleaf:
1. **Go to** [Overleaf](https://www.overleaf.com/)
2. **Create a new project** → Upload the following files:
   - `anu-slide.cls`
   - `anu.sty`
   - `slide.tex`
   - Any required images or figures
3. **Click "Recompile"** to generate the PDF.
4. **Download the PDF** or share the project link.

---

### 4️⃣ **Downloading and Compiling Locally**
If you prefer to compile **locally**, use the following command:

\`\`\`sh
pdflatex slide.tex
\`\`\`

Ensure all required files are in the same directory.

---

## 🎯 Features Supported
- **Lists** (`itemize` or `enumerate`)
- **Equations & Math** (`align`, `equation`, `frac{}`)
- **Figures** (via TikZ or `\includegraphics{}` for external images)
- **Pauses** (`\pause` to reveal content progressively)

---

## 📌 Example Workflow
### 📌 Request:
\`\`\`plaintext
"Make slides for a Machine Learning introduction covering supervised learning, 
unsupervised learning, and deep learning."
\`\`\`
### 📌 AI Output:
1. **Title Slide**
2. **Supervised Learning (Bullet Points)**
3. **Unsupervised Learning (Bullet Points)**
4. **Deep Learning (Equation for Neural Networks)**

---

## 🛠 Troubleshooting
### ❌ Errors While Compiling?
- Ensure all necessary `.cls` and `.sty` files are available.
- Check for missing brackets `{}` or incorrect LaTeX syntax.
- Use **Overleaf** for debugging if local compilation fails.

---

## 🎓 Conclusion
This AI-powered workflow **automates Beamer slide creation**, ensuring well-structured and professional presentations. Simply provide your content, and the AI will format it into a polished **LaTeX presentation**.

🚀 **Happy TeX-ing!** 🎓
