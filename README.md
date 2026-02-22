# Learning Mathematics

A curated collection of resources for learning mathematics: linear algebra, analysis, topology, algebra, probability, and more.

## Table of Contents
- [Suggested Learning Path](#suggested-learning-path)
- [General](#general)
- [Linear Algebra](#linear-algebra)
- [Analysis](#analysis)
- [Complex Analysis and Fourier](#complex-analysis-and-fourier)
- [Probability and Statistics](#probability-and-statistics)
- [Measure Theory and Stochastic Processes](#measure-theory-and-stochastic-processes)
- [Abstract Algebra](#abstract-algebra)
- [Number Theory](#number-theory)
- [Functional Analysis](#functional-analysis)
- [Category Theory](#category-theory)
- [Topology](#topology)
- [Geometry](#geometry)
- [Partial Differential Equations](#partial-differential-equations)
- [Numerical Analysis and Optimization](#numerical-analysis-and-optimization)
- [Dynamical Systems and Chaos](#dynamical-systems-and-chaos)
- [Machine Learning and Deep Learning](#machine-learning-and-deep-learning)
- [Formalization and Exercises (Lean 4)](#formalization-and-exercises-lean-4)

## Suggested Learning Path

> Hour estimates are rough ranges for self-study including exercises. Your pace will differ. Video-only hours assume active note-taking. Book hours assume working most exercises. At 2 hrs/day the full path takes ~3-5 years.

### Phase 0: Orientation (~15 hrs)
Get the big picture before diving in.
1. [The two cultures of mathematics](https://www.dpmms.cam.ac.uk/~wtg10/2cultures.pdf) - Read this essay first (~1 hr)
2. [All the Math You Missed - Thomas Garrity](https://www.cambridge.org/universitypress/subjects/mathematics/recreational-mathematics/all-math-you-missed-need-know-graduate-school-2nd-edition) - Skim to see what lies ahead (~15 hrs)

### Phase 1: Foundations (~400-600 hrs)
Linear algebra, analysis, and learning to prove. Run these three tracks in parallel.

**Track A - Linear Algebra (~150-250 hrs)**
1. [Essence of linear algebra - 3blue1brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) - Watch first for visual intuition (~5 hrs)
2. [MIT OCW 18.06 - Gilbert Strang](https://www.youtube.com/playlist?list=PL221E2BBF13BECF6C) - Full computational course (~60-80 hrs)
3. [Linear Algebra Done Right - Sheldon Axler](https://www.youtube.com/playlist?list=PLGAnmvB9m7zOBVCZBUUmSinFV0wEir2Vw) - Proof-based, do the exercises (~100-150 hrs)

**Track B - Analysis (~200-350 hrs)**
1. [The Essence of Calculus - 3blue1brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) - Visual intuition first (~5 hrs)
2. [Real Analysis - Francis Su](https://www.youtube.com/playlist?list=PL0E754696F72137EC) - Watch alongside Tao (~50-70 hrs)
3. [Analysis I - Terence Tao](https://link.springer.com/book/10.1007/978-981-19-7261-4) - The main text, work all exercises (~200-300 hrs)
4. [Lean Companion to Tao's Analysis I](https://github.com/teorth/analysis) - Formalize proofs as you go (included in above)

**Track C - Learn Lean (~50-80 hrs, interleave with above)**
1. [Natural Number Game](https://adam.math.hhu.de/#/g/hhu-adam/NNG4) - Start here, day one (~10-15 hrs)
2. [The Mechanics of Proof - Heather Macbeth](https://hrmacbeth.github.io/math2001/) - Proofs + Lean together (~30-50 hrs)
3. [Theorem Proving in Lean 4](https://leanprover.github.io/theorem_proving_in_lean4/) - Reference, read as needed (~15-20 hrs)

### Phase 2: Core Undergraduate (~500-800 hrs)
These can run in parallel. Each is one semester equivalent.

1. [Abstract Algebra - Dummit & Foote](https://www.wiley.com/en-us/Abstract+Algebra,+3rd+Edition-p-9780471433347) - The encyclopedic text. Use [Socratica](https://www.youtube.com/playlist?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6) and [Artin lectures](https://www.youtube.com/playlist?list=PLelIK3uylPMGzHBuR3hLMHrYfMqWWsmx5) alongside (~200-350 hrs)
2. [Topology - James Munkres](https://www.pearson.com/en-us/subject-catalog/p/topology-classic-version/P200000006299/9780137848669) - Point-set then algebraic. Use [Tokieda lectures](https://www.youtube.com/playlist?list=PLTBqohhFNBE_09L0i-lf3fYXF5woAbrzJ) for intuition (~200-300 hrs)
3. [Probability - MIT Tsitsiklis](https://www.edx.org/course/probability-the-science-of-uncertainty-and-data) + [Feller Vol. 1](https://www.wiley.com/en-us/An+Introduction+to+Probability+Theory+and+Its+Applications,+Volume+1,+3rd+Edition-p-9780471257080) (~150-250 hrs)

### Phase 3: Intermediate (~400-600 hrs)
Requires Phase 1-2 as prerequisites.

1. [Analysis II - Terence Tao](https://link.springer.com/book/10.1007/978-981-19-7284-3) - Metric spaces, Lebesgue integral, Fourier (~200-300 hrs)
2. [Complex Analysis - Stein & Shakarchi](https://press.princeton.edu/books/hardcover/9780691113852/complex-analysis) or [Ahlfors](https://www.amazon.com/Complex-Analysis-Lars-Ahlfors/dp/0070006571) - Use [Borcherds lectures](https://www.youtube.com/playlist?list=PL8yHsr3EFj537_iYA5QrvwhvMlpkJ1yGN) alongside (~200-300 hrs)
3. [Elementary Number Theory - William Stein](https://wstein.org/ent/ent.pdf) + [Borcherds lectures](https://www.youtube.com/playlist?list=PL8yHsr3EFj53L8sMbzIhhXSAOpuZ1Fov8) (~100-150 hrs)

### Phase 4: Advanced (pick based on interest, ~200-400 hrs each)
Each is independent. Do any combination.

- **Functional Analysis**: [Conway](https://link.springer.com/book/10.1007/978-1-4757-4383-8) or [Lax](https://www.wiley.com/en-us/Functional+Analysis-p-9780471556046) + [ICTP lectures](https://www.youtube.com/playlist?list=PLp0hSY2uBeP-MGleT2B1vWjXEa_APRc2z). Requires: Analysis, Linear Algebra, Topology
- **Measure Theory & Stochastics**: [Billingsley](https://www.wiley.com/en-us/Probability+and+Measure,+Anniversary+Edition-p-9781118122372) → [Karlin & Taylor](https://shop.elsevier.com/books/a-first-course-in-stochastic-processes/karlin/978-0-08-057041-9) → [Oksendal](https://link.springer.com/book/10.1007/978-3-642-14394-6). Requires: Analysis, Probability
- **PDEs**: [Evans](https://bookstore.ams.org/gsm-19-r) + [MIT 18.152](https://ocw.mit.edu/courses/18-152-introduction-to-partial-differential-equations-fall-2011/). Requires: Analysis, Linear Algebra
- **Differential Geometry**: [Needham](https://www.vdgf.space/) → [Lee Manifolds](https://link.springer.com/book/10.1007/978-1-4419-7940-7). Requires: Analysis, Topology, Linear Algebra
- **Category Theory**: [Awodey](https://global.oup.com/academic/product/category-theory-9780199237180) → [Mac Lane](https://link.springer.com/book/10.1007/978-1-4757-4721-8) + [Borcherds lectures](https://www.youtube.com/playlist?list=PL8yHsr3EFj51F9XZ_Ka4bLnQoxTdMx0AL). Requires: Abstract Algebra
- **Numerical Methods**: [Trefethen & Bau](https://epubs.siam.org/doi/10.1137/1.9781611977165) + [Boyd Convex Optimization](https://stanford.edu/~boyd/cvxbook/). Requires: Linear Algebra, Analysis
- **Algebraic Number Theory**: [Milne](https://www.jmilne.org/math/CourseNotes/ANT.pdf) + [Borcherds](https://www.youtube.com/playlist?list=PL8yHsr3EFj52Qf7lc3HHvHRdIysxEcj1H). Requires: Abstract Algebra, Number Theory

### Phase 5: Lean Mastery (ongoing, alongside any phase)
- [Mathematics in Lean](https://leanprover-community.github.io/mathematics_in_lean/) - Work through as you cover each math topic (~80-120 hrs)
- [Formalising Mathematics 2024 - Buzzard](https://github.com/ImperialCollegeLondon/formalising-mathematics-2024) - After Phase 2 (~60-100 hrs)
- [The Hitchhiker's Guide to Logical Verification](https://lean-forward.github.io/hitchhikers-guide/2024/) - For the CS/logic side (~60-80 hrs)

### Phase 6: Applications (optional, any time after Phase 2)
- **Machine Learning**: [StatQuest](https://www.youtube.com/@statquest) (~20 hrs) → [ISL - Hastie & Tibshirani](https://www.youtube.com/watch?v=5N9V07EIfIg&list=PLOg0ngHtcqbPTlZzRHA2ocQZqB1D_qZ5V) (~60 hrs) → [fast.ai](https://course.fast.ai/) (~80 hrs)
- **Dynamical Systems**: [SFI Introduction](https://www.complexityexplorer.org/courses/105-introduction-to-dynamical-systems-and-chaos) (~40 hrs) → [Brunton Data-Driven](https://www.youtube.com/playlist?list=PLMrJAkhIeNNR6DzT17-MM1GHLkuYVjhyt) (~40 hrs)
- **Computational Math**: [MIT Computational Thinking (Julia)](https://computationalthinking.mit.edu/Spring21/) (~50 hrs)

---

## General

- [The two cultures of mathematics](https://www.dpmms.cam.ac.uk/~wtg10/2cultures.pdf) - Timothy Gowers' essay contrasting problem-solving and theory-building approaches in mathematics
- [All the Math You Missed - Thomas Garrity](https://www.cambridge.org/universitypress/subjects/mathematics/recreational-mathematics/all-math-you-missed-need-know-graduate-school-2nd-edition) - Concise overview of the essential mathematics needed for graduate school across all fields
- [Introduction to Computational Thinking - Alan Edelman, David P. Sanders and Charles E. Leiserson](https://computationalthinking.mit.edu/Spring21/) - MIT course teaching computational thinking through Julia with applications in data science and modeling
- [Matrix Methods in Data Analysis, Signal Processing, and Machine Learning](https://ocw.mit.edu/courses/mathematics/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/) - Gilbert Strang's MIT course on matrix decompositions, deep learning, and optimization

### Proof Writing
- [Book of Proof - Richard Hammack](https://richardhammack.github.io/BookOfProof/) - Free textbook teaching the methods of mathematical proof: sets, logic, direct proof, contrapositive, contradiction, and induction
- [How to Prove It - Daniel Velleman](https://www.cambridge.org/highereducation/books/how-to-prove-it/6D2965D625C6836CD4A785A2C843B3DA) - Structured introduction to proof techniques with emphasis on reading and writing mathematical arguments

### Applied Mathematics
- [Freya Holmer: Math for Game Devs](https://www.youtube.com/@acegikmo) - Outstanding visual video course covering vectors, matrices, splines, and quaternions with interactive game development examples
- [The Nature of Code (2nd ed., 2024) - Daniel Shiffman](https://natureofcode.com/) - Free online book teaching physics simulations, autonomous agents, and genetic algorithms through creative coding in p5.js
- [Math for Programming - Ronald T. Kneusel (No Starch Press, 2025)](https://nostarch.com/math-programming) - Practical book covering vectors, matrices, calculus for optimization, graph theory, and probability with direct applications to programming algorithms

## Linear Algebra
- [Essence of linear algebra - 3blue1brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) - Visual series building geometric intuition for vectors, linear transformations, eigenvalues, and determinants
- [MIT OCW 18.06: Linear Algebra - Gilbert Strang](https://www.youtube.com/playlist?list=PL221E2BBF13BECF6C) - The classic MIT linear algebra course covering column space, eigenvalues, SVD, and positive definite matrices
- [Linear Algebra - Steve Brunton](https://www.youtube.com/playlist?list=PLMrJAkhIeNNRjxJ_sMtJ02geqw_-vuB7O) - Engineering-focused linear algebra covering SVD, PCA, and applications to data-driven methods
- [Introduction to Applied Linear Algebra - Stephen Boyd](https://www.youtube.com/watch?v=oR6G1MUMveE&list=PLoROMvodv4rMz-WbFQtNUsUElIh2cPmN9) - Stanford course covering vectors, matrices, least squares, and applications in data fitting and control
- [Linear Algebra Done Right - Sheldon Axler](https://www.youtube.com/playlist?list=PLGAnmvB9m7zOBVCZBUUmSinFV0wEir2Vw) - Proof-based linear algebra emphasizing vector spaces and linear maps over determinant-heavy approaches

### Books
- [Linear Algebra Done Right - Sheldon Axler (4th ed., free)](https://linear.axler.net/LADR4e.pdf) - Free textbook emphasizing vector spaces and linear maps with a determinant-free approach to eigenvalues
- [Linear Algebra and Its Applications - Gilbert Strang](https://www.amazon.com/Linear-Algebra-Its-Applications-4th/dp/0030105676) - Classic applied linear algebra textbook emphasizing matrix factorizations and computational methods
- [Finite-Dimensional Vector Spaces - Paul Halmos](https://link.springer.com/book/10.1007/978-1-4612-6387-6) - Elegant abstract treatment of linear algebra through the lens of vector spaces and linear transformations

## Analysis
- [The Essence of Calculus - 3blue1brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) - Visual series building intuition for derivatives, integrals, and the fundamental theorem of calculus
- [Real Analysis: Lectures by Professor Francis Su](https://www.youtube.com/playlist?list=PL0E754696F72137EC) - Full course on sequences, continuity, compactness, and metric spaces with elegant proofs
- [Distributions theory - The Bright Side Of Mathematics](https://www.youtube.com/watch?v=gwVEEUg8PBY&list=PLBh2i93oe2qsbptdcvFlowCl51EX_a3nB) - Introduction to distributions (generalized functions), test functions, and the Dirac delta

### Books
- [Analysis I - Terence Tao](https://link.springer.com/book/10.1007/978-981-19-7261-4) - Rigorous introduction to real analysis covering the real numbers, sequences, series, and continuity
- [Analysis II - Terence Tao](https://link.springer.com/book/10.1007/978-981-19-7284-3) - Continuation covering metric spaces, differentiation, the Lebesgue integral, and Fourier analysis
- [Principles of Mathematical Analysis - Walter Rudin](https://www.amazon.com/Principles-Mathematical-Analysis-International-Mathematics/dp/007054235X) - The classic "Baby Rudin" covering sequences, continuity, differentiation, and Riemann-Stieltjes integration

## Complex Analysis and Fourier
- [Complex analysis - Richard E. Borcherds](https://www.youtube.com/playlist?list=PL8yHsr3EFj537_iYA5QrvwhvMlpkJ1yGN) - Fields medalist's lecture series covering analytic functions, contour integrals, and residue theory
- [Fourier Analysis - Steve Brunton](https://www.youtube.com/playlist?list=PLMrJAkhIeNNT_Xh3Oy0Y4LTj0Oxo8GqsC) - Covers Fourier series, Fourier transform, FFT, and applications to signal processing and PDEs
- [Complex Analysis - Steven Miller (Williams College)](https://www.youtube.com/playlist?list=PL71JUoXcec_mmLm9psjMKo1FYBXS9WHb7) - Full undergraduate complex analysis course with clear explanations
- [Crash Course in Complex Analysis - Steve Brunton](https://www.youtube.com/playlist?list=PLMrJAkhIeNNQBRslPb7I0yTnES981R8Cg) - Fast-paced overview of complex analysis for engineers and applied mathematicians
- [Visual Complex Functions: an Introduction with Phase Portraits - Elias Wegert](https://www.goodreads.com/book/show/12353218-visual-complex-functions?from_search=true&from_srp=true&qid=04GqQgkIBM&rank=1) - Introduces complex analysis through colorful phase portraits that visualize analytic functions

### Books
- [Complex Analysis - Lars Ahlfors](https://www.amazon.com/Complex-Analysis-Lars-Ahlfors/dp/0070006571) - Standard graduate text on complex analysis covering analytic functions, conformal mapping, and Riemann surfaces
- [Complex Analysis - Stein & Shakarchi](https://press.princeton.edu/books/hardcover/9780691113852/complex-analysis) - Princeton Lectures in Analysis volume covering Cauchy's theorem, residues, conformal mappings, and the Gamma function
- [Complex Analysis - Serge Lang](https://link.springer.com/book/10.1007/978-1-4757-3083-8) - Graduate-level textbook covering Cauchy's theorem, conformal mappings, and Riemann surfaces

## Probability and Statistics
- [Probability The Science of Uncertainty and Data - John Tsitsiklis](https://www.edx.org/course/probability-the-science-of-uncertainty-and-data) - MIT course covering probability axioms, random variables, Bayesian inference, and limit theorems
- [MIT RES.6-012: Introduction to Probability](https://www.youtube.com/playlist?list=PLUl4u3cNGP60hI9ATjSFgLZpbNJ7myAg6) - MIT probability course covering Bayes' rule, random variables, limit theorems, and Markov chains
- [Fundamentals of Statistics - Philippe Rigollet](https://www.edx.org/course/fundamentals-of-statistics) - MIT course on statistical estimation, hypothesis testing, and confidence intervals
- [StatQuest with Josh Starmer](https://www.youtube.com/@statquest) - Accessible visual explanations of statistics, machine learning, and data science concepts
- [Random Walks - Santa Fe Institute](https://www.complexityexplorer.org/courses/46-random-walks) - Course on random walk theory and its applications in physics, biology, and finance
- [The Logic of Science by E.T. Jaynes](https://www.youtube.com/watch?v=rfKS69cIwHc&list=PL9v9IXDsJkktefQzX39wC2YG07vw7DsQ_) - Video series on Bayesian probability as extended logic, based on Jaynes' foundational textbook

### Books
- [An Introduction to Probability Theory and Its Applications Vol. 1 - William Feller](https://www.wiley.com/en-us/An+Introduction+to+Probability+Theory+and+Its+Applications,+Volume+1,+3rd+Edition-p-9780471257080) - Classic text covering discrete probability, random walks, Markov chains, and generating functions
- [Statistical Inference - Casella & Berger](https://www.amazon.com/Statistical-Inference-George-Casella/dp/0534243126) - Comprehensive graduate text on probability theory, estimation, hypothesis testing, and decision theory

## Measure Theory and Stochastic Processes
- [Measure theory - The Bright Side Of Mathematics](https://www.youtube.com/playlist?list=PLBh2i93oe2qvMVqAzsX1Kuv6-4fjazZ8j) - Step-by-step introduction to sigma-algebras, measures, Lebesgue integration, and convergence theorems

### Books
- [Probability and Measure - Patrick Billingsley](https://www.wiley.com/en-us/Probability+and+Measure,+Anniversary+Edition-p-9781118122372) - Rigorous treatment of probability theory from a measure-theoretic foundation
- [A First Course in Stochastic Processes - Karlin & Taylor](https://shop.elsevier.com/books/a-first-course-in-stochastic-processes/karlin/978-0-08-057041-9) - Classic introduction to Markov chains, birth-death processes, renewal theory, and Brownian motion
- [Stochastic Differential Equations - Bernt Oksendal](https://link.springer.com/book/10.1007/978-3-642-14394-6) - Standard reference on Ito calculus, SDEs, diffusion processes, and applications to finance and filtering

## Abstract Algebra
- [Abstract Algebra - Socratica](https://www.youtube.com/playlist?list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6) - Short, clear videos introducing groups, rings, and fields with motivating examples
- [Abstract (Modern) Algebra - Bill Kinney](https://www.youtube.com/playlist?list=PLmU0FIlJY-Mn3Pt-r5zQ_-Ar8mAnBZTf2) - Full lecture course covering groups, rings, fields, and Galois theory at the undergraduate level
- [Rings and modules - Richard E. Borcherds](https://www.youtube.com/playlist?list=PL8yHsr3EFj52XDLrmvrFDgwcf6XOm2TEE) - Graduate-level lectures on ring theory, modules, and their applications in algebra
- [Abstract Algebra - Michael Artin](https://www.youtube.com/playlist?list=PLelIK3uylPMGzHBuR3hLMHrYfMqWWsmx5) - MIT lectures based on Artin's textbook covering groups, symmetry, linear algebra, and rings
- [Visual Group Theory - Matthew Macauley](https://www.youtube.com/playlist?list=PLwV-9DG53NDxU337smpTwm6sef4x-SCLv) - Group theory taught visually using Cayley diagrams, symmetry, and geometric intuition

### Books
- [Abstract Algebra - Dummit & Foote](https://www.wiley.com/en-us/Abstract+Algebra,+3rd+Edition-p-9780471433347) - Encyclopedic undergraduate/graduate algebra covering groups, rings, modules, fields, and Galois theory
- [Algebra - Serge Lang](https://www.wiley.com/en-au/Abstract+Algebra,+3rd+Edition-p-9780471433347) - Comprehensive graduate algebra textbook covering groups, rings, modules, fields, and Galois theory
- [Topics in Algebra - Herstein](https://www.amazon.com/Topics-Algebra-2nd-I-Herstein/dp/0471010901) - Classic undergraduate algebra text known for rigorous treatment of groups, rings, and field extensions

## Number Theory
- [Elementary Number Theory: Primes, Congruences, and Secrets - William Stein](https://wstein.org/ent/ent.pdf) - Free textbook covering primes, modular arithmetic, and cryptographic applications using Sage
- [Algebraic Number Theory](https://www.jmilne.org/math/CourseNotes/ANT.pdf) - Milne's graduate notes on number fields, rings of integers, Dedekind domains, and class field theory
- [Introduction to number theory - Richard E. Borcherds](https://www.youtube.com/playlist?list=PL8yHsr3EFj53L8sMbzIhhXSAOpuZ1Fov8) - Lecture series covering divisibility, primes, congruences, and quadratic reciprocity
- [Theory of numbers - Richard E. Borcherds](https://www.youtube.com/playlist?list=PL8yHsr3EFj52Qf7lc3HHvHRdIysxEcj1H) - Advanced number theory lectures covering algebraic integers, p-adic numbers, and zeta functions

## Functional Analysis
- [Functional Analysis - The Bright Side Of Mathematics](https://www.youtube.com/watch?v=yDdxFBcvSGw&list=PLBh2i93oe2qsGKDOsuVVw-OCAfprrnGfr) - Covers Banach spaces, Hilbert spaces, bounded operators, and the spectral theorem
- [ICTP: Functional Analysis Lectures](https://www.youtube.com/playlist?list=PLp0hSY2uBeP-MGleT2B1vWjXEa_APRc2z) - Comprehensive functional analysis lecture series from the International Centre for Theoretical Physics

### Books
- [A Course in Functional Analysis - John Conway](https://link.springer.com/book/10.1007/978-1-4757-4383-8) - Graduate text covering Hilbert spaces, Banach spaces, operator theory, and the spectral theorem
- [Functional Analysis - Peter Lax](https://www.wiley.com/en-us/Functional+Analysis-p-9780471556046) - Broad treatment of functional analysis connecting abstract theory to applications in PDEs and physics

## Category Theory
- [Categories for the idle mathematician - Richard E. Borcherds](https://www.youtube.com/playlist?list=PL8yHsr3EFj51F9XZ_Ka4bLnQoxTdMx0AL) - Accessible introduction to categories, functors, natural transformations, and adjunctions
- [Mathoma: Category Theory](https://www.youtube.com/channel/UCL_lVXCyzqBb2Xc8CrvPENg) - Video explanations of category theory concepts with concrete examples

### Books
- [Category Theory - Steve Awodey](https://global.oup.com/academic/product/category-theory-9780199237180) - Accessible introduction to categories, functors, natural transformations, limits, and adjoints
- [Categories for the Working Mathematician - Saunders Mac Lane](https://link.springer.com/book/10.1007/978-1-4757-4721-8) - The original and definitive graduate text on category theory by one of its founders

## Topology
- [Algebraic Topology: a beginner's course - N J Wildberger](https://www.youtube.com/playlist?list=PL41FDABC6AA085E78) - Introductory course covering simplicial complexes, homology groups, and the fundamental group
- [Topology and Geometry - Tadashi Tokieda](https://www.youtube.com/playlist?list=PLTBqohhFNBE_09L0i-lf3fYXF5woAbrzJ) - Engaging lectures on topology and geometry with beautiful physical demonstrations

### Point Set Topology
- [Point Set Topology Online Notes with Problems: MAT327 Course Notes](http://www.math.toronto.edu/ivan/mat327/?resources) - Course notes covering topological spaces, continuity, compactness, connectedness, and metric spaces

### Books
- [Topology - James Munkres](https://www.pearson.com/en-us/subject-catalog/p/topology-classic-version/P200000006299/9780137848669) - Standard undergraduate topology textbook covering topological spaces, connectedness, compactness, and fundamental group
- [Introduction to Topological Manifolds - John Lee](https://link.springer.com/book/10.1007/978-1-4419-7940-7) - Graduate text bridging point-set topology and differential geometry through the theory of manifolds

## Geometry
- [Visual Differential Geometry and Forms: A Mathematical Drama in Five Acts - Tristan Needham](https://www.vdgf.space/) - Geometric and visual approach to differential geometry, curvature, and differential forms

## Partial Differential Equations
- [MIT OCW 18.152: Introduction to Partial Differential Equations](https://ocw.mit.edu/courses/18-152-introduction-to-partial-differential-equations-fall-2011/) - MIT course on classification and solution methods for PDEs

### Books
- [Partial Differential Equations - Lawrence Evans](https://bookstore.ams.org/gsm-19-r) - Standard graduate PDE textbook covering transport, Laplace, heat, and wave equations plus Sobolev spaces

## Numerical Analysis and Optimization

### Books
- [Numerical Linear Algebra - Trefethen & Bau](https://epubs.siam.org/doi/10.1137/1.9781611977165) - Concise and elegant treatment of numerical algorithms for matrix computations, SVD, and eigenvalues
- [Convex Optimization - Boyd & Vandenberghe](https://stanford.edu/~boyd/cvxbook/) - Free textbook covering convex sets, convex functions, optimization problems, duality, and algorithms

## Dynamical Systems and Chaos
- [Nonlinear Dynamics: Mathematical and Computational Approaches - Santa Fe Institute](https://www.complexityexplorer.org/courses/115-nonlinear-dynamics-mathematical-and-computational-approaches) - Course on bifurcations, chaos, fractals, and numerical methods for nonlinear systems
- [Introduction to Dynamical Systems and Chaos - Santa Fe Institute](https://www.complexityexplorer.org/courses/105-introduction-to-dynamical-systems-and-chaos) - Introductory course covering iterated maps, strange attractors, and the onset of chaos
- [Data-Driven Dynamical Systems Overview - Steve Brunton](https://www.youtube.com/playlist?list=PLMrJAkhIeNNR6DzT17-MM1GHLkuYVjhyt) - Using machine learning and data analysis to discover dynamical systems models from measurements
- [Parallel Computing and Scientific Machine Learning - MIT 18.337J](https://github.com/mitmath/18337) - MIT course combining parallel computing, differential equations, and neural network approaches

### Books
- [Nonlinear Dynamics and Chaos - Steven Strogatz](https://www.routledge.com/Nonlinear-Dynamics-and-Chaos-With-Applications-to-Physics-Biology-Chemistry-and-Engineering/Strogatz/p/book/9780367026509) - Best introductory textbook on nonlinear systems, bifurcations, and chaos with applications across science and engineering

### Papers
- [More is different - Anderson](https://www.science.org/doi/10.1126/science.177.4047.393) - Classic paper arguing that complexity at each scale requires fundamentally new laws, not just more particles
- [What is complexity? Remarks on simplicity and complexity - Gell-Man](https://onlinelibrary.wiley.com/doi/abs/10.1002/cplx.6130010105) - Nobel laureate's essay defining different notions of complexity and their relationships
- [Numerical Evidence That the Motion of Pluto Is Chaotic - Gerald Jay Sussman, Jack Wisdom](https://web.mit.edu/wisdom/www/pluto-chaos.pdf) - Demonstrates through numerical integration that Pluto's orbit exhibits chaotic behavior over millions of years
- [Deterministic nonperiodic Flow - Edward Lorenz](https://journals.ametsoc.org/doi/pdf/10.1175/1520-0469%281963%29020%3C0130%3ADNF%3E2.0.CO%3B2) - The foundational 1963 paper discovering deterministic chaos in a simple atmospheric convection model
- [Intermittent transition to turbulence in dissipative dynamical systems - Yves Pomeau, Paul Manneville](https://link.springer.com/article/10.1007%2FBF01197757) - Describes the Type I intermittency route to chaos through tangent bifurcations near periodic orbits
- [Roads to turbulence in dissipative dynamical systems - Eckmann](https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.53.643) - Review of the main scenarios by which laminar flow transitions to turbulent chaos

## Machine Learning and Deep Learning
- [Neural Networks: Zero to Hero - Andrej Karpathy](https://karpathy.ai/zero-to-hero.html) - Video series building neural networks from scratch in pure Python, from backpropagation and micrograd through GPT-level language models
- [Introduction to Statistical Learning Series - Robert Tibshirani and Trevor Hastie](https://www.youtube.com/watch?v=5N9V07EIfIg&list=PLOg0ngHtcqbPTlZzRHA2ocQZqB1D_qZ5V) - Stanford course covering regression, classification, resampling, tree methods, and unsupervised learning
- [Practical Deep Learning for Coders](https://course.fast.ai/) - Fast.ai's top-down course teaching deep learning with PyTorch through practical applications first
- [Part 2: Deep Learning from the Foundations](https://course19.fast.ai/part2) - Fast.ai's advanced course rebuilding deep learning frameworks from scratch, covering backprop and optimizers
- [Geometric Deep Learning - Michael Bronstein](https://youtu.be/PtA0lg_e5nA?list=PLn2-dEmQeTfQ8YVuHBOvAhUlnIPYxkeu3) - Unifying framework for deep learning on graphs, meshes, groups, and manifolds

## Formalization and Exercises (Lean 4)

### Getting Started
- [Natural Number Game](https://adam.math.hhu.de/#/g/hhu-adam/NNG4) - Browser-based interactive game where you prove theorems about natural numbers from the Peano axioms, learning Lean tactics along the way
- [Lean Game Server](https://adam.math.hhu.de/) - Web platform hosting multiple interactive Lean 4 games including the Natural Number Game, Set Theory Game, and Logic Game
- [Theorem Proving in Lean 4](https://leanprover.github.io/theorem_proving_in_lean4/) - Official reference by Jeremy Avigad, Leonardo de Moura, and others covering dependent type theory, tactics, and interactive theorem proving
- [The Mechanics of Proof - Heather Macbeth](https://hrmacbeth.github.io/math2001/) - Introductory textbook for learning rigorous proof writing alongside Lean 4, aimed at early undergraduates with a gentler learning curve
- [Learning Lean 4 (Community Hub)](https://leanprover-community.github.io/learn.html) - Curated gateway page listing all major learning resources, books, and tutorials organized by topic and experience level

### Formalizing Mathematics
- [Mathematics in Lean (Lean 4 / Mathlib)](https://leanprover-community.github.io/mathematics_in_lean/) - Standard tutorial by Jeremy Avigad and Patrick Massot teaching mathematical formalization with Mathlib, featuring hundreds of exercises from number theory to measure theory
- [Formalising Mathematics 2024 - Kevin Buzzard (Imperial College, Lean 4)](https://github.com/ImperialCollegeLondon/formalising-mathematics-2024) - Full course on formalizing math in Lean 4 with Mathlib exercises and projects covering groups, topology, and analysis
- [Lean Companion to Tao's Analysis I - Terence Tao](https://github.com/teorth/analysis) - Official Lean 4 formalization of definitions, theorems, and exercises from Tao's Analysis I textbook where readers prove results by filling in `sorry` placeholders
- [The Hitchhiker's Guide to Logical Verification](https://lean-forward.github.io/hitchhikers-guide/2024/) - Graduate-level textbook on interactive theorem proving and logical verification in Lean 4 from Vrije Universiteit Amsterdam

### Reference
- [Mathlib4 Documentation](https://leanprover-community.github.io/mathlib4_docs/) - Auto-generated API documentation for Mathlib, Lean 4's comprehensive mathematical library covering algebra, analysis, topology, probability, and more
- [100 Theorems in Lean](https://leanprover-community.github.io/100.html) - Tracks Lean/Mathlib's progress on Freek Wiedijk's 100 theorems challenge, with links to each formalized proof
- [Functional Programming in Lean - David Thrane Christiansen](https://lean-lang.org/functional_programming_in_lean/) - Free book teaching functional programming concepts using Lean 4, useful for understanding the language foundations underlying theorem proving
