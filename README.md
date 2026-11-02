# CAL00 Online Modules

Self-paced online modules for **Pre-Calculus**
(Instr. Ryan M. Vitalez, LPT, Department of Earth and Space Sciences, Rizal Technological University),
following Stewart, Redlin and Watson, *Precalculus: Mathematics for Calculus*. Students use them on days when class
cannot meet in person.

**Entry point:** https://mrvitalez.github.io/PreCalculus-online-module/ sends students to the student site, which is a
Google Apps Script web app open only to **@rtu.edu.ph** accounts. The instructor has a separate admin site on the
same deployment (`?page=admin`). Setup: [INSTRUCTOR-SETUP.md](INSTRUCTOR-SETUP.md).

Each module follows one chapter of the course:

1. **Discussion**: one part per topic of the chapter, with definitions, key equations, original figures and common
   mistakes ("Take note").
2. **Worked examples**: 12 problems solved step by step (Given, Step 1, Step 2, …, Answer, Check), solutions hidden
   until opened.
3. **Lecture video**: one free lecture (cited on the page) that pauses for three multiple-choice questions;
   answers are recorded.
4. **Activity**: 10 graded items plus a reflection. Answers can be numbers, exact values (`sqrt(5)`, `-7/2`,
   `ln(20)/ln(5)`; `log` is base 10) or formulas (`(2x+1)/(3-x)`); formulas are checked for equivalence, so any
   correct form is accepted. The student's RTU email is detected automatically; they enter their name, student
   number and block and section, write solutions with a symbol/LaTeX toolbar and live preview, and see their score
   and per-item results on submit.

| # | Module | Topics | Video |
|---|--------|--------|-------|
| 1 | Fundamentals of Algebra | Real Numbers; Exponents and Radicals; Algebraic Expressions; Rational Expressions; Equations; Complex Numbers; Inequalities; The Coordinate Plane; Graphs of Equations; Circles; Lines; Solving Equations and Inequalities Graphically | Introduction to the quadratic equation (Khan Academy) |
| 2 | Functions | Functions; Graphs of Functions; Getting Information from the Graph of a Function; Average Rate of Change of a Function; Linear Functions and Models; Transformations of Functions; One-to-One Functions and Their Inverses | Introduction to function inverses (Khan Academy) |
| 3 | Polynomial and Rational Functions | Quadratic Functions and Models; Polynomial Functions and Their Graphs; Dividing Polynomials; Real Zeros of Polynomials; Complex Zeros and the Fundamental Theorem of Algebra; Rational Functions; Polynomial and Rational Inequalities | Applying the rational root theorem (Khan Academy) |
| 4 | Exponential and Logarithmic Functions | Exponential Functions; The Natural Exponential Function; Logarithmic Functions; Laws of Logarithms; Exponential and Logarithmic Equations; Modeling with Exponential Functions; Logarithmic Scales | Introduction to logarithm properties (Khan Academy) |
| 5 | Trigonometric Functions: Unit Circle Approach | The Unit Circle; Trigonometric Functions of Real Numbers; Trigonometric Graphs; Inverse Trigonometric Functions and Their Graphs; Modeling Harmonic Motion | Unit Circle Definition of Trig Functions (Khan Academy) |
| 6 | Trigonometric Functions: Right Triangle Approach | Angle Measure; Trigonometry of Right Triangles; Trigonometric Functions of Angles; Inverse Trigonometric Functions and Right Triangles; The Law of Sines; The Law of Cosines | Proof of the law of cosines (Khan Academy) |

Problem sets (answered in the notebook, linked from the home page):

- Problem Set 1: Algebra and Functions (modules 1, 2; Long Examination 1)
- Problem Set 2: Polynomial, Rational, Exponential and Logarithmic Functions (modules 3, 4; Long Examination 2)
- Problem Set 3: Trigonometry (modules 5, 6; Long Examination 3)

The discussions, examples, figures and problems are original and follow the instructor's module notes and the order
and notation of Stewart, Redlin and Watson; no text or figures are copied from the book. Videos: Khan Academy
(CC BY-NC-SA 3.0 US). Videos can be changed in the admin site.

## Files

```
index.html, modules/      Entry pages that send visitors to the RTU-only student site
assets/config.js          The student site URL (set once by the instructor)
assets/style.css          Shared styles (Forest Green with Tangerine theme)
content/                  Lessons, activities, problem sets, manifest and syllabus (no answers)
img/                      Figures and the university seal
apps-script/              Code for the Apps Script project: Code.gs, Student.html, Admin.html, Styles.html
```

The answer key and the video question answers are **not** in this repository. They are seeded from a private
`Seed.gs` file and then kept only in the instructor's Google Sheet.
