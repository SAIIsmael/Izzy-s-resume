# Izzy's resume
This is a modern and clean LaTeX resume template designed to be professional, modern, and easy to use. The template is inspired by Jake's resume template, with a few tweaks to improve its functionality and design. It's perfect for anyone looking to create a sleek, ATS-friendly resume with LaTeX.

## Features
- Simple and clean layout.
- Fully customizable for different job roles and experiences.
- Compatible with Overleaf and local LaTeX setups.
- Responsive to different page sizes (A4, letter).
- Includes sections for summary, experience, education, and skills.

## Clone or Download
You can use this template in two ways:

### 1. **Clone it on Overleaf**
For the easiest experience, you can clone this template directly on Overleaf:
[Click here to clone the project on Overleaf](https://www.overleaf.com/read/tqcrxgrvdwyr#2e019f
)

### 2. **Download the Source Code**
Alternatively, you can clone the source code from this repository and compile it locally using a LaTeX editor of your choice (e.g., TeXShop, TeXworks, or command-line LaTeX).

## How to Use the Template

### Step 1: Set Up Your LaTeX Environment

#### **For Overleaf:**
Simply clone the project and start editing. Overleaf takes care of all dependencies automatically, so you don’t need to worry about installing packages.

#### **For Local Compilation:**

If you're using a local LaTeX editor, you'll need to ensure that you have the necessary packages installed. This template relies on the following packages:
- `latexsym`
- `fullpage`
- `titlesec`
- `marvosym`
- `color` (with `usenames,dvipsnames`)
- `verbatim`
- `enumitem`
- `hyperref` (with `hidelinks`)
- `fancyhdr`
- `babel` (English)
- `tabularx`
- `fontawesome5`
- `academicons`
- `sourcecodepro` (Source Code Pro font)

If you're using a package manager for your LaTeX distribution (e.g., MiKTeX or TeX Live), these packages should be available by default. If not, you can manually install them.

### Step 2: Edit Your Resume
1. Open the `main.tex` file in your LaTeX editor.
2. Customize the fields as needed:
   - Replace your name, contact information, and summary in the header.
   - Modify the experience, skills, and education sections with your details.
   - The template is designed with easy-to-understand commands like `\resumeItem`, `\resumeSubheading`, and `\resumeItemListStart`, so you can easily update the content.

### Step 3: Compile Your Document
Once you’ve made your changes, compile the document using your LaTeX editor. Overleaf automatically compiles your document for you, while in a local setup, use the command:

```bash
pdflatex main.tex
```
If you are using fonts like Source Code Pro or icons like FontAwesome5 or Academicons, ensure you have them installed or modify the template to use alternative fonts/icons.

### Step 4: Export the PDF
Once compiled, you will have a PDF file of your resume ready to be printed or shared online.

---
#### License
This template is open-source and can be freely used or modified. Feel free to customize it for your needs, share it with others, or contribute to its development. It’s shared under the MIT License.

#### Contributions
If you find a bug or want to improve the template, feel free to open an issue or submit a pull request. Contributions are welcome!

#### Acknowledgments
This template is inspired by Jake's LaTeX resume template, with additional tweaks and enhancements to make it more flexible and easier to use.

Happy LaTeX-ing! 😊