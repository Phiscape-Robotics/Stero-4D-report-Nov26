# Stereo 4D project report

LaTeX project report arranged for direct compilation in Overleaf.

In Overleaf, select `main.tex` at the repository root as the main document and use the pdfLaTeX compiler. All chapters, front matter, figures, and references use paths relative to this root.

Build from this folder (create the build directory first if needed):

    mkdir -p build
    pdflatex -interaction=nonstopmode -halt-on-error -output-directory=build main.tex

Run three times to resolve contents and references. The review copy is `Stereo-Based 4D Scene Reconstruction - Project Report - 16 November 2026.pdf`.

Before submission, confirm institutional declaration/certificate wording and signatures. The HoD is Dr. Shajahan E S, verified from the CET ECE faculty page on 16 November 2026. The report reflects the progress presentation, not a completed stereo/temporal evaluation. Figures are extracted unchanged from supplied slides 7 and 8. Experiment counts come from the presentation and experiment logs; the original cloud runs were not repeated.
