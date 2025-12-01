
📄 My Resume

Welcome!
This repository contains the source code for my résumé, written in LaTeX.
Also you can use it for cover letter too.

You can download the latest compiled PDF from the Releases section:

👉 Download Latest Resume￼

⸻

📦 Repository Structure

/resume/
    resume.tex          # Main Resume LaTeX file
/cover-letter/
    cover-letter.tex    # Main Cover Letter LaTeX file    
/components/
    title.tex           # Title section
    ...                 # Other sections
structure.tex           # Shared layout & configuration
Makefile                # Build instructions
.github/workflows/
    main.yml            # GitHub Action to auto-build and release PDF


⸻

🚀 Automated Build & Release

Every push to the main branch triggers an automated GitHub Action:
	•	Compiles resume.tex using LuaLaTeX
	•	Generates the final resume.pdf
	•	Creates a tagged GitHub Release
	•	Uploads the PDF to the release assets

This means the PDF is always up-to-date with your latest changes.

⸻

🔧 Building Locally

If you want to build the resume on your own machine:

Prerequisites
	•	A full LaTeX distribution (e.g., TeX Live)
	•	lualatex
	•	make

Build Command

make build-resume

The final resume.pdf will appear inside:

/resume/resume.pdf

Also you can easily go to the resume or cover-letter directory and runs "pdflatex resume.tex(or cover-letter.tex)".

⸻

🪪 License

Feel free to make a copy of this resume structure for your own use.
If you do, a reference link back to this repository would be appreciated. 🍏

⸻

⭐️ Feedback

If you have suggestions to improve the LaTeX template or want a better design, feel free to open an issue.

⸻