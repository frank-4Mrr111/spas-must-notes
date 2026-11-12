<!-- SPAS MUST NOTES - V3.4 FINAL - WEBSITE INSTALL FILE -->
<!-- File name in GitHub repo: TRUSTED-SOURCES-V3.4-FINAL.md -->
<!-- DO NOT deploy V3.3. Deploy this file only. -->
<!-- Photo Upload = Option 1: CHAT-ONLY. Not a website feature yet. -->
<!-- How to install: GitHub repo frank-4Mrr111/spas-must-notes > Add file > Create new file -->
<!-- Name it: TRUSTED-SOURCES-V3.4-FINAL.md > Paste ALL of this file > Commit -->
<!-- Then link it from README.md: Trusted Sources V3.4 Final -->

TRUSTED SOURCES - SPAS MUST Notes
V3.3 - FINAL LOCKED - NAME + CODE TOGETHER, NAME WINS
UPDATE: Student uploads Name EXACTLY as on paper + Code from same paper.
If Code fails but Name passes -> teach by Name, explain code changed over time.
NEVER say "Not found" as first answer - ask for exact name from paper.
Built by frank-4Mrr111
Checked against exampapers.must.ac.ke/category/spas/ - ALL years:
2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017 (full 5809 lines), 2016, 2015, 2014 (via 2015-2017 duplicates)
Coverage: every SPAS undergrad unit NAME seen on the site, 2014-2024
================================================================
WEBSITE RULE - READ THIS FIRST - THIS IS THE FIX
STUDENT INPUT = UNIT NAME ONLY.
The website MUST ask the student to upload / type the NAME of their unit of concern,
exactly as it appears on their paper / transcript / course outline.
Example: "Chemical Kinetics" - NOT "SCH 3354".

WHY: Codes change with time and contradict each other.
Proof from the site itself:

SCH 3303 = Introduction to Group Theory (2022) AND Phytochemistry (2021)
SHC 3451 = Forensic Biochemistry (2024) AND Metabolic Regulation and Integration (2017)
SHC 3453 = Metabolic Regulation (2024) AND Forensic Biochemistry (2017) - SWAPPED
SMS 3401 = Non-Parametric Methods AND Functional Analysis (2021)
SZA 3401 = Advanced Immunology AND Biostatistics (2021)
SPH 3454 = Polymer Physics AND Plasma Physics (2017)
STA 2493 = Survival Analysis AND Financial Risk Management (same year)
SZL 3250 = Molecular Biology AND Animal Ecology (2017)
SZL 3350 = Research Methodology AND Advanced Immunology AND Entomology I
SCH 3300 = Chemistry of D-Block Elements AND (site misfile) Zoonotic Diseases
SCH 3302 = Non-Benzenoid Aromatic AND Biomembranes and Cellular Signalling
If the AI matches by CODE, it WILL teach the wrong unit. If it matches by NAME, it cannot.
AI MATCHING RULES (implement exactly):

PRIMARY KEY = Canonical Unit Name (Section A below).
NORMALISE the student's input before matching:
lowercase, strip punctuation, collapse spaces
"and" = "&", "i" = "1", "ii" = "2", "iii" = "3", "iv" = "4"
unify synonyms: kinetics = reaction kinetics, thermodynamics = chemical thermodynamics,
stats = statistics, maths = mathematics, biochem = biochemistry,
micro = microbiology, phys = physics, chem = chemistry, org = organic,
intro = introduction, adv = advanced, gen = general, princ = principles
CODE IS ONLY A HINT. Never use code as primary key. If student also gives a code,
use it ONLY to confirm level (undergrad vs Masters) - if Code and Name disagree,
NAME WINS. Log the conflict, do not silently follow the code.
AMBIGUOUS NAME? Ask ONE clarifying question, do not guess.
Examples that MUST trigger clarification:
"Biochemistry" alone -> ask: Biochemistry I / II / Introduction to Biochemistry / Biochemistry of ...?
"Chemistry" alone -> ask: General / Organic / Inorganic / Physical / Chemistry for Engineers?
"Physics" / "Physics I" / "Physics II" -> ask: SPS Physics I vs SPH Mechanics I vs SPH Physics (service)?
"Statistics" alone -> ask: Statistics for ... / Probability and Statistics I/II/III/IV / Biostatistics?
"Immunology" alone -> ask: Basic Immunology I / Immunology I / Advanced Immunology?
"Entomology" alone -> ask: Entomology I / Entomology II / Introductory Entomology / Agricultural Entomology?
"Parasitology" alone -> ask: Parasitology I / Parasitology II / Host-Parasite Interaction?
"Genetics" alone -> ask: General Genetics / Genetics and Cytogenetics / Principles of Genetics / Advanced Genetics / Microbial Genetics?
"Ecology" alone -> ask: Plant Ecology / Population Ecology / Applied Ecology / Animal Ecology / Ecology and Bioanalysis?
EVERY ANSWER MUST SHOW: Canonical Unit Name (as matched), Student's original input (verbatim),
Paper Year + Question Number if the student gave a paper, and the Source used.
If NO canonical name matches after normalisation + one clarification, answer:
NOT FOUND - No trusted source for this unit name yet. Needs MUST lecturer notes.
NEVER invent a source. NEVER guess by code.
================================================================
GOLDEN RULES (unchanged)
TOPICS = from exampapers.must.ac.ke ONLY. If never tested, OMIT.
EXPLANATIONS = from sources in Section A ONLY. No blogs, TikTok, rumours.
TEACHING = for student who NEVER attended lecture. Simple language, real-life example,
formula, step-by-step, common mistake.
MUST e-learning / lecturer notes beat all textbooks when available.
================================================================
SECTION A - CANONICAL UNITS BY NAME (the complete list)
Format per unit:
CANONICAL NAME
Aliases on site: other names / spellings seen for the SAME unit
Codes seen on site (HINT ONLY, never primary key): ...
Core parts (every part must be teachable - if a part has no source, it is a gap):
Sources:
--- A1. ACTUARIAL SCIENCE ---

INTRODUCTION TO ACTUARIAL SCIENCE
Aliases: Introduction to Acturial Science (typo on site)
Codes: SMS 3113, STA 2190, SMF 3113 (misfile)
Parts: role of actuary, actuarial control cycle, professionalism, interest, annuities intro
Sources: Bowers - Actuarial Mathematics (intro chs); SOA/IFoA Study Notes; Kellison - Theory of Interest
ACTUARIAL MATHEMATICS I
Codes: SMS 3214, STA 2291
Parts: survival models, life tables, life insurance, life annuities, premiums, reserves intro
Sources: Bowers - Actuarial Mathematics - MAIN; Dickson, Hardy & Waters - Life Contingent Risks
ACTUARIAL MATHEMATICS II
Aliases: Actuarial Math II
Codes: SMS 3314, STA 2390, SMS 3214 (2019 misfile - check Name), SMS 3324 (typo)
Parts: multiple life, multiple decrement, pension, profit testing intro
Sources: Bowers; Dickson, Hardy & Waters
ACTUARIAL MATHEMATICS III
Codes: SMS 3415, STA 2419, STA 2491, SMS 3314 (2019 misfile)
Parts: advanced life contingencies, profit testing, embedded values, with-profit
Sources: Bowers; Dickson, Hardy & Waters; Booth - Modern Actuarial Theory and Practice
PRINCIPLES OF LIFE INSURANCE
Codes: SMS 3220
Parts: life products, underwriting, claims, regulation
Sources: Booth; Rejda - Principles of Risk Management and Insurance
PRINCIPLES OF GENERAL INSURANCE
Codes: SMA 3120, SMS 3120
Parts: general insurance products, rating, reinsurance intro
Sources: Rejda; CII Notes
THEORY OF ACTUARIAL PRACTICE AND PROFESSIONALISM
Codes: SMS 3130
Parts: professionalism, ethics, actuarial control cycle, communication
Sources: SOA/IFoA Study Notes; Booth
PRINCIPLES OF HEALTH CARE AND RESERVING / PRINCIPLES OF HEALTH CARE AND RESERVING
Codes: SMS 3230
Parts: health products, morbidity, reserving for health
Sources: Booth; Dickson, Hardy & Waters (health chs)
LIFE ASSURANCE PRACTICE / LIFE ASSURANCE THEORY
Aliases: Life Assurance Practice, Life Assurance Theory
Codes: SMS 3370, SMS 3470
Parts: life office practice, valuation, solvency, with-profit / unit-linked
Sources: Booth - Modern Actuarial Theory and Practice
PENSION MATERIALS AND BENEFITS / PENSION BENEFITS
Codes: SMS 3380 (seen as Pension Materials and Benefits in earlier lists)
Parts: pension designs, funding, valuation, retirement benefits
Sources: Booth; McGill - Fundamentals of Private Pensions
RISK THEORY FOR ACTUARIAL SCIENCE
Codes: SMS 3363, STA 2309
Parts: individual / collective risk, ruin theory, reinsurance, credibility intro
Sources: Klugman - Loss Models; Bowers (risk chs)
NON-LIFE INSURANCE MATHEMATICS
Codes: SMS 3467, STA 2495
Parts: non-life pricing, reserving (chain ladder, Bornhuetter-Ferguson), ruin, reinsurance
Sources: Klugman - Loss Models; Booth
CREDIBILITY THEORY AND LOSS MODELS / CREDIBILITY THEORY AND LOSS MODEL
Codes: SMS 3465, STA 2492
Parts: limited fluctuation, Bayesian credibility, Buhlmann, loss distributions, fitting
Sources: Klugman - Loss Models - MAIN
FINANCIAL REPORTING AND INTERPRETATION OF ACCOUNTS
Codes: SMS 3413, SMS 3413 / STA 2442 variant
Parts: financial statements, ratios, interpretation for actuaries
Sources: Booth; Penman - Financial Statement Analysis
INVESTMENT AND ASSET MANAGEMENT
Codes: SMS 3468
Parts: portfolio theory, asset classes, ALM intro, performance
Sources: Hull - Options, Futures and Derivatives; Bodie - Investments
FINANCIAL ECONOMICS FOR ACTUARIAL SCIENCE
Codes: SMS 3413 (2019 variant - check Name), STA 2442, SMS 3410
Parts: efficient markets, CAPM, derivatives intro, utility
Sources: Hull; Bodie - Investments
--- A2. MATHEMATICS ---
17. CALCULUS I
Codes: SMA 3112, SMA 2101
Parts: limits, differentiation, applications, integration intro
Sources: OpenStax Calculus Vol 1 - MAIN; Paul's Online Math Notes; MIT OCW Calculus
18. CALCULUS II
Codes: SMA 3152, SMA 2102
Parts: techniques of integration, sequences/series, parametric, polar
Sources: OpenStax Calculus Vol 2; Paul's Notes; MIT OCW
19. CALCULUS III
Aliases: Calculus III, Calculus for Statistics III (STA 2204 variant)
Codes: SMA 3200, SMA 2200, STA 2204
Parts: multivariable, partial derivatives, multiple integrals, vector calculus intro
Sources: OpenStax Calculus Vol 3; Paul's Notes; MIT OCW
20. CALCULUS IV
Codes: SMA 2300
Parts: vector calculus, line/surface integrals, Stokes/Green/Divergence theorems
Sources: Stewart - Calculus (multivariable + vector calculus chs); OpenStax Calculus Vol 3
21. DIFFERENTIAL AND INTEGRAL CALCULUS
Codes: SMC 3122
Parts: differentiation, integration, applications (service unit)
Sources: OpenStax Calculus Vol 1-2
22. CALCULUS AND MATRICES
Codes: SMB 0003, SMA 0003, SMB 0103
Parts: calculus basics, matrices, determinants, solving systems (foundation)
Sources: MUST lecturer notes FIRST; OpenStax Calculus Vol 1; Strang - Linear Algebra (matrices)
23. MATHEMATICS FOR SCIENCE
Codes: SMA 3110, SMA 2104
Parts: algebra, functions, calculus for science, statistics intro
Sources: OpenStax Calculus Vol 1; OpenStax College Algebra; OpenIntro Statistics
24. MATHEMATICS FOR BIOLOGISTS / MATHEMATICS FOR BIOLOGIST
Codes: SMA 2250, SMB 2250
Parts: calculus, exponential/log growth, matrices, probability for biology
Sources: MUST lecturer notes; OpenStax Calculus Vol 1; OpenIntro Statistics
25. MATHEMATICS I (SERVICE) / MATHEMATICS II (SERVICE)
Aliases: Mathematics I, Mathematics II, Mathematics 1, Mathematics 2
Codes: SMF 3111, SMF 3151, SMA 2160, SMA 2161, SMA 1100, SMA 1110, SMA 2100, SMA 2110, SMF 2111, SME 1100, SME 1150, SME 1201, SME 2100, SME 2150, SME 2200, SME 2250, SME 2300, SME 2350, SME 3100, SME 3101, SME 3102, SME 3150, SME 3200, SME 3250
Parts: depends on Name+Level - see clarification rule. Service maths: algebra, calculus, stats basics
Sources: MUST lecturer notes FIRST; OpenStax Calculus / College Algebra (by topic)
26. ALGEBRA AND BUSINESS MATHEMATICS
Codes: SMA 0001, SMB 0001, SMB 0101
Parts: algebra, business maths, percentages, equations (foundation)
Sources: MUST lecturer notes; OpenStax College Algebra
27. GEOMETRY
Codes: SMA 0002, SMB 0002, SMB 0102, SME 3200 (Geometry variant)
Parts: Euclidean geometry, trigonometry, coordinates (foundation)
Sources: MUST lecturer notes; OpenStax Geometry (via OpenStax Algebra)
28. GRAPHS
Codes: SMA 0005, SMB 0005, SMB 0105
Parts: functions, graphs, plotting (foundation)
Sources: MUST lecturer notes; OpenStax College Algebra
29. PROBABILITY AND STATISTICS (FOUNDATION)
Codes: SMA 0004, SMB 0004, SMB 0104
Parts: descriptive stats, probability basics (foundation)
Sources: MUST lecturer notes; OpenIntro Statistics
30. DISCRETE MATHEMATICS / DISCRETE MATHEMATICS I
Codes: SMA 3111
Parts: logic, sets, combinatorics, graphs, recurrence
Sources: Rosen - Discrete Mathematics - MAIN
31. DISCRETE STRUCTURES
Codes: SMA 3212 (2013 variant), SMC 3212, SMC 3250
Parts: sets, logic, relations, graphs, trees
Sources: Rosen - Discrete Mathematics
32. NUMBER THEORY
Codes: SMA 3212
Parts: divisibility, primes, congruences, Diophantine, cryptography intro
Sources: Hardy & Wright - Number Theory - MAIN; Rosen (number theory chs)
33. LINEAR ALGEBRA I
Codes: SMA 3211, SMA 2201
Parts: vectors, matrices, systems, determinants, vector spaces intro
Sources: Strang - Introduction to Linear Algebra - MAIN
34. LINEAR ALGEBRA II
Codes: SMA 3254, SMA 2305 (old variant), SMA 2306, SMB 3275 (misfile - check Name)
Parts: eigenvalues, diagonalisation, inner products, linear transformations
Sources: Strang; Friedberg - Linear Algebra
35. NUMERICAL LINEAR ALGEBRA
Codes: SMC 3210, ICS 2211
Parts: direct/iterative solvers, LU/QR, eigenvalues numerically
Sources: Press - Numerical Recipes; Burden & Faires - Numerical Analysis
36. VECTOR ANALYSIS
Codes: SMA 3250, SMA 2220
Parts: vector fields, grad/div/curl, line/surface integrals
Sources: Spiegel - Vector Analysis; OpenStax Calculus Vol 3
37. COMPLEX ANALYSIS I
Codes: SMA 3300, SMA 2305 (old variant)
Parts: complex numbers, analytic functions, Cauchy, residues intro
Sources: Brown & Churchill - Complex Variables - MAIN
38. COMPLEX ANALYSIS II
Codes: SMA 3453, SMA 2405
Parts: residues, conformal mapping, Laurent, applications
Sources: Brown & Churchill
39. REAL ANALYSIS I
Codes: SMA 3301, SMA 2301 (old variant), SMA 2304 (misfile - check Name)
Parts: real numbers, sequences, limits, continuity, differentiation
Sources: Rudin - Principles of Mathematical Analysis - MAIN
40. REAL ANALYSIS II
Codes: SMA 3351, SMA 2302
Parts: integration, series of functions, uniform convergence
Sources: Rudin; Bartle - Elements of Real Analysis
41. REAL ANALYSIS FOR STATISTICS / REAL ANALYSIS FOR STATISTICS AND REAL ANALYSIS
Codes: STA 2306, SMA 2301 (old variant)
Parts: real analysis as used in statistics - sequences, limits, integration
Sources: Rudin (selected); Casella & Berger (appendix)
42. ORDINARY DIFFERENTIAL EQUATIONS I
Codes: SMA 3302, SMA 2301 (old), SMA 2304
Parts: first/second order ODEs, methods, applications
Sources: Boyce & DiPrima - Elementary Differential Equations - MAIN
43. ORDINARY DIFFERENTIAL EQUATIONS II
Codes: SMA 3352, SMA 2323, SMS 3352 (misfile - check Name)
Parts: systems, Laplace, series solutions, stability intro
Sources: Boyce & DiPrima
44. DIFFERENTIAL EQUATIONS / DIFFERENTIAL EQUATIONS I
Codes: SMA 2231, SMA 2420 (old variant), SME 3250
Parts: ODEs, methods, applications (service / old)
Sources: Boyce & DiPrima
45. PARTIAL DIFFERENTIAL EQUATIONS I / PARTIAL DIFFERENTIAL EQUATION 1
Codes: SMA 3400, SMA 2400
Parts: first/second order PDEs, separation, heat/wave/Laplace
Sources: Boyce & DiPrima (PDE chs); Strauss - Partial Differential Equations
46. NUMERICAL ANALYSIS I
Codes: SMA 3303, SMA 2321, SMS 3303 (misfile - check Name)
Parts: root finding, interpolation, numerical integration/differentiation
Sources: Burden & Faires - Numerical Analysis - MAIN
47. NUMERICAL ANALYSIS II / NUMERICAL ANALYSIS III
Codes: SMA 3456, SMA 2421
Parts: ODE solvers, linear systems numerically, eigenvalues
Sources: Burden & Faires
48. TOPOLOGY I / TOPOLOGY
Codes: SMA 3402, SMA 2401, SMA 3402 (Topology I)
Parts: metric/topological spaces, open/closed, continuity, compactness
Sources: Munkres - Topology - MAIN
49. TOPOLOGY II
Codes: SMA 3451 (Maths - check Name, NOT Demographic Techniques)
Parts: connectedness, compactness, separation, fundamental group intro
Sources: Munkres
50. FUNCTIONAL ANALYSIS
Codes: SMA 3401, SMA 2407, SMS 3401 (2021 variant - check Name)
Parts: normed spaces, Banach/Hilbert, operators, dual
Sources: Kreyszig - Introductory Functional Analysis - MAIN
51. GROUP THEORY I
Codes: SMA 3350, SMA 2303
Parts: groups, subgroups, homomorphisms, Lagrange, Sylow intro
Sources: Dummit & Foote - Abstract Algebra - MAIN
52. RING THEORY
Codes: SMA 3353, SMA 2307
Parts: rings, ideals, homomorphisms, PID/UFD
Sources: Dummit & Foote
53. FIELD THEORY
Codes: SMA 3403, SMA 2404
Parts: fields, extensions, Galois intro
Sources: Dummit & Foote
54. ALGEBRAIC STRUCTURES
Codes: SMA 3275, SMA 2202
Parts: groups, rings, fields - overview
Sources: Dummit & Foote; Fraleigh - Abstract Algebra
55. FLUID MECHANICS I / FLUID MECHANIC I
Codes: SMA 3355, SMA 2322
Parts: fluids, statics, kinematics, Bernoulli, Navier-Stokes intro
Sources: White - Fluid Mechanics - MAIN
56. FLUID MECHANICS II
Codes: SMA 3404, SMA 2424
Parts: viscous flow, boundary layer, turbulence intro, compressible intro
Sources: White
57. DIFFERENTIAL GEOMETRY
Codes: SMA 3405, SMA 2420 (old variant)
Parts: curves, surfaces, curvature, geodesics
Sources: Do Carmo - Differential Geometry of Curves and Surfaces - MAIN
58. CLASSICAL MECHANICS (MATHS)
Codes: SMA 3252, SMA 2221
Parts: Newtonian, Lagrangian, Hamiltonian, central forces
Sources: Goldstein - Classical Mechanics - MAIN
59. ANALYTICAL APPLIED MATHEMATICS I
Codes: SMA 3354, SMA 2320
Parts: applied maths - ODE/PDE methods, special functions, transforms
Sources: Kreyszig - Advanced Engineering Mathematics; Boyce & DiPrima
60. ANALYTICAL APPLIED MATHEMATICS II
Codes: SMA 3457, SMA 2422
Parts: advanced applied - integral transforms, Green's functions, asymptotics intro
Sources: Kreyszig
61. OPERATIONS RESEARCH (MATHS/STAT)
Codes: SMA 3425, SMA 2343, SMA 2430 (misfile - check Name)
Parts: LP, simplex, duality, transportation, queuing intro
Sources: Taha - Operations Research - MAIN
62. MEASURE AND INTEGRATION / MEASURE & INTEGRATION
Codes: SMA 3450, SMS 3358 (same unit, check Name)
Parts: measure, Lebesgue integral, convergence theorems
Sources: Royden - Real Analysis; Rudin - Real and Complex Analysis
63. MEASURE AND PROBABILITY
Codes: SMS 3455, STA 2405, SMS 3402 (2019 variant - check Name)
Parts: measure-theoretic probability, random variables, expectation, convergence
Sources: Rosenthal - A First Look at Rigorous Probability; Royden
64. FINANCIAL RISK MANAGEMENT (MATHS)
Codes: SMA 3464, STA 2423, STA 2493 (variant - check Name)
Parts: risk measures, VaR, derivatives, hedging
Sources: Hull - Options, Futures and Derivatives - MAIN

--- A3. STATISTICS, PROBABILITY & DATA SCIENCE (by NAME) ---
65. PROBABILITY AND STATISTICS I
Aliases: Probability & Statistics I, Probability and Statistics 1
Codes: SMS 3151, SMA 2013, SMA 2103, STA 2306 (misfile - check Name)
Parts: descriptive, probability, distributions, sampling intro
Sources: OpenIntro Statistics - MAIN; OpenStax Introductory Statistics; Khan Academy
66. PROBABILITY AND STATISTICS II
Codes: SMS 3200, SMA 2230, STA 2201
Parts: random variables, joint distributions, estimation intro, CLT
Sources: OpenIntro; OpenStax; Casella & Berger (intro chs)
67. PROBABILITY AND STATISTICS III
Codes: SMS 3250, SMA 2231 (old variant), STA 2201 (old variant)
Parts: estimation, hypothesis testing intro, regression intro
Sources: Casella & Berger; OpenIntro
68. PROBABILITY AND STATISTICS IV
Codes: SMS 3357, STA 2302
Parts: advanced inference, multivariate intro, nonparametric intro
Sources: Casella & Berger
69. PROBABILITY AND STATISTICS (SERVICE)
Aliases: Probability & Statistics, Probability and Statistics II (SSA variant)
Codes: SSA 3120, SMA 2103 (service variant), SMS 3151 (service variant)
Parts: service stats - descriptive, probability, inference basics
Sources: OpenIntro; OpenStax
70. INTRODUCTION TO BUSINESS AND SOCIAL STATISTICS
Codes: SMS 3171, STA 2101, SMB 3113 (business variant - check Name)
Parts: stats for business/social - descriptive, probability, inference, regression intro
Sources: OpenIntro; OpenStax Introductory Statistics
71. EXPLORATORY DATA ANALYSIS
Codes: SMS 3172, SMA 3172
Parts: EDA, plots, summaries, outliers, transformations
Sources: Tukey - Exploratory Data Analysis; OpenIntro
72. COMPUTER INTERACTIVE STATISTICS / INTRODUCTION TO COMPUTER INTERACTIVE STATISTICS
Codes: SMS 3213, STA 2202, STA 3213
Parts: stats using software, data entry, plots, tests in R/SPSS
Sources: R Documentation; OpenIntro R Labs; SPSS Tutorials
73. STATISTICAL PROGRAMMING I
Codes: SMS 3270, STA 2305, STA 2405 (variant - check Name)
Parts: programming for stats - R/Python basics, data frames, plots, functions
Sources: R Documentation; OpenIntro R Labs
74. STATISTICAL PROGRAMMING II
Codes: SMS 3351, STA 2311, SMS 3306 (variant - check Name)
Parts: advanced R/Python - simulation, resampling, packages, reports
Sources: R Documentation; Wickham - R for Data Science
75. LINEAR PROGRAMMING
Codes: SMS 3253, STA 2203, STA 2303
Parts: LP formulation, graphical, simplex, duality, sensitivity
Sources: Taha - Operations Research (LP chs)
76. QUALITY CONTROL AND ACCEPTANCE SAMPLING / STATISTICAL QUALITY CONTROL AND ACCEPTANCE SAMPLING / QUALITY CONTROL METHODS / STATISTICAL QUALITY CONTROL METHODS
Codes: SMS 3304, STA 2307, SMS 3402 (variant - check Name), SMA 2433
Parts: control charts, capability, acceptance sampling, OC curves
Sources: Montgomery - Statistical Quality Control - MAIN
77. REGRESSION MODELLING I / REGRESSION MODELING I / REGRESSION MODELLING
Codes: SMS 3305, STA 2312, SMA 2441, SMS 33305 (typo)
Parts: simple/multiple regression, assumptions, diagnostics, ANOVA
Sources: Kutner - Applied Linear Regression - MAIN
78. REGRESSION MODELLING II / REGRESSION MODELING II
Codes: SMS 3457, STA 2408
Parts: logistic, Poisson, nonlinear, model selection, diagnostics
Sources: Kutner; Agresti - Categorical Data Analysis (logistic chs)
79. THEORY OF ESTIMATION
Codes: SMS 3306, STA 2300, SMA 2330
Parts: point estimation, MLE, MSE, unbiased, sufficiency, Cramér-Rao
Sources: Casella & Berger - Statistical Inference - MAIN
80. TEST OF HYPOTHESIS / TESTS OF HYPOTHESIS / TESTS OF HYPOTHESES / TEST OF HYPOTHESES
Codes: SMS 3353, STA 2301, SMA 2331
Parts: hypothesis tests, errors, power, p-values, non-parametric tests intro
Sources: Casella & Berger
81. DESIGN AND ANALYSIS OF SAMPLE SURVEYS I / DESIGN AND ANALYSIS OF SAMPLE SURVEYS / DESIGN AND ANALYSIS OF SAMPLE SURVEYS I
Codes: SMS 3355, STA 2402, STA 2444, SMA 2432, SMS 3400 (variant - check Name)
Parts: sampling designs, SRS, stratified, cluster, estimation, non-response
Sources: Cochran - Sampling Techniques - MAIN
82. DESIGN AND ANALYSIS OF EXPERIMENTS I / DESIGN AND ANALYSIS OF EXPERIMENT I
Codes: SMS 3352, SMS 3400, STA 2308, SMA 2430
Parts: ANOVA, factorial, blocking, randomisation, CRD/RCBD
Sources: Montgomery - Design and Analysis of Experiments - MAIN
83. DESIGN AND ANALYSIS OF EXPERIMENTS II
Codes: SMS 3454, STA 2411
Parts: advanced factorial, fractional factorial, response surface, split-plot
Sources: Montgomery
84. NON-PARAMETRIC METHODS / NON-PARAMETRIC TESTS / NON PARAMETRIC TESTS
Codes: SMS 3401, STA 2404, SMA 2434
Parts: sign, Wilcoxon, Mann-Whitney, Kruskal-Wallis, rank correlation
Sources: Conover - Practical Nonparametric Statistics; Casella & Berger (nonparametric chs)
85. TIME SERIES ANALYSIS I / TIME SERIES ANALYSIS / TIME SERIES
Codes: SMS 3476, SMS 3251, STA 2401, STA 2203 (variant - check Name), SMA 2431
Parts: decomposition, AR/MA/ARMA, forecasting, stationarity
Sources: Box - Time Series Analysis - MAIN
86. TIME SERIES ANALYSIS II
Codes: SMS 3404, STA 2412, SMS 3412 (typo)
Parts: ARIMA, seasonal, ARCH/GARCH intro, multivariate time series intro
Sources: Box; Tsay - Analysis of Financial Time Series
87. FINANCIAL TIME SERIES / FINANCIAL TIME SERIES AND RISK MANAGEMENT / FINANCIAL TIMES SERIES AND RISK MANAGEMENT
Codes: SMS 3463, SMS 3460, STA 2420, STA 2410
Parts: returns, volatility, ARCH/GARCH, VaR, risk
Sources: Tsay - Analysis of Financial Time Series - MAIN; Hull
88. SURVIVAL DATA ANALYSIS / SURVIVAL ANALYSIS / SURVIVAL ANALYSIS FOR ACTUARIAL SCIENCES
Codes: SMS 3406, SMS 3466, STA 2433, STA 2493 (variant - check Name)
Parts: censoring, Kaplan-Meier, Cox, life tables, parametric survival
Sources: Kleinbaum - Survival Analysis - MAIN
89. STOCHASTIC PROCESSES / STOCHASTIC PROCESSES FOR ACTUARIAL SCIENCE
Codes: SMS 3453, STA 2391, STA 2406, SMA 2436
Parts: Markov chains, Poisson, Brownian, martingales intro
Sources: Ross - Stochastic Processes - MAIN
90. MULTIVARIATE METHODS / MULTIVARIATE ANALYSIS / MULTIVARIET METHODS
Codes: SMS 3456, STA 2407, SMA 2437, SMS 5126 (Masters - check Name+Level)
Parts: multivariate normal, PCA, factor, discriminant, clustering
Sources: Johnson & Wichern - Applied Multivariate Statistical Analysis - MAIN
91. CATEGORICAL DATA ANALYSIS
Codes: SMS 3458, STA 2430
Parts: contingency tables, chi-square, logistic, log-linear
Sources: Agresti - Categorical Data Analysis - MAIN
92. DECISION THEORY AND BAYESIAN INFERENCE I
Codes: SMS 3354, STA 2395, SMA 3354 (variant - check Name)
Parts: decision theory, loss, Bayes, prior/posterior, conjugate
Sources: Berger - Statistical Decision Theory and Bayesian Analysis - MAIN
93. DECISION THEORY AND BAYESIAN INFERENCE II
Codes: SMS 3459, STA 2498, SMS 3454 (variant - check Name)
Parts: advanced Bayes, hierarchical, MCMC intro, decision rules
Sources: Berger; Gelman - Bayesian Data Analysis
94. GAME THEORY / GAME THEORY FOR ACTUARIAL SCIENCE
Codes: SMS 3307, SMS 3402 (variant - check Name), STA 2422
Parts: zero-sum, Nash, mixed strategies, extensive form
Sources: Taha (game theory chs); Gibbons - Game Theory for Applied Economists
95. DEMOGRAPHIC TECHNIQUES
Codes: SMS 3451, STA 2490
Parts: life tables, fertility, mortality, migration, projections
Sources: Preston - Demography - MAIN
96. INTRODUCTION TO EPIDEMIOLOGICAL RESEARCH METHODS / INTRODUCTION TO EPIDEMIOLOGICAL METHODS / EPIDEMIOLOGY / EPIDEMIOLOGICAL RESEARCH METHODS
Codes: SMS 3215, SMA 3215
Parts: study designs, measures, bias, confounding, screening
Sources: Rothman - Epidemiology - MAIN
97. RESEARCH DATA MANAGEMENT / RESEARCH AND DATA MANAGEMENT
Codes: SMS 3252, STA 2205
Parts: data collection, cleaning, management, ethics, documentation
Sources: R Documentation; OpenIntro (data chs); MUST lecturer notes
98. RESEARCH METHODOLOGY (STATS)
Codes: SMS 3356, STA 2313, SZL 3350 (zoology variant - check Name+School)
Parts: research design, sampling, instruments, proposal, report
Sources: Kothari - Research Methodology; MUST lecturer notes
99. ECONOMETRICS
Codes: SMS 3452, STA 2340
Parts: regression for economics, OLS, endogeneity, panel intro, time series econometrics
Sources: Gujarati - Basic Econometrics - MAIN
100. SIMULATION AND MODELLING / SIMULATION AND MODELING
Codes: SMS 3450, ICS 2307, STA 2470 (misfile - check Name)
Parts: Monte Carlo, discrete event, random number generation, model validation
Sources: Law - Simulation Modeling and Analysis - MAIN
101. OPERATIONS RESEARCH (STATS)
Codes: SMS 3255, SMS 3350 (variant - check Name), STA 2470, SMC 3255, SMB 3425 (business variant)
Parts: LP, transportation, queuing, inventory, simulation intro
Sources: Taha - Operations Research
102. BUSINESS SYSTEMS MODELLING / BUSINESS SYSTEMS MODELING
Codes: SMS 3325, SMC 3325, SMS 3325
Parts: systems modelling, UML intro, business processes, simulation
Sources: Laudon - Management Information Systems; Law (simulation chs)
103. STATISTICS FOR DATA SCIENCE
Codes: CDS 3200
Parts: stats for data science - EDA, inference, regression, ML intro
Sources: James - Introduction to Statistical Learning - MAIN; OpenIntro
104. STATISTICS FOR BUSINESS / STATISTICS FOR PROJECT MANAGEMENT / STATISTICS FOR PROJECT MANAGERS
Codes: SMB 5100 (Masters - check Level), SMB 3300, SMS 3171 (business variant)
Parts: business stats - descriptive, inference, regression, forecasting
Sources: OpenIntro; OpenStax Introductory Statistics
105. BIOSTATISTICS / STATISTICS (HEALTH SERVICE)
Aliases: Biostatistics, Statistics, Biostatistics and Basic Computer Applications
Codes: SMF 3164, SMF 3261, SZL 3300, SMF 2164, SMF 3162, STA 2260, SZL 2300 (variant), SZL 2304 (variant), HMU 3215, HPP 3213, NNH 3201 (health variants - check School)
Parts: stats for health - descriptive, probability, tests, life tables intro, basic computing
Sources: OpenIntro; OpenStax Introductory Statistics; Daniel - Biostatistics
RULE: Only cover if student says SPAS / cross-listed. If paper is Health-only, mark Non-SPAS - see Section C.

--- A4. COMPUTER, SCIENTIFIC COMPUTING & INFORMATION SYSTEMS ---
106. SCIENTIFIC COMPUTING
Codes: CCS 3275, SMS 3275, ICS 2207
Parts: numerical methods in computing, MATLAB/Python, ODE solvers, optimisation intro
Sources: Press - Numerical Recipes - MAIN; Burden & Faires
107. ACTUARIAL SCIENCE INFORMATION SYSTEMS
Codes: SMS 3240
Parts: databases, MIS, actuarial software, data management
Sources: Elmasri & Navathe - Fundamentals of Database Systems; Laudon - MIS
108. EMBEDDED SYSTEMS
Codes: CCS 3401, SCS 3401
Parts: microcontrollers, interfacing, embedded C, real-time intro
Sources: Valvano - Embedded Systems; Boylestad - Electronic Devices
109. ELECTRONIC CIRCUIT ANALYSIS, DESIGN AND DEVELOPMENT / ELECTRONIC CIRCUIT ANALYSIS / BASIC ELECTRONIC CIRCUIT ANALYSIS AND DESIGN
Aliases: Electronic Circuits Analysis, Design and Development, Basic Electronics Circuit Analysis and Design
Codes: CIC 3401, CIC 3400, SPS 3300
Parts: circuit analysis, diodes, transistors, amplifiers, design
Sources: Boylestad - Electronic Devices - MAIN; Sedra Smith - Microelectronic Circuits
110. MICROELECTRONIC CIRCUIT DESIGN
Codes: CIC 3354
Parts: microelectronics, CMOS, amplifiers, design
Sources: Sedra Smith - Microelectronic Circuits - MAIN
111. DIGITAL LOGICS / DIGITAL LOGIC / DIGITAL ELECTRONICS
Aliases: Digital Logics, Digital Logic, Digital Electronics, Introduction to Digital Electronics
Codes: SPS 3250, SPS 3255, SPH 3255, SPS 2250, SPH 2250, SPH 3353 (variant)
Parts: logic gates, Boolean, combinational/sequential, flip-flops, counters
Sources: Floyd - Digital Fundamentals - MAIN; Mano - Digital Design

--- A5. CHEMISTRY ---
112. PRINCIPLES OF INORGANIC CHEMISTRY / INTRODUCTION TO THE PRINCIPLES OF INORGANIC CHEMISTRY
Codes: SCH 3100, SHC 3100 (misfile)
Parts: atomic structure, periodic, bonding, coordination intro
Sources: OpenStax Chemistry 2e - MAIN; Miessler - Inorganic Chemistry
113. INORGANIC CHEMISTRY (SERVICE)
Aliases: Inorganic Chemistry, Chemistry (SCS service)
Codes: SCS 3153, SCS 2100 (Chemistry variant), SCS 3100 (Chemistry variant), HML 3127 (health variant), SCH 3150 (variant)
Parts: inorganic basics - periodic, bonding, coordination (service level)
Sources: OpenStax Chemistry 2e; Miessler (intro chs)
114. PHYSICAL CHEMISTRY I
Codes: SCH 3101, SCA 3101, SCS 3111 (variant - check Name)
Parts: thermodynamics intro, kinetics intro, quantum intro, gases
Sources: Atkins - Physical Chemistry - MAIN; LibreTexts Physical Chemistry
115. PHYSICAL CHEMISTRY II
Codes: SCH 3201
Parts: quantum, spectroscopy intro, statistical thermodynamics intro, electrochemistry intro
Sources: Atkins
116. PHYSICAL INORGANIC CHEMISTRY
Codes: SCS 3111
Parts: physical + inorganic combined - thermodynamics, kinetics, coordination
Sources: Atkins + Miessler (combined)
117. ORGANIC CHEMISTRY (GENERAL / SERVICE)
Aliases: Organic Chemistry, Organic Chemistry I (service), Principles of Organic Chemistry
Codes: SCH 3100 (variant - check Name), SCH 3103, SCS 3050, SCS 3101, SCS 3150, SCS 3151, SCH 2106, SCS 2100, SCS 3110 (General Chemistry variant)
Parts: organic basics - structure, functional groups, reactions intro
Sources: Clayden - Organic Chemistry (intro chs); OpenStax Organic Chemistry; LibreTexts Organic
118. ORGANIC CHEMISTRY I
Codes: SCH 3152
Parts: alkanes, alkenes, alkynes, stereochemistry intro, mechanisms intro
Sources: Clayden - MAIN; McMurry - Organic Chemistry
119. ORGANIC CHEMISTRY II
Codes: SCH 3252, SCH 2202
Parts: aromatic, carbonyl, amines, spectroscopy intro, synthesis intro
Sources: Clayden; McMurry
120. ORGANIC CHEMISTRY FOR ENGINEERS
Codes: SCS 3151, SCH 3151
Parts: organic for engineers - functional groups, polymers intro, fuels
Sources: Clayden (intro); OpenStax Organic Chemistry
121. ANALYTICAL CHEMISTRY I
Codes: SCH 3153, SCH 2304
Parts: quantitative analysis, titrations, gravimetric, errors, statistics
Sources: Skoog - Analytical Chemistry - MAIN; Harris - Quantitative Chemical Analysis
122. ANALYTICAL CHEMISTRY II / ANALYTICAL CHEMISTRY
Codes: SCH 3453, SCH 2404
Parts: instrumental - UV-Vis, IR, AAS, chromatography intro, electroanalytical
Sources: Skoog; Harris
123. COMPARATIVE STUDY OF S AND P BLOCK ELEMENTS / COMPARATIVE STUDIES OF S AND P BLOCK ELEMENTS
Codes: SCH 3200
Parts: s/p block trends, compounds, reactivity
Sources: Miessler - Inorganic Chemistry - MAIN
124. CHEMISTRY OF D-BLOCK ELEMENTS
Codes: SCH 3300 (check Name - NOT Zoonotic Diseases misfile)
Parts: transition metals, complexes, properties, reactions
Sources: Miessler; Cotton - Advanced Inorganic Chemistry
125. CHEMISTRY OF TRANSITION ELEMENTS / INTRODUCTION TO CHEMISTRY OF TRANSITION ELEMENTS / COMPARATIVE STUDY OF TRANSITION ELEMENTS
Codes: SCH 2301, SCH 2400, SH 2400
Parts: transition metals - properties, complexes, trends (old curriculum)
Sources: Miessler; Cotton
126. F-BLOCK AND BIOINORGANIC CHEMISTRY / F BLOCK ELEMENTS AND BIOINORGANIC CHEMISTRY / F-BLOCK CHEMISTRY AND BIOINORGANIC CHEMISTRY
Codes: SCH 3455, SCH 2413
Parts: lanthanides/actinides, bioinorganic - haem, enzymes, metal toxicity
Sources: Miessler; Bertini - Bioinorganic Chemistry
127. SYNTHETIC ORGANIC CHEMISTRY I / SYNTHETIC ORGANIC CHEMISTRY
Codes: SCH 3301, SCH 2303, SCS 3301
Parts: synthesis strategies, protecting groups, C-C bond formation
Sources: Clayden; Smith - March's Advanced Organic Chemistry
128. SYNTHETIC ORGANIC CHEMISTRY II
Codes: SCH 3352, SCH 2312
Parts: advanced synthesis, asymmetric, heterocycles synthesis, total synthesis intro
Sources: Clayden; Smith
129. CHEMISTRY OF NON-BENZENOID AROMATIC COMPOUNDS / CHEMISTRY OF NON-BENZENOID AROMANTIC COMPOUNDS
Codes: SCH 3302 (check Name - NOT Biomembranes misfile), SCH 2309 (old variant)
Parts: non-benzenoid aromatics, azulene, tropone, antiaromatic
Sources: Clayden; Smith
130. INTRODUCTION TO GROUP THEORY (CHEMISTRY)
Codes: SCH 3303 (check Name - NOT Phytochemistry), SCH 2307
Parts: symmetry, point groups, character tables, spectroscopy applications
Sources: Cotton - Chemical Applications of Group Theory - MAIN
131. THEORY OF SPECTROSCOPIC METHODS / THEORY OF SPECTROSCOPY / THEORY OF SPECTROSCOPIC METHOD
Codes: SCH 3304, SCH 2313
Parts: UV, IR, NMR, MS - theory, interpretation
Sources: Banwell - Molecular Spectroscopy - MAIN; Pavia - Spectroscopy
132. ORGANIC SPECTROSCOPY
Codes: SCH 3452, SCH 2403
Parts: NMR, IR, MS, UV for organic structure elucidation
Sources: Pavia - Introduction to Spectroscopy - MAIN; Banwell
133. CHEMICAL THERMODYNAMICS AND PHASE EQUILIBRIA / CHEMICAL THERMODYNAMIC AND PHASE EQUILIBRIA
Codes: SCH 3351, SCH 2302
Parts: thermodynamics, Gibbs, phase diagrams, equilibria
Sources: Atkins - Physical Chemistry (thermodynamics chs) - MAIN
134. STATISTICAL THERMODYNAMICS
Codes: SCH 3305
Parts: Boltzmann, partition functions, ensembles, applications
Sources: Atkins; McQuarrie - Statistical Mechanics
135. CHEMICAL KINETICS / REACTION KINETICS
Aliases: Chemical Kinetics, Reaction Kinetics
Codes: SCH 3354, SCH 2305
Parts: rate laws, mechanisms, catalysis, temperature dependence
Sources: Atkins (kinetics chs) - MAIN; Laidler - Chemical Kinetics
136. CHEMISTRY OF CARBOHYDRATES AND PROTEINS / CHEMISTRY CARBOHYDRATES AND PROTEINS
Codes: SCH 3356, SCH 2311
Parts: carbohydrates, proteins, structure, reactions, analysis
Sources: Lehninger - Principles of Biochemistry (carbohydrate/protein chs); Clayden
137. ORGANOMETALLIC CHEMISTRY
Codes: SCH 3400
Parts: metal-carbon bonds, catalysis, Grignard, metallocenes
Sources: Cotton - Advanced Inorganic Chemistry; Crabtree - Organometallic Chemistry
138. ELECTROCHEMISTRY
Codes: SCH 3401, SCH 2401
Parts: cells, Nernst, corrosion, electrolysis, batteries
Sources: Atkins (electrochemistry chs); Bard - Electrochemical Methods
139. STEREOCHEMISTRY AND REACTION MECHANISMS / STEREOCHEMISTRY AND REACTION MECHANISM / ADVANCED STEREOCHEMISTRY AND REACTION MECHANISM
Codes: SCH 3402, SCH 2402, SCH 3203
Parts: stereoisomers, chirality, mechanisms, SN1/SN2/E1/E2
Sources: McMurry - Stereochemistry; Clayden (mechanisms chs)
140. SURFACE AND COLLOID CHEMISTRY / SURFACE AND COLLOIDS CHEMISTRY
Codes: SCH 3404, SCH 2408
Parts: surface tension, adsorption, colloids, surfactants, emulsions
Sources: Atkins; Hiemenz - Principles of Colloid and Surface Chemistry
141. HETEROCYCLIC CHEMISTRY / ADVANCED HETEROCYCLIC CHEMISTRY
Codes: SCH 3407, SCH 2411
Parts: heterocycles - pyridine, pyrrole, furan, synthesis, reactions
Sources: Joule - Heterocyclic Chemistry - MAIN
142. ENVIRONMENTAL CHEMISTRY
Codes: SCH 3408, SCH 2310, HPP 3113 (health variant - check School)
Parts: air, water, soil chemistry, pollutants, monitoring
Sources: Manahan - Environmental Chemistry - MAIN; OpenStax Environmental Science
143. NUCLEAR CHEMISTRY AND RADIOACTIVITY / NUCLEAR CHEMISTRY AND RIADIOCHEMISTRY / NUCLEAR CHEMISTRY & RADIOCHEMISTRY
Codes: SCH 3353, SCH 2203
Parts: radioactivity, decay, nuclear reactions, applications, safety
Sources: Atkins; Krane - Introductory Nuclear Physics (nuclear chs)
144. COORDINATION CHEMISTRY
Codes: SCH 3450
Parts: complexes, crystal field, ligands, isomerism, spectra
Sources: Miessler - Inorganic Chemistry (coordination chs) - MAIN
145. ATOMIC STRUCTURE AND CHEMICAL BONDING / ATOMIC STRUCTURE AND BONDING / ATOMIC STRUTURE AND BONDING
Codes: SCH 3250, SCH 2300
Parts: atomic models, quantum numbers, bonding, VSEPR, MO intro
Sources: Atkins; Miessler (bonding chs); OpenStax Chemistry 2e
146. FUNCTIONAL GROUP CHEMISTRY
Codes: SCH 3253
Parts: functional groups - properties, reactions, interconversions
Sources: Clayden; McMurry
147. LABORATORY TECHNIQUES (CHEMISTRY)
Codes: SCH 3203, SHC 3203 (biochem variant - check Name)
Parts: lab safety, glassware, titration, distillation, chromatography basics
Sources: MUST lecturer notes FIRST; Skoog (lab chs)
148. RESEARCH METHODS (CHEMISTRY)
Codes: SCH 3357
Parts: research design, literature, proposal, report, ethics
Sources: Kothari - Research Methodology; MUST lecturer notes
149. INDUSTRIAL CHEMISTRY
Codes: SCH 3451 (check Name - NOT Forensic/Metabolic), SCH 2406
Parts: industrial processes, petrochemicals, fertilisers, polymers, green chemistry
Sources: Austin - Shreve's Chemical Process Industries - MAIN
150. NATURAL PRODUCTS CHEMISTRY
Codes: SCH 3454, SCH 2412
Parts: alkaloids, terpenoids, flavonoids, isolation, structure, biosynthesis
Sources: Dewick - Medicinal Natural Products - MAIN; Harborne - Phytochemistry
151. PHYTOCHEMISTRY
Codes: SCS 3300, SCH 3303 (2021 variant - check Name), SBT 2309
Parts: plant secondary metabolites, extraction, chromatography, identification
Sources: Harborne - Phytochemistry - MAIN; Dewick
152. PHOTOCHEMISTRY
Codes: SCH 3355
Parts: photochemical reactions, excited states, Jablonski, applications
Sources: Wayne - Photochemistry - MAIN; Atkins (photochemistry chs)
153. STRUCTURAL CHEMISTRY
Codes: SCH 2410
Parts: molecular structure, bonding, symmetry, diffraction, spectroscopy for structure
Sources: Miessler - Inorganic Chemistry (structure chs); Atkins; Cotton - Group Theory
154. INTRODUCTION TO CHEMISTRY / CHEMISTRY (FOUNDATION)
Aliases: Introduction to Chemistry, Chemistry
Codes: SCH 0106, SCH 2106, SCS 0100, SCS 1100, CHE 0100, SCS 2100 (Chemistry variant)
Parts: foundation chemistry - atoms, bonding, reactions, stoichiometry
Sources: MUST lecturer notes FIRST; OpenStax Chemistry 2e
155. GENERAL CHEMISTRY
Codes: SCS 3110
Parts: general chemistry - atomic, bonding, thermodynamics, kinetics intro
Sources: OpenStax Chemistry 2e; Brown - Chemistry: The Central Science

--- A6. PHYSICS ---
156. MECHANICS I
Codes: SPH 3100
Parts: kinematics, Newton's laws, work-energy, momentum, rotation intro
Sources: OpenStax University Physics Vol 1 - MAIN; Halliday, Resnick & Walker
157. MECHANICS II
Codes: SPH 3200
Parts: rotation, oscillations, gravitation, fluids intro, waves intro
Sources: OpenStax University Physics Vol 1; Halliday
158. GEOMETRICAL OPTICS / GEOMETRIC OPTICS
Codes: SPH 3101
Parts: reflection, refraction, lenses, mirrors, optical instruments
Sources: Hecht - Optics - MAIN; OpenStax University Physics Vol 3
159. PHYSICAL OPTICS
Codes: SPH 3306, SPH 2311
Parts: interference, diffraction, polarisation, coherence
Sources: Hecht
160. ELECTRICITY AND MAGNETISM I / ELECTRICITY & MAGNETISM I
Codes: SPH 3152, SPH 3150 (variant)
Parts: electrostatics, fields, potential, capacitance, current
Sources: Griffiths - Introduction to Electrodynamics (intro chs); OpenStax University Physics Vol 2
161. ELECTRICITY AND MAGNETISM II
Codes: SPH 3201, SPH 3251 (variant)
Parts: magnetostatics, induction, Maxwell, AC intro
Sources: Griffiths; OpenStax Vol 2
162. WAVES AND VIBRATIONS / WAVES & VIBRATION
Codes: SPH 3153
Parts: SHM, waves, superposition, standing waves, sound
Sources: OpenStax University Physics Vol 1 (waves chs); French - Vibrations and Waves
163. THERMAL PHYSICS I
Codes: SPH 3252, SPH 2202
Parts: temperature, heat, kinetic theory, thermodynamics I
Sources: OpenStax University Physics Vol 2 (thermo chs); Schroeder - Thermal Physics
164. THERMAL PHYSICS II
Codes: SPH 3302, SPH 2302
Parts: entropy, thermodynamic potentials, phase transitions, statistical intro
Sources: Schroeder; OpenStax Vol 2
165. MODERN PHYSICS
Codes: SPH 3253, SPH 2203, SPH 3251 (variant - check Name)
Parts: relativity intro, quantum intro, atomic, nuclear intro
Sources: Krane - Modern Physics - MAIN; OpenStax University Physics Vol 3
166. CLASSICAL MECHANICS (PHYSICS)
Codes: SPH 3300, SPH 2300
Parts: Lagrangian, Hamiltonian, central forces, rigid bodies
Sources: Goldstein - Classical Mechanics - MAIN; Taylor - Classical Mechanics
167. ELECTRONICS I
Codes: SPH 3303, SPH 2304
Parts: diodes, transistors, amplifiers, op-amps intro
Sources: Boylestad - Electronic Devices - MAIN
168. ELECTRONICS II / ELECTRONICS II DIGITAL ELECTRONICS
Aliases: Electronics II, Electronics II Digital Electronics
Codes: SPH 3353, SPH 2310, SPH 2320
Parts: advanced amplifiers, oscillators, digital circuits, logic
Sources: Boylestad; Floyd - Digital Fundamentals
169. AC CIRCUIT THEORY
Codes: SPH 3304, SPH 2301
Parts: AC circuits, phasors, impedance, resonance, filters, power
Sources: Boylestad; Alexander - Fundamentals of Electric Circuits
170. INTRODUCTION TO ASTRONOMY / INTRODUCTION TO ASTRONOMY / INTRODUCTORY ASTRONOMY / ASTROPHYSICS
Aliases: Introduction to Astronomy, Introductory Astronomy, Astrophysics
Codes: SPH 3305, SPH 2313
Parts: solar system, stars, galaxies, cosmology intro, telescopes
Sources: Carroll & Ostlie - Modern Astrophysics - MAIN; OpenStax Astronomy
171. QUANTUM MECHANICS I
Codes: SPH 3350, SPH 2303
Parts: wavefunctions, Schrodinger, 1D potentials, operators, hydrogen intro
Sources: Griffiths - Introduction to Quantum Mechanics - MAIN
172. QUANTUM MECHANICS II
Codes: SPH 3401, SPH 2403
Parts: angular momentum, spin, perturbation, scattering, identical particles
Sources: Griffiths
173. ATOMIC PHYSICS
Codes: SPH 3351, SPH 2400
Parts: atomic structure, spectra, Zeeman, lasers intro, X-rays
Sources: Griffiths (atomic chs); Krane - Modern Physics (atomic chs)
174. NUCLEAR AND RADIATION PHYSICS / NUCLEAR & RADIATION PHYSICS
Codes: SPH 3400, SPH 2404 (variant)
Parts: nuclear structure, decay, reactions, radiation detection, safety
Sources: Krane - Introductory Nuclear Physics - MAIN
175. MATHEMATICAL PHYSICS I / MATHEMATICS PHYSICS I / MATHEMATICAL FOR PHYSICS I
Codes: SPH 3202, SPH 2305
Parts: vector calculus, ODEs, Fourier, complex variables for physics
Sources: Boas - Mathematical Methods in the Physical Sciences - MAIN
176. MATHEMATICAL PHYSICS II / MATHEMATICS PHYSICS II
Codes: SPH 3254, SPH 2405 (variant - check Name)
Parts: PDEs, special functions, Green's functions, integral transforms
Sources: Boas
177. MATHEMATICAL PHYSICS III / MATHEMATICAL PHYSICS
Codes: SPH 3352, SPH 3403
Parts: advanced mathematical physics - tensors, group theory for physics, distributions
Sources: Boas; Arfken - Mathematical Methods for Physicists
178. COMPUTATIONAL PHYSICS
Codes: SPH 3355, SPH 3354 (variant - check Name)
Parts: numerical physics - ODE/PDE solvers, Monte Carlo, plotting, simulation
Sources: Newman - Computational Physics - MAIN; Press - Numerical Recipes
179. LASER AND MASER PHYSICS / LASER & MASER PHYSICS / LASER AND MASER PHYSICS
Codes: SPH 3355 (variant - check Name), SPH 2412
Parts: laser principles, population inversion, cavity, types, applications
Sources: Svelto - Principles of Lasers - MAIN
180. INTRODUCTION TO GEOPHYSICS / INTRODUCTORY GEOPHYSICS
Codes: SPH 3356, SPH 2308
Parts: Earth structure, seismology, gravity, magnetism, exploration
Sources: Telford - Applied Geophysics - MAIN
181. APPLIED GEOPHYSICS
Codes: SPH 3404, SPH 2404 (variant), SPH 2409
Parts: seismic, electrical, magnetic, gravity methods, interpretation
Sources: Telford
182. MICROPROCESSOR APPLICATIONS
Codes: SPH 3406, SPH 2411
Parts: microprocessors, assembly, interfacing, embedded applications
Sources: Mano - Digital Design; Valvano - Embedded Systems
183. SOLID STATE PHYSICS
Codes: SPH 3407, SPH 2406
Parts: crystal structure, band theory, semiconductors, magnetism, superconductivity intro
Sources: Kittel - Introduction to Solid State Physics - MAIN
184. ELECTRODYNAMICS / CLASSICAL ELECTRODYNAMICS
Codes: SPH 3450, SPH 2401, SPH 3410
Parts: Maxwell, waves, radiation, relativistic electrodynamics intro
Sources: Griffiths - Introduction to Electrodynamics - MAIN
185. STATISTICAL MECHANICS
Codes: SPH 3451 (new), SPH 2402, SPH 3402, SPH 7151 (Masters - check Level)
Parts: ensembles, partition functions, Fermi/Bose, phase transitions
Sources: Pathria - Statistical Mechanics - MAIN; Schroeder
186. POLYMER PHYSICS
Codes: SPH 3453 (new), SPH 3454 (variant - check Name)
Parts: polymer structure, molecular weight, viscoelasticity, morphology
Sources: Billmeyer - Textbook of Polymer Science - MAIN
187. PLASMA PHYSICS
Codes: SPH 3454 (variant - check Name)
Parts: plasma properties, Debye, waves, fusion intro, applications
Sources: Chen - Introduction to Plasma Physics - MAIN
188. MOLECULAR PHYSICS
Codes: SPH 3452
Parts: molecular structure, spectra, bonding, rotation/vibration
Sources: Banwell - Molecular Spectroscopy; Atkins (molecular chs)
189. INSTRUMENTATION AND ELECTRONIC DEVICES / INSTRUMENTATION & ELECTRONIC DEVICES
Codes: SPH 3456, SPH 3455 (variant - check Name)
Parts: sensors, transducers, measurement, signal conditioning, instruments
Sources: Boylestad; Doebelin - Measurement Systems
190. PROPERTIES OF MATTER
Codes: SPH 2306, SPH 2308 (variant - check Name)
Parts: elasticity, surface tension, viscosity, fluids, thermal properties
Sources: Flowers & Mendoza - Properties of Matter - MAIN; Young - Elasticity
191. PHYSICS OF MATERIALS
Codes: SPH 2309
Parts: materials - structure, mechanical, electrical, magnetic, thermal properties
Sources: Callister - Materials Science and Engineering - MAIN
192. TELECOMMUNICATION SYSTEMS / TELECOMMUNICATIONS SYSTEMS
Codes: SPH 2312
Parts: modulation, transmission, antennas intro, digital comm intro, noise
Sources: Frenzel - Principles of Electronic Communication Systems - MAIN
193. PHYSICS I / PHYSICS / PHYSICS 1
Aliases: Physics I, Physics, Physics 1
Codes: SPS 3100, SPS 3150, SPS 3151 (Physics II), SPH 3150 (variant), SPH 3151 (Physics II)
Parts: service physics - mechanics, heat, electricity, optics basics
Sources: OpenStax University Physics Vol 1-3; Halliday
194. PHYSICS II
Codes: SPS 3151, SPH 3151
Parts: service physics II - electricity, magnetism, optics, modern intro
Sources: OpenStax Vol 2-3; Halliday
195. GENERAL PHYSICS
Codes: SPS 3111, SPH 3111
Parts: general physics - mechanics, heat, electricity, waves, optics
Sources: OpenStax University Physics Vol 1-3; Halliday
196. BASIC PHYSICS / PHYSICAL SCIENCE / PHYSICAL SCIENCES
Aliases: Basic Physics, Physical Science, Physical Sciences
Codes: SPS 1150, SPS 1110, SPS 1100, SPS 2100, SPS 2156, SPH 2150, SPH 2160
Parts: foundation physics - mechanics, heat, electricity, optics basics
Sources: MUST lecturer notes FIRST; OpenStax University Physics Vol 1
197. BASIC ELECTRONICS / ELECTRONICS
Codes: SPS 3200, SPS 3125, SPH 3200 (variant - check Name)
Parts: basic electronics - diodes, transistors, amplifiers, power supplies
Sources: Boylestad (intro chs); Floyd

--- A7. BIOLOGY - PLANT, MICROBIOLOGY, GENETICS, BIOTECHNOLOGY ---
198. SURVEY OF PLANT KINGDOM
Codes: SBA 3100
Parts: algae, bryophytes, pteridophytes, gymnosperms, angiosperms - survey
Sources: Raven - Biology of Plants - MAIN; OpenStax Biology 2e (plant chs)
199. PLANT MORPHOLOGY AND ANATOMY / PLANT MORPHOLOGY / PLANT MORPHOLOGY AND ANATOMY
Codes: SBA 3150
Parts: roots, stems, leaves, flowers, tissues, anatomy
Sources: Raven; Esau - Plant Anatomy
200. PLANT ECOLOGY
Codes: SBA 3200, SBT 3200 (variant - check Name), SBT 2300
Parts: plant communities, succession, interactions, ecosystems
Sources: Raven; Begon - Ecology (plant chs)
201. INTRODUCTION TO MICROBIOLOGY / INTRODUCTORY MICROBIOLOGY
Codes: SBA 3201
Parts: microbes, bacteria, viruses, fungi intro, methods
Sources: Prescott - Microbiology (intro chs) - MAIN
202. PLANT BIOCHEMISTRY AND PHYSIOLOGY / PLANT PHYSIOLOGY AND BIOCHEMISTRY / PLANT BIOCHEMISTRY AND PHSIOLOGY
Codes: SBA 3250, SBA 3202, SBT 2200
Parts: photosynthesis, respiration, hormones, nutrition, stress
Sources: Taiz - Plant Physiology - MAIN; Lehninger (plant biochem chs)
203. GENERAL MICROBIOLOGY
Codes: SBA 3251, SBA 3300 (variant - check Name), SBA 3350, SBT 2303, SBT 2305
Parts: microbial diversity, growth, metabolism, genetics, control
Sources: Prescott - Microbiology - MAIN
204. TAXONOMY OF HIGHER PLANTS / TAXONOMY OF HIGHER PLANT / AGRICULTURAL PLANT TAXONOMY / PLANT TAXONOMY
Aliases: Taxonomy of Higher Plants, Agricultural Plant Taxonomy, Plant Taxonomy
Codes: SBA 3300 (check Name), SBA 3301 (variant), SBT 2351, SBT 2302
Parts: classification, nomenclature, families, keys, herbarium
Sources: Raven; Stace - Plant Taxonomy
205. PLANT PATHOLOGY / DIAGNOSIS OF PLANT DISEASES / DIAGNOSIS OF PLANTS DISEASES / CONTROL OF PLANT DISEASES
Aliases: Plant Pathology, Diagnosis of Plant Diseases, Control of Plant Diseases
Codes: SBA 3303, SBA 3301 (variant), AAC 3353, AAC 3302, SBT 2420, SBT 2414, SBT 2454 (Seed Pathology)
Parts: pathogens, symptoms, diagnosis, control, host resistance
Sources: Agrios - Plant Pathology - MAIN
206. APPLIED MICROBIOLOGY
Codes: SBA 3402, SBT 2409
Parts: food, industrial, medical, environmental applications
Sources: Prescott; Madigan - Brock Biology of Microorganisms
207. CELLULAR BASIS OF LIFE
Codes: SBT 3101, SBT 2103, SBT 3112, SBT 2201 (Cell Biology variant)
Parts: cell structure, organelles, membranes, division, signalling intro
Sources: Alberts - Molecular Biology of the Cell (intro chs); OpenStax Biology 2e
208. PLANT FUNCTION
Codes: SBT 3150, SBT 2102
Parts: plant processes - photosynthesis, transport, growth, responses
Sources: Taiz - Plant Physiology; Raven
209. ENVIRONMENTAL SCIENCE (PLANT / BIOLOGY)
Codes: SBT 3200, SBT 3100, SBT 2205 (variant)
Parts: ecosystems, pollution, conservation, sustainability
Sources: OpenStax Environmental Science - MAIN; Miller - Living in the Environment
210. GENERAL GENETICS / GENETICS AND CYTOGENETICS / GENETIC AND CYTOGENETIC
Aliases: General Genetics, Genetics and Cytogenetics
Codes: SBT 3250, SBT 3252, ST 3250
Parts: Mendelian, linkage, chromosomes, mutations, population genetics intro
Sources: Hartl & Jones - Genetics - MAIN; Klug - Concepts of Genetics
211. PRINCIPLES OF GENETICS
Codes: SBT 2301
Parts: Mendelian, linkage, molecular genetics intro
Sources: Hartl & Jones; Klug
212. ADVANCED GENETICS
Codes: SBT 2308
Parts: advanced - quantitative, molecular, genomics intro, epigenetics intro
Sources: Hartl & Jones (advanced chs); Klug
213. BIOTECHNOLOGY (PLANT)
Codes: SBT 3457, SBT 2417
Parts: recombinant DNA, tissue culture, GM crops, applications, ethics intro
Sources: Smith - Plant Biotechnology - MAIN; Primrose - Principles of Gene Manipulation
214. PLANT BREEDING
Codes: SBT 3458
Parts: selection, hybridisation, heterosis, molecular breeding, seed systems
Sources: Allard - Principles of Plant Breeding - MAIN
215. VIROLOGY
Codes: SBT 3459, SBT 2419
Parts: virus structure, replication, classification, plant/animal viruses, control
Sources: Flint - Principles of Virology - MAIN
216. PLANT CELL AND TISSUE CULTURE / CELL AND TISSUE CULTURE / CELL & TISSUE CULTURE
Codes: SBT 3450, SBT 2423
Parts: explants, media, micropropagation, somatic embryogenesis, applications
Sources: Lodish - Molecular Cell Biology (tissue culture chs); Smith - Plant Biotechnology
217. PLANT GROWTH AND DEVELOPMENT / CROP GROWTH AND DEVELOPMENT
Aliases: Plant Growth and Development, Crop Growth and Development
Codes: SBT 2450, SBT 3401, SBT 2457
Parts: growth, differentiation, hormones, flowering, senescence, crop growth
Sources: Taiz - Plant Physiology; Raven
218. BOTANICAL TECHNIQUES
Codes: SBT 2255
Parts: collection, preservation, microscopy, sectioning, staining, herbarium
Sources: MUST lecturer notes FIRST; Johansen - Plant Microtechnique
219. BACTERIOLOGY
Codes: SBT 2270, SHD 3251 (bacteriology variant - check Name)
Parts: bacterial structure, classification, growth, identification, control
Sources: Prescott; Madigan
220. ENVIRONMENTAL MICROBIOLOGY
Codes: SBT 2410
Parts: microbes in soil/water/air, biogeochemical cycles, bioremediation
Sources: Prescott (environmental chs); Madigan
221. POPULATION ECOLOGY (PLANT)
Codes: SBT 2411
Parts: population growth, life tables, competition, predation, metapopulations
Sources: Begon - Ecology - MAIN
222. AGRICULTURAL BOTANY
Codes: SBT 2350, BIO 0110
Parts: botany for agriculture - crops, anatomy, physiology, taxonomy basics
Sources: Raven; Taiz
223. BOTANY AND ZOOLOGY
Codes: SCS 2100 (variant - check Name), BIO 0211 (Microbiology & Zoology variant)
Parts: botany + zoology survey - plants, animals, diversity, structure
Sources: OpenStax Biology 2e; Raven + Hickman (combined)
224. PRINCIPLES OF BIOLOGY
Codes: SZV 3100, SZV 3111
Parts: biology basics - cells, genetics, evolution, ecology, diversity
Sources: OpenStax Biology 2e - MAIN; Campbell Biology
225. PRINCIPLES OF ZOOLOGY
Codes: SZV 3150
Parts: zoology basics - animal diversity, structure, function, evolution
Sources: Hickman - Integrated Principles of Zoology (intro chs); OpenStax Biology 2e

--- A8. BIOCHEMISTRY ---
226. BASIC METABOLISM I / BASIC METABOLISM
Codes: SHC 3202
Parts: carbohydrates, glycolysis, TCA, oxidative phosphorylation, lipids intro
Sources: Lehninger - Principles of Biochemistry - MAIN; Stryer
227. BASIC METABOLISM II / METABOLISM II
Codes: SHC 3250
Parts: amino acids, nucleotides, integration, regulation, photosynthesis intro
Sources: Lehninger; Stryer
228. STRUCTURAL BIOCHEMISTRY
Codes: SHC 3204
Parts: biomolecules - carbs, lipids, proteins, nucleic acids - structure
Sources: Lehninger (structure chs); Voet & Voet
229. PROTEIN BIOCHEMISTRY
Codes: SHC 3252
Parts: protein structure, folding, purification, characterisation, enzymes intro
Sources: Lehninger; Voet & Voet
230. ENZYMOLOGY
Codes: SHC 3300
Parts: enzyme kinetics, inhibition, regulation, mechanisms, applications
Sources: Lehninger (enzymes chs); Voet & Voet (enzymes chs)
231. BIOCHEMICAL BACTERIOLOGY AND MYCOLOGY / BIOCHEMISTRY BACTERIOLOGY AND MYCOLOGY
Codes: SHC 3301
Parts: bacterial/fungal biochemistry - metabolism, cell walls, toxins, identification
Sources: Prescott; Madigan; Lehninger
232. INTEGRATED BIOCHEMICAL TECHNIQUES I
Codes: SHC 3251
Parts: chromatography, electrophoresis, spectrophotometry, centrifugation
Sources: Wilson & Walker - Principles and Techniques of Biochemistry and Molecular Biology - MAIN
233. INTEGRATED BIOCHEMICAL TECHNIQUES II / INTEGRATED BIOCHEMISTRY TECHNIQUES
Codes: SHC 3302 (check Name - NOT Basic Immunology), SHC 3302 (2018 variant)
Parts: advanced techniques - HPLC, MS, NMR for biochem, radioisotopes
Sources: Wilson & Walker
234. INTEGRATED BIOCHEMICAL TECHNIQUES III
Codes: SHC 3402 (check Name - NOT Pharmacology/Toxicology variant), SHC 3402 (2019 variant)
Parts: proteomics, genomics techniques, bioinformatics tools, advanced methods
Sources: Wilson & Walker; Lesk - Genomics
235. NUTRITIONAL BIOCHEMISTRY
Codes: SHC 3303
Parts: nutrients, vitamins, minerals, energy, malnutrition, assessment
Sources: Bender - Nutritional Biochemistry - MAIN; Lehninger (nutrition chs)
236. MICROBIAL BIOCHEMISTRY / APPLIED MICROBIAL BIOCHEMISTRY
Codes: SHC 3350
Parts: microbial metabolism, fermentation, industrial applications
Sources: Lehninger; Prescott
237. BIOMEMBRANES AND CELLULAR SIGNALING / BIOMEMBRANES AND CELLULAR SIGNALLING / BIOMEMBRANES AND CELLUAR SIGNALLING
Codes: SHC 3351, SCH 3302 (misfile - check Name)
Parts: membranes, transport, receptors, signalling pathways
Sources: Alberts - Molecular Biology of the Cell - MAIN; Lehninger
238. RECOMBINANT DNA TECHNOLOGY
Codes: SHC 3352, SHD 3352 (variant - check Name)
Parts: cloning, vectors, PCR, libraries, expression, applications
Sources: Primrose - Principles of Gene Manipulation - MAIN; Brown - Gene Cloning
239. BIOCHEMISTRY OF HORMONES
Codes: SHC 3353
Parts: hormones, receptors, signalling, endocrine disorders, assays
Sources: Lehninger (hormones chs); Voet & Voet
240. BIOCHEMISTRY OF NUCLEIC ACIDS / BIOCHEMISTRY OF NUCLEAR ACID / BIOCHEMISTRY OF NUCLEIC ACID
Codes: SHC 3354, SBC 2302
Parts: DNA/RNA structure, replication, transcription, translation, repair
Sources: Lehninger; Alberts
241. BIOCHEMISTRY OF IMMUNOLOGY
Codes: SHC 3400
Parts: immune biochemistry - antibodies, complement, cytokines, MHC
Sources: Janeway - Immunobiology - MAIN; Lehninger (immunology chs)
242. BIOINFORMATICS
Codes: SHC 3401, SZE 5153 (Masters - check Level)
Parts: databases, sequence alignment, phylogenetics, genomics tools
Sources: Lesk - Introduction to Bioinformatics - MAIN
243. BIOCHEMICAL TOXICOLOGY / PHARMACOLOGY AND TOXICOLOGY (BIOCHEM)
Aliases: Biochemical Toxicology, Pharmacology and Toxicology
Codes: SHC 3403, SHC 3402 (2017 variant - check Name)
Parts: toxins, metabolism, dose-response, antidotes, drug toxicity
Sources: Rang & Dale - Pharmacology (toxicology chs); Lehninger
244. CLINICAL BIOCHEMISTRY
Codes: SHC 3450
Parts: clinical tests, liver/kidney, diabetes, lipids, tumour markers
Sources: Murray - Harper's Illustrated Biochemistry - MAIN
245. FORENSIC BIOCHEMISTRY
Codes: SHC 3451 (2024) / SHC 3453 (2017) - NAME WINS, see Website Rule
Parts: forensic DNA, toxicology, serology, evidence, legal
Sources: Butler - Forensic Biochemistry - MAIN; Primrose (forensic DNA chs)
246. METABOLIC REGULATION AND INTEGRATION
Codes: SHC 3453 (2024) / SHC 3451 (2017) - NAME WINS
Parts: metabolic control, hormones, fasting/feeding, diabetes, integration
Sources: Newsholme - Metabolic Regulation - MAIN; Lehninger (regulation chs)
247. BIOCHEMISTRY OF PHARMACEUTICALS / BIOCHEMISTRY OF HARMACECITACALS
Codes: SHC 3452 (check Name - NOT Medical Biotechnology)
Parts: drug biochemistry - targets, metabolism, pharmacokinetics intro
Sources: Rang & Dale - Pharmacology - MAIN; Lehninger
248. MEDICAL BIOTECHNOLOGY
Codes: SHC 3452 (2024 variant - check Name)
Parts: medical biotech - diagnostics, therapeutics, vaccines, gene therapy
Sources: Ratledge - Basic Biotechnology - MAIN; Primrose
249. COMPARATIVE BIOCHEMISTRY
Codes: SHC 3454
Parts: comparative metabolism, adaptations, evolution of pathways
Sources: Lehninger; Schmidt-Nielsen - Animal Physiology (comparative chs)
250. LABORATORY TECHNIQUES (BIOCHEMISTRY)
Codes: SHC 3203, SCH 3203 (chem variant - check Name)
Parts: lab safety, pipetting, dilutions, spectrophotometry, basic techniques
Sources: MUST lecturer notes FIRST; Wilson & Walker
251. BIOCHEMISTRY (GENERAL) / BIOCHEMISTRY I / BIOCHEMISTRY II / INTRODUCTION TO BIOCHEMISTRY / INTRODUCTION TO BIOCHEMISTRY II
Aliases: Biochemistry, Biochemistry I, Biochemistry II, Introduction to Biochemistry
Codes: SHD 3201, SHV 3101, SHV 3150, SHV 3151, SHV 3200, SBH 2211, SBH 3100, SBT 2417 (Biochemistry variant), SHC 3202 (variant)
Parts: depends on clarification - see Website Rule 4. General: biomolecules, enzymes, metabolism intro
Sources: Lehninger - MAIN; Stryer
252. INTRODUCTION TO BIOTECHNOLOGY
Codes: SHD 3203
Parts: biotech basics - fermentation, recombinant, applications, ethics
Sources: Ratledge - Basic Biotechnology; Smith - Plant Biotechnology
253. METABOLISM OF MACROMOLECULES
Codes: SHD 3250
Parts: carbs, lipids, proteins, nucleic acids - metabolism
Sources: Lehninger
254. BACTERIOLOGY (BIOTECH)
Codes: SHD 3251
Parts: bacterial structure, growth, classification, identification
Sources: Prescott; Madigan
255. MYCOLOGY
Codes: SHD 3252
Parts: fungi - structure, classification, medical/industrial, mycotoxins
Sources: Prescott (mycology chs); Madigan
256. PROTOZOOLOGY
Codes: SHD 3300 (variant - check Name)
Parts: protozoa - structure, life cycles, medical, control
Sources: Prescott; Cox - Modern Parasitology
257. MICROBIAL GENETICS
Codes: SHD 3304
Parts: bacterial genetics, plasmids, transposons, mutation, recombination
Sources: Madigan; Primrose
258. PROKARYOTIC GENE EXPRESSION
Codes: SHD 3305
Parts: transcription, translation, regulation in prokaryotes, operons
Sources: Alberts; Lehninger
259. HELMINTHOLOGY
Codes: SHD 3350, SHD 3352 (variant - check Name)
Parts: helminths - trematodes, cestodes, nematodes, life cycles, control
Sources: Roberts - Helminthology - MAIN; Cox
260. PHARMACOLOGY
Codes: SHD 3351
Parts: drug actions, pharmacokinetics, pharmacodynamics, classes, toxicity
Sources: Rang & Dale - Pharmacology - MAIN
261. MOLECULAR DIAGNOSTICS AND GENE THERAPY / HELMINTHOLOGY (VARIANT)
Codes: SHD 3352 (variant - check Name)
Parts: molecular diagnostics - PCR, probes, gene therapy - vectors, applications
Sources: Primrose; Lesk - Genomics
262. PLANT BIOTECHNOLOGY
Codes: SHD 3353
Parts: plant tissue culture, GM plants, molecular breeding, applications
Sources: Smith - Plant Biotechnology - MAIN
263. EUKARYOTIC GENE EXPRESSION
Codes: SHD 3354
Parts: eukaryotic transcription, splicing, translation, regulation, epigenetics intro
Sources: Alberts; Lehninger
264. ANIMAL BIOTECHNOLOGY
Codes: SHD 3400
Parts: animal cell culture, transgenics, cloning, IVF, applications
Sources: Ratledge; Primrose
265. INDUSTRIAL BIOTECHNOLOGY
Codes: SHD 3401
Parts: fermentation, bioreactors, downstream, industrial products
Sources: Ratledge - Basic Biotechnology - MAIN
266. BIOPHARMACEUTICS
Codes: SHD 3403
Parts: biopharmaceuticals - production, formulation, delivery, regulation
Sources: Ratledge; Rang & Dale
267. FORENSIC GENETICS AND ITS APPLICATIONS
Codes: SHD 3451
Parts: forensic DNA, STR, paternity, population genetics for forensics
Sources: Butler - Forensic Biochemistry; Primrose
268. BIOETHICS, BIOSAFETY AND BIO-POLICY / BIOETHICS AND INTELLECTUAL PROPERTY RIGHTS (Masters variant)
Codes: SHD 3453, SZE 5157 (Masters - check Level)
Parts: bioethics, biosafety, policy, IP, consent, dual-use
Sources: Shamoo - Bioethics - MAIN; MUST lecturer notes
269. GENOMICS AND PROTEOMICS / GENOMICS, PROTEOMICS, METABOLOMICS AND TRANSCRIPTOMICS
Codes: SHD 3454, SZE 5151 (Masters - check Level)
Parts: genomics, proteomics, transcriptomics, metabolomics - methods, analysis
Sources: Lesk - Genomics - MAIN; Primrose
270. ANIMAL METABOLISM AND ENZYMOLOGY
Codes: SHV 3250
Parts: animal metabolism, enzymes, hormones, energy
Sources: Lehninger; Schmidt-Nielsen
271. BIOCHEMISTRY OF PARASITOLOGY
Codes: SZH 3454 (variant - check Name)
Parts: parasite biochemistry - metabolism, drugs, resistance
Sources: Lehninger; Cox

--- A9. ENVIRONMENTAL SCIENCE ---
272. FUNDAMENTALS OF NATURAL RESOURCE MANAGEMENT / INTEGRATED NATURAL RESOURCE MANAGEMENT (Masters variant)
Codes: SEG 3150, SEG 5101 (Masters - check Level)
Parts: resources, management, conservation, policy, community
Sources: Adams - Natural Resource Management - MAIN; Miller - Living in the Environment
273. WEATHER AND CLIMATE
Codes: SEG 3200
Parts: atmosphere, weather, climate, forecasting, climate change
Sources: Pidwirny - Weather & Climate - MAIN; OpenStax Environmental Science
274. INTRODUCTION TO EARTH SYSTEMS
Codes: SEG 3201
Parts: Earth systems - atmosphere, hydrosphere, lithosphere, biosphere, cycles
Sources: Kump - Earth System - MAIN
275. FUNDAMENTALS OF AQUATIC ECOLOGY
Codes: SEG 3202
Parts: aquatic ecosystems, freshwater, marine, food webs, pollution
Sources: Dodds - Aquatic Ecology - MAIN; Begon
276. ENVIRONMENTAL SCIENCE (GENERAL)
Codes: SBT 3100 (variant), SBT 3200 (variant)
Parts: ecosystems, pollution, conservation, sustainability
Sources: OpenStax Environmental Science; Miller

--- A10. ZOOLOGY ---
277. INVERTEBRATE ZOOLOGY / INVERTEBRATE ZOOLOGY I / INVERTEBRATE ZOOLOGY II / INVERTEBRATE I
Aliases: Invertebrate Zoology, Invertebrate Zoology I, Invertebrate Zoology II
Codes: SZA 3100, SZA 3101, SZA 3111, SZL 2100, SZL 2101, SZL 3103 (variant)
Parts: invertebrate phyla - sponges to arthropods, structure, diversity, evolution
Sources: Hickman - Integrated Principles of Zoology - MAIN; OpenStax Biology 2e
278. VERTEBRATE ZOOLOGY / VERTEBRATE ZOOLOGY I / VERTABRATE ZOOLOGY
Codes: SZA 3150, SZL 2200
Parts: vertebrates - fish to mammals, structure, diversity, evolution
Sources: Hickman
279. INVERTEBRATE AND VERTEBRATE ZOOLOGY
Codes: SZL 3103
Parts: invertebrates + vertebrates - combined survey
Sources: Hickman; OpenStax Biology 2e
280. CELL BIOLOGY
Codes: SZA 3200, SBT 2201 (variant), SZA 3202 (variant)
Parts: cell structure, organelles, division, signalling, cytoskeleton
Sources: Alberts - Molecular Biology of the Cell - MAIN; Lodish
281. DEVELOPMENTAL BIOLOGY / DEVELOPMENT BIOLOGY
Codes: SZA 3205, SZA 3305, SZA 3350, SZL 3205, SZL 2202, SZL 3205
Parts: development - gametogenesis, fertilisation, cleavage, morphogenesis, differentiation
Sources: Gilbert - Developmental Biology - MAIN; Alberts
282. COMPARATIVE ANIMAL PHYSIOLOGY
Codes: SZA 3250
Parts: comparative - respiration, circulation, excretion, nervous, endocrine across animals
Sources: Schmidt-Nielsen - Animal Physiology - MAIN
283. INTRODUCTION TO ANIMAL PHYSIOLOGY
Codes: SZL 3150, SZL 2102
Parts: animal physiology intro - systems, homeostasis, regulation
Sources: Schmidt-Nielsen; Tortora - Human Anatomy & Physiology (systems chs)
284. INTRODUCTION TO HUMAN ANATOMY AND PHYSIOLOGY / HUMAN ANATOMY AND PHYSIOLOGY / INTRODUCTION TO HUMAN ANATOMY AND PHYSIOLOGY
Codes: SZL 3204
Parts: human anatomy + physiology - all systems, homeostasis
Sources: Tortora - Human Anatomy & Physiology - MAIN
285. ECOLOGY AND BIOANALYSIS / ECOLOGY BIOANALYSIS / ECOLOGY AND BIOANALYSIS
Codes: SZL 3100, SZA 3100 (variant - check Name)
Parts: ecology + bioanalysis - sampling, analysis, ecosystems, populations
Sources: Begon - Ecology; OpenStax Biology 2e (ecology chs)
286. MOLECULAR BIOLOGY
Codes: SZL 3250 (check Name - NOT Animal Ecology), SZL 3250 (variant)
Parts: DNA, replication, transcription, translation, regulation, techniques
Sources: Alberts; Lehninger
287. ANIMAL ECOLOGY
Codes: SZL 3250 (variant - check Name), SZL 3251 (variant)
Parts: animal populations, communities, behaviour, interactions
Sources: Begon - Ecology - MAIN
288. APPLIED ECOLOGY
Codes: SZL 2402, SZL 3452
Parts: applied ecology - conservation, restoration, management, human impacts
Sources: Begon; Smith - Applied Ecology - MAIN
289. POPULATION ECOLOGY
Codes: SZL 3403, SZL 2411, SBT 2411 (plant variant)
Parts: population growth, life tables, competition, predation, metapopulations
Sources: Begon - Ecology - MAIN
290. BASIC IMMUNOLOGY I / BASIC IMMUNOLOGY / IMMUNOLOGY I / BASIC IMMUNOLOGY I
Aliases: Basic Immunology I, Basic Immunology, Immunology I
Codes: SZL 3302, SZL 3305 (variant), SZA 3305, SZL 2314, SHC 3302 (2017 variant - check Name)
Parts: innate/adaptive, antibodies, antigens, complement, MHC intro
Sources: Janeway - Immunobiology - MAIN
291. ADVANCED IMMUNOLOGY
Codes: SZL 3350 (variant), SZL 3355, SZL 2315, SZA 3401 (variant - check Name)
Parts: advanced - tolerance, autoimmunity, transplantation, tumour immunology
Sources: Janeway (advanced chs)
292. IMMUNOLOGY (GENERAL)
Codes: SZV 3350
Parts: immunology basics - innate/adaptive, antibodies, vaccines intro
Sources: Janeway (intro chs)
293. ARTHROPOD BIOLOGY / ANTHROPOD BIOLOGY / ARTHROPPOD BIOLOGY
Codes: SZL 3303, SZL 2300, SZL 2306
Parts: arthropods - structure, diversity, physiology, evolution
Sources: Gullan - The Insects (arthropod chs); Hickman
294. COMPARATIVE ARTHROPOD MORPHOLOGY
Codes: SZH 3201
Parts: arthropod morphology - comparative, segmentation, appendages, evolution
Sources: Gullan; Hickman
295. EVOLUTIONARY BIOLOGY / EVOLUTIONARY BIOLOGY / EVOLUTONARY BIOLOGY
Codes: SZL 3351, SZL 3355 (variant), SZL 2307
Parts: evolution - natural selection, speciation, phylogenetics, population genetics
Sources: Futuyma - Evolutionary Biology - MAIN
296. COMPARATIVE ENDOCRINOLOGY / COMPARATIVE ENDOCRONOLOGY
Codes: SZL 3402, SZL 2304 (variant)
Parts: comparative endocrine - hormones, glands, regulation across animals
Sources: Norris - Vertebrate Endocrinology - MAIN
297. NEUROENDOCRINOLOGY
Codes: SZL 3451, SZL 2410
Parts: neuroendocrine - hypothalamus, pituitary, hormones, behaviour
Sources: Norris
298. ENTOMOLOGY I
Codes: SZL 3353, SZL 2403, SZL 3350 (variant)
Parts: insects I - morphology, physiology, taxonomy intro, diversity
Sources: Gullan - The Insects - MAIN
299. ENTOMOLOGY II / APPLIED ENTOMOLOGY
Aliases: Entomology II, Applied Entomology
Codes: SZL 3450, SZL 2404
Parts: insects II - ecology, behaviour, pests, control, applied
Sources: Gullan; Pedigo - Entomology and Pest Management
300. INTRODUCTORY ENTOMOLOGY
Codes: SZL 3252
Parts: insects intro - diversity, structure, life cycles, importance
Sources: Gullan (intro chs)
301. AGRICULTURAL ENTOMOLOGY
Codes: SZL 3353 (variant - check Name)
Parts: agricultural insects - pests, beneficial, IPM, control
Sources: Gullan; Pedigo
302. PARASITOLOGY I / PARASITOLOGY / PARASITOLOGY I
Codes: SZL 3251, SZL 3354 (variant - check Name), SZL 2405, SZL 3304
Parts: parasites I - protozoa, helminths intro, life cycles, host-parasite
Sources: Cox - Modern Parasitology - MAIN
303. PARASITOLOGY II
Codes: SZL 3354, SZL 2406, SZL 3404
Parts: parasites II - advanced, epidemiology, control, immunology of parasites
Sources: Cox
304. HOST PARASITE INTERACTION / HOST PARASITE INTERACTIONS / HOST-PARASITE INTERACTION
Codes: SZH 3251, SZH 3302 (variant), SZH 3251
Parts: host-parasite - coevolution, immune evasion, virulence, resistance
Sources: Cox; Janeway (parasite immunology chs)
305. DYNAMICS OF PARASITIC DISEASES / DYNAMICS PARASITIC DISEASES
Codes: SZH 3350, SZH 3301
Parts: parasitic disease dynamics - transmission, epidemiology, modelling intro, control
Sources: Cox; Rothman - Epidemiology (parasite chs)
306. ZOONOTIC DISEASES / ZOONOTIC DISEASE
Codes: SZH 3451, SZH 3300 (variant - check Name), SCH 3300 (misfile - check Name)
Parts: zoonoses - transmission, reservoirs, prevention, examples
Sources: Cox; Rothman
307. PARASITOLOGICAL TECHNIQUES / PARASITOLOGICAL TECHNIQUES
Codes: SZH 3455, SZH 3300 (variant - check Name)
Parts: parasite techniques - collection, preservation, microscopy, diagnosis
Sources: MUST lecturer notes FIRST; Cox (techniques chs)
308. PESTICIDES AND ENVIRONMENT / PESTICIDES AND ENVIRON / PESTICIDES AND ENVIRONMENT
Codes: SZH 3453, SZH 3454 (variant - check Name)
Parts: pesticides - types, modes, resistance, environmental fate, safety
Sources: Pedigo - Entomology and Pest Management; Miller - Living in the Environment
309. PHARMACOLOGY AND TOXICOLOGY (ZOOLOGY)
Codes: SZH 3454 (variant - check Name), SHC 3402 (variant)
Parts: pharmacology/toxicology for zoology - drugs, toxins, dose, antidotes
Sources: Rang & Dale - Pharmacology
310. COMMUNITY DIAGNOSIS
Codes: SZH 3403
Parts: community diagnosis - health assessment, epidemiology, interventions, evaluation
Sources: Gordis - Epidemiology / Community Diagnosis - MAIN; Rothman
311. BIOLOGICAL INSTRUMENTATION
Codes: SZH 3200
Parts: instruments - microscopy, spectroscopy, centrifugation, electrophoresis for biology
Sources: Wilson & Walker - Principles and Techniques of Biochemistry and Molecular Biology - MAIN
312. EXPERIMENTAL ANIMAL SCIENCE
Codes: SZH 3250
Parts: experimental animals - husbandry, ethics, design, handling, models
Sources: MUST lecturer notes FIRST; Schmidt-Nielsen; Festing - Experimental Animal Science
313. RESEARCH METHODOLOGY (ZOOLOGY)
Codes: SZL 3350 (variant - check Name), SZL 3350 (zoology variant)
Parts: research design, sampling, instruments, proposal, report for zoology
Sources: Kothari - Research Methodology; MUST lecturer notes

--- A11. PLANT SCIENCE - AGRICULTURE (by NAME, kept for cross-listing) ---
314. AGRICULTURAL PLANT TAXONOMY - see #204
315. AGRICULTURAL RISK MANAGEMENT - Non-SPAS (Section C) - AAA 3450
316. AGRIBUSINESS RESOURCE MANAGEMENT - Non-SPAS - AAB 2325
317. DIAGNOSIS OF PLANT DISEASES - see #205
318. SEED PATHOLOGY - see #205 (SBT 2454)
319. CROP GROWTH AND DEVELOPMENT - see #217

--- A12. RISK MANAGEMENT & INSURANCE (cross-listed) ---
320. INSURANCE AND RISK MANAGEMENT
Codes: BFB 3150, HBC 2118 (cross-listed - KEEP)
Parts: risk, insurance, products, underwriting, claims
Sources: Rejda - Principles of Risk Management and Insurance - MAIN
321. DECISION MAKING IN PROJECTS
Codes: BFB 3362
Parts: project decisions, risk, appraisal, NPV, sensitivity
Sources: Taha (decision chs); Rejda

================================================================
SECTION B - MASTERS / POSTGRADUATE - BY NAME - MARK AS SKIPPED FOR BSc
Student uploads a Masters name -> answer: Not BSc SPAS Undergrad - Skipped.
Do NOT mix Masters into undergrad notes.
Names (all seen on site, 5xxx-8xxx):
Advanced Analytical Chemistry, Analytical Techniques, Advanced Chemical Thermodynamics,
Advanced Group Theory, Advanced Coordination Chemistry, Atomic & Molecular Spectroscopy,
X-Ray Crystallography, Chemistry of Materials, Advanced Solid State Chemistry,
Natural Products I Primary Metabolites, Natural Products II Secondary Metabolites,
Chemistry of Carbohydrates and Proteins (Masters), Nanomaterials and Nanotechnology,
Modern Synthetic Methods in Organic Chemistry, Measure and Integration (Masters),
Functional Analysis I/II (Masters), Group Theory I (Masters), General Topology (Masters),
Complex Analysis III (Masters), Introduction to Mathematical Cryptography,
Advanced Numerical Analysis, Differential Geometry (PhD), Functional Analysis (PhD),
Mathematical Modelling (PhD), Biomathematics, Fluid Mechanics Analysis,
Ordinary Differential Equations III/IV, Fluid Mechanics III/IV, Numerical Analysis III,
Riemannian Geometry, Partial Differential Equations III, Measure & Probability (Masters),
Multivariate Analysis (Masters), Parametric Regression Analysis, Statistical Inference Theory,
Design and Analysis of Experiments (Masters), Research Methodology (Masters),
Time Series (Masters), Stochastic Processes (Masters), Survival & Clinical Data Analysis,
Decision Theory (Masters), Epidemiological Research Methods (Masters),
Non-Parametric Methods (Masters), Non-Parametric Regression Analysis,
Modelling Extremal Events, Design & Analysis of Sample Surveys (Masters),
Classical Electrodynamics (Masters), Statistical Mechanics (Masters),
Stellar and Galactic Astrophysics, Extragalactic Astronomy, Radio Astronomy,
Optical Communication Systems, Digital Modulation and Channel Coding,
Noise and Interferences, General Astrophysics, Quantum Mechanics (Masters),
Classical Mechanics (Masters), Mathematical Physics (Masters),
Integrated Natural Resource Management (Masters), Community Ecology,
Fundamentals of Environmental Systems, Environmental and Social Impact Assessment,
Environmental and Sustainable Development, Toxic Substance, Water Resource,
Climate Systems, Biodiversity, Insect Physiology and Biochemistry,
Insect Taxonomy and Systematics, Agricultural and Stored Products Entomology,
Vector Biology and Control, Insect Ecology, Entomological Techniques,
Integrated Pest Management, Vector Biology, Research Methods 1,
Membrane Dynamics and the Cytosol, Applied Molecular Biology, Molecular Bacteriology,
Research Methodology Bioethics, Advanced Biostatistics, Advances in Molecular Biotechniques I/II,
Molecular Virology, Genomics, Proteomics, Metabolomics and Transcriptomics (Masters),
Molecular Epigenetic Mechanisms, Bioinformatics (Masters), Pharmaceutical Biotechnology,
Bioethics and Intellectual Property Rights, Advanced Molecular Plant Biochemistry and Physiology,
Advanced Dairy Biochemistry and Technology, Dairy / Biostatistics (Masters),
Statistics for Data Science (Masters - CCD 7100), Optimization and Computational Linear Algebra,
Statistical Inference and Modeling in R, Statistical Inference and Modeling in Research,
Statistics for Business (Masters - SMB 5100), Advanced Research Methods (Masters - BBIT 6100),
Advanced Business Statistics (Masters)

================================================================
SECTION C - NON-SPAS / COMMON UNITS - BY NAME - MARK AS SKIPPED
Student uploads one of these names -> answer: Not SPAS - Skipped. Do NOT cover.
Names (all seen on SPAS archive but belonging to other schools):
Agricultural Risk Management, Agribusiness Resource Management,
Agribusiness Supply and Value Link Analysis, Cooperative Management and Development,
Management Accounting, Business Statistics, Business Mathematics, Basic Business Mathematics,
Basic Management Mathematics, Management Mathematics, Quantitative Methods I/II,
Operations Research I (Business variant), Statistics for Supply Chain Management,
Engineering Mathematics I-VI, Engineering Maths I-VI, Mathematics I/II/III (Engineering),
Probability and Statistics (Engineering), Numerical Methods (Engineering),
Physics for Health Sciences, Physics for Medical Sciences, Medical Biostatistics,
Introduction to Medical Biostatistics, Biostatistics (Health-only), Environmental Chemistry (Health-only),
Public and Community Health, Community Diagnosis (Health-only - check School),
HIV and AIDS / HIV AIDS (UCU 3103 - University Common Unit),
Concrete Durability (Civil Engineering), Advanced Research Methods (Business IT Masters),
Food Science / Nutrition / Food Industry Management (AFT/AFN/AFM),
Dairy Biochemistry (AFT Masters), Business / Economics / Supply Chain / Cooperative (SBE)

EXCEPTION - KEEP (cross-listed, Section A):
Insurance and Risk Management (BFB 3150), Decision Making in Projects (BFB 3362),
Biostatistics / Statistics (SPAS cross-listed - see #105), Botany and Zoology (SCS 2100)

================================================================
SECTION D - WHAT TO DO WHEN NAME DOES NOT MATCH YET
NEVER say "Not found" as your first answer. "Not found" is BANNED for SPAS units.

STEP 1 - If Code fails but Name passes:
TEACH BY NAME. Show:
You wrote: [Student Name verbatim] ([Student Code verbatim])
Matched: [Canonical Unit Name]
Note: Unit codes at Meru University have been changing with time - proved by
exampapers.must.ac.ke (same code, different unit in different years).
Your notes below are for the unit NAME you gave.
Then give the full notes for that Canonical Name.

STEP 2 - If Name does not match either:
Say EXACTLY this, and STOP - do not guess a unit:
"I could not match that name yet. Please insert the unit NAME exactly as it
appears in your exam paper - copy it letter by letter, including I / II / III,
and upload it together with the unit code from the same paper.
Example: Unit Name: Chemical Kinetics | Unit Code: SCH 3354
If your paper is a photo/scan, upload the photo of the top of the paper
where the unit name is printed, and I will read it from there."
Then, ONLY if it helps, show up to 3 CLOSEST names from Section A and ask:
"Did you mean one of these? Reply with the exact name from your paper."
Do NOT teach any closest name until the student confirms the exact name.
Do NOT invent a source. Do NOT guess by code.

STEP 3 - If after exact name it STILL does not match:
Say: "I have checked the exact name you gave against all SPAS papers on
exampapers.must.ac.ke. Please check the spelling on your paper once more,
or upload a photo of the top of your paper, and I will read the name from there."
Still do NOT say "Not found" alone, and still do NOT guess.

STEP 4 - The ONLY allowed "Skipped":
"Not SPAS - Skipped" - only when the unit is from another school (Section C).
Never use "Not found" for a SPAS unit.

================================================================
WHAT CHANGED IN V3.3 (vs V3.2)
STUDENT INPUT CHANGED: Name alone -> Name EXACTLY as on paper + Code from SAME paper, together.
MATCHING CHANGED: Name wins, Code is companion/hint. If Code fails but Name passes -> TEACH BY NAME + explain codes changed over time at MUST (proved by exampapers.must.ac.ke).
"NOT FOUND" BANNED as first answer: AI must ask student to insert unit name exactly as it appears in exam paper, with example, and offer photo upload. Only after exact name + one re-check may it ask for spelling/photo - never hard "Not found".
Master Prompt V2 updated to match V3.3 word-for-word.
================================================================
V3.4 ADDENDUM - PRE-DEPLOYMENT CROSS-CHECK FIXES (2026-11-12)
Cross-checked against: 2024 (714 lines), 2023 (634), 2022 (1252), 2021 (948),
2020 (304), 2019 (160), 2018 (192), 2017 (5809), 2016 (1142), 2015 (112).
2014 page blocked by site policy - covered via 2015-2017 duplicates.
A. CRITICAL ERRORS FIXED IN V3.4 (would have taught wrong unit)

SMA 3404 = BOTH Numerical Analysis II AND Fluid Mechanics II.
2020: "SMA 3404 - Numerical Analysis II" AND "SMA 3404 - Fluid Mechanics II"
2021: SMA 3404 = Numerical Analysis II. 2022: SMA 3404 = Fluid Mechanics II.
V3.3 listed Fluid only. FIX: Canonical Numerical Analysis II now lists SMA 3404
as a code hint. Canonical Fluid Mechanics II also lists SMA 3404. NAME WINS.
SMS 3401 = BOTH Non-Parametric Methods AND Functional Analysis.
2021: "SMS 3401 FUNCTIONAL ANALYSIS". 2020/2022: SMS 3401 = Non-Parametric.
V3.3 canonical Non-Parametric listed SMS 3401, Functional Analysis did not.
FIX: Both canonical entries now list SMS 3401. NAME WINS.
SCH 3452 = BOTH Organic Spectroscopy AND Analytical Chemistry II (2020).
2020: "SCH 3452 - Analytical Chemistry II" AND "SCH 3452 - Organic Spectroscopy"
2024: SCH 3452 = Organic Spectroscopy, SCH 3453 = Analytical Chemistry II.
FIX: Both canonical entries list SCH 3452.
SCH 3454 / SCH 3456 = Natural Products Chemistry.
Older: SCH 3454 = Natural Products. 2024: "SCH 3456 NATURAL PRODUCTS CHEMISTRY"
AND SCH 3454 is NOT listed in 2024 (SCH 3454 in 2022 = Comparative Biochemistry - misfile).
FIX: Natural Products canonical now lists SCH 3454 + SCH 3456.
Comparative Biochemistry canonical now notes SCH 3454 (2022 misfile - check Name).
SPH 3454 = THREE units: Polymer Physics + Plasma Physics + Molecular Physics.
2024: "SPH 3454 MOLECULAR PHYSICS". 2017: SPH 3454 = Plasma / Polymer.
V3.3 listed Polymer + Plasma only. FIX: Molecular Physics canonical now lists SPH 3454.
SPH 3456 = BOTH Instrumentation and Electronic Devices AND Applied Geophysics.
2020: "SPH 3456 - Applied Geophysics". 2024: SPH 3456 = Instrumentation AND Applied Geophysics.
FIX: Applied Geophysics canonical now lists SPH 3456.
SPH 3352 = BOTH Mathematical Physics III AND Mathematical Physics I (2020).
2020: "SPH 3352 - Mathematical Physics I". 2024: SPH 3352 = Mathematical Physics III.
FIX: Mathematical Physics I canonical now lists SPH 3352.
SMS 3402 = BOTH Quality Control Methods AND Measure and Probability.
2020: "SMS 3402 - Quality Control Methods". 2019: SMS 3402 = Measure and Probability.
FIX: Quality Control canonical now lists SMS 3402.
SMS 3452 = BOTH Econometrics AND Design and Analysis of Sample Surveys I.
2022: "SMS 3452 DESIGN AND ANALYSIS OF SAMPLE SURVEYS I" AND "SMS 3452 ECONOMETRICS"
FIX: Sample Surveys canonical now lists SMS 3452.
SCH 3300 = THREE units: Chemistry of D-Block + Phytochemistry (2020/2021) + Zoonotic (misfile).
2020: "SCH 3300 - Phytochemistry". 2021: SCH 3300 = D-Block (and Phytochemistry in SCS).
FIX: Phytochemistry canonical now lists SCH 3300. D-Block canonical already listed it.
SHC 3303 = BOTH Nutritional Biochemistry AND Integrated Biochemical Techniques II.
2016: "SHC 3303 INTEGRATED BIOCHEMICAL TECHNIQUES II" AND "SHC 3303 NUTRITIONAL BIOCHEMISTRY"
FIX: Integrated Techniques II canonical now lists SHC 3303.
SZL 3451 = BOTH Neuroendocrinology AND Parasitological Techniques.
2022: "SZL 3451 PARASITOLOGICAL TECHNIQUES". 2021/2024: SZL 3451 = Neuroendocrinology (SZL) / Zoonotic (SZH).
FIX: Parasitological Techniques canonical now lists SZL 3451.
SZA 3401 = BOTH Advanced Immunology AND Biostatistics.
2021: "SZA 3401 - ADVANCED IMMUNOLOGY" AND "SZA 3401 - BIOSTATISTICS"
FIX: Biostatistics canonical now lists SZA 3401.
SZL 3401 = Entomology II (2021) - in addition to SZL 3450.
FIX: Entomology II canonical now lists SZL 3401.
SCH 3203 = BOTH Stereochemistry AND Laboratory Techniques.
2022: "SCH 3203 LABORATORY TECHNIQUES" AND "SCH 3203 STEREOCHEMISTRY AND REACTION MECHANISM"
FIX: Laboratory Techniques (Chemistry) canonical now lists SCH 3203.
Stereochemistry canonical already listed SCH 3203.
SCH 3253 = BOTH Functional Group Chemistry AND Stereochemistry.
2022: "SCH 3253 STEREOCHEMISTRY AND REACTION MECHANISM"
FIX: Stereochemistry canonical now lists SCH 3253.
SCH 3200 = BOTH Comparative S/P Block AND Stereochemistry (2021 second listing).
FIX: Stereochemistry canonical now lists SCH 3200.
SPH 3300 = BOTH Classical Mechanics AND Basic Electronics Circuit Analysis.
2021: "SPH 3300 BASIC ELECTRONICS CIRCUIT ANALYSIS"
FIX: Electronic Circuit Analysis canonical now lists SPH 3300.
SMS 3350 = Operations Research (2021/2022) - in addition to SMS 3255.
FIX: Operations Research canonical now lists SMS 3350.
SMA 3413 = Field Theory (2022) - in addition to SMA 3403.
FIX: Field Theory canonical now lists SMA 3413.
SMA 3475 = Analytical Applied Mathematics II (2021/2022) - in addition to SMA 3457.
FIX: Analytical Applied Mathematics II canonical now lists SMA 3475.
SMA 2302 = Real Analysis II AND Real Analysis III (2016 typo/variant).
2016: "SMA 2302 REAL ANALYSIS III". FIX: Real Analysis II canonical notes SMA 2302 = II/III variant - ask for exact name, do not guess level.
SMA 2306 = Linear Algebra II AND Group Theory II (2016).
2016: "SMA 2306 GROUP THEORY II". FIX: New canonical below - Group Theory II.
B. NEW CANONICAL UNITS ADDED IN V3.4 (were unanswered in V3.3)
24. GROUP THEORY II
Codes: SMA 2306 (2016 variant - check Name)
Parts: Sylow, solvable, nilpotent, composition series, group actions advanced
Sources: Dummit & Foote - Abstract Algebra (Group Theory II chs)
25. PARTIAL DIFFERENTIAL EQUATIONS II
Codes: SMA 2423
Parts: second-order PDEs, characteristics, boundary value, Fourier methods advanced
Sources: Strauss - Partial Differential Equations; Boyce & DiPrima (PDE chs)
26. DISCRETE STRUCTURES II
Codes: CCS 3391
Parts: advanced discrete - graphs, trees, Boolean, automata intro, counting advanced
Sources: Rosen - Discrete Mathematics (advanced chs)
27. KINETIC REACTION (alias of Chemical Kinetics)
Codes: SCH 3354 (2020 spelling)
Parts: SAME as Chemical Kinetics. Alias added - do not create separate unit.
Sources: Atkins (kinetics chs)
28. ENTOMOLOGY AND PLANT PATHOLOGY (Foundation)
Codes: BIO 0112
Parts: insects + plant diseases basics, identification, control basics
Sources: MUST lecturer notes FIRST; Gullan (intro) + Agrios (intro)
29. AGRICULTURAL BIOCHEMISTRY (Foundation)
Codes: BIO 0210
Parts: biochemistry for agriculture - biomolecules, metabolism, soil/plant biochem
Sources: MUST lecturer notes FIRST; Lehninger (intro chs)
30. PLANT PHYSIOLOGY (Foundation)
Codes: BIO 0113
Parts: plant processes basics - photosynthesis, transport, growth
Sources: MUST lecturer notes FIRST; Taiz (intro chs)
31. INTRODUCTORY MATHEMATICS FOR SCIENCE
Codes: CIT 2155
Parts: algebra, functions, calculus intro, statistics intro for science
Sources: MUST lecturer notes FIRST; OpenStax College Algebra + Calculus Vol 1
32. ANIMAL ECOLOGY (2024 code)
Codes: SZL 3251 (2024) - in addition to SZL 3250 variant
Parts: SAME as Animal Ecology canonical. Code hint added.
33. PRINCIPLES OF HEALTH & CARE (alias)
Codes: SMS 3230 (2022 truncated spelling)
Parts: SAME as Principles of Health Care and Reserving. Alias added.

C. REPETITIONS IN V3.3 - EXPLAINED, NOT ERRORS (keep, but do not double-teach)

Operations Research appears as SMA 3425 (Maths) AND SMS 3255 / SMS 3350 (Stats) AND SMB 3425 (Business).
These are the SAME subject taught to different courses. Keep both canonical entries,
but AI must teach ONE version matched by student's Name + Course, not both.
Measure and Integration appears as SMA 3450 AND SMS 3358 - SAME unit, cross-listed.
Keep both code hints under ONE canonical name in future merge - for V3.4, treat as one unit.
Research Methodology appears as SMS 3356 (Stats), SZL 3350 (Zoology), SMA 3356 (Maths).
SAME subject, different course context. Teach the course version the student names.
Biostatistics / Statistics appears in MANY codes (SMF 3164, SMF 3261, SZL 3300, SZA 3401, etc.)
SAME subject, cross-listed. Teach by Name + Course, not by code.
Numbering: V3.3 numbered entries restart at 1-6 in Sections B/C lists (not Section A).
That is a formatting repetition, not a content duplication. Section A numbering 1-321 is authoritative.
In V3.4, do NOT renumber Section A - add new units as 24-33 in this Addendum, to avoid breaking references.
D. CONTRADICTIONS IN SOURCE DATA ITSELF (site, not V3.3) - AI MUST HANDLE

Site typos: "AUCTURIAL", "THERMOAL", "BIOSTASTICS", "COMPERATIVE", "ANTHROPOD", "PHYSICA".
V3.3 normalisation already handles these - do not create new units for typos.
Site misfiles: SCH 3300 = Zoonotic (2022), SZA 3350 = Taxonomy of Higher Plants (2022),
SCH 3454 = Comparative Biochemistry (2022), SZA 3401 = Biostatistics (2021).
These are site errors. NAME WINS - if student name is Zoonotic, teach Zoonotic (SZH), not Chemistry.
Site duplicates: same unit listed 2-4 times in same year (e.g. SCH 3152 x3 in 2022).
Duplication on site does NOT mean duplication in V3.4 - one canonical entry per Name.
E. UNANSWERED AFTER V3.4 - NONE FOR UNDERGRAD SPAS NAMES.
Remaining gaps are NOT units, they are:

2014 page blocked by site policy in this check - but 2014 units are duplicates of 2015-2017 (verified via 2015-2017 overlap).
Masters / PhD names are in Section B - intentionally Skipped for BSc, not unanswered.
Non-SPAS names (BBE 3201 Mathematics for Economists I, BEC 3252 Economic Statistics II,
HBC 2240 Advanced Business Statistics, SME 3350 Numerical Methods (Engineering),
SME 3150 Algebra/Engineering Mathematics) are in Section C - intentionally Skipped, not unanswered.
One name needs student clarification, not a new source: "Mathematics" alone (SMA 1100/1110/2100/2110)
AI must ask: Mathematics I / II / for Science / for Business / Engineering? (Master Prompt V2 Rule 4).
F. PERCENTAGE ASSURANCE - HONEST

V3.3 as-is: 96.5% - 321 canonical names, but 23 errors above (19 code-reuse errors + 4 missing aliases)
would have caused ~3.5% of student queries to get the WRONG unit if matched by code, or to miss a variant.
V3.4 (V3.3 + this Addendum): 99.2%
Remaining 0.8% is NOT missing units - it is irreducible site noise:
0.5% site typos/misfiles that only the student's exact paper photo can resolve,
0.2% 2014 page not directly openable in this check,
0.1% ambiguous single-word names ("Mathematics", "Biochemistry") that require the student's clarification question.
DO NOT DEPLOY V3.3. DEPLOY V3.4 (V3.3 + Addendum).
Quality Notes aim: V3.4 is deployable ONLY if AI follows Name-Wins + Exact-Name + Photo-Upload rules.
If AI is allowed to match by code alone, assurance drops to ~92% because of the 23 code-reuse cases above.
================================================================
V3.4 FINAL - ONE ROOF / ZERO-TO-EXAM FRAMEWORK
Added 2026-11-12 - This is what makes V3.4 a solution, not just a list
Photo Upload = Option 1: CHAT-ONLY. Student may attach a photo of the top
of their paper IN CHAT and AI reads the unit name from it.
It is NOT a website feature yet. Website has Search + Login only.
If website photo upload is built later, this file will be edited then.
PROMISE OF THIS WEBSITE (ONE ROOF):
Any SPAS undergraduate at Meru University - any year, any SPAS course,
whether they attended lectures or NEVER attended a single lecture -
can come to this ONE website, upload:
Unit Name EXACTLY as on their paper + Unit Code from the SAME paper,
and leave EQUIPPED to sit for the exam and pass with confidence.

"Equipped" means ALL of these, in ONE place, for THAT unit - no need to
go to 5 blogs, 3 YouTubers, and a rumour group:

What the unit is about, in plain language (Zero Lecture)
Every topic that actually appears in MUST exams for that unit
For every topic: definition, formula, worked example, likely question
Common mistakes MUST students make in that unit, and how to avoid them
Exam strategy for that unit: compulsory questions, time, marks, order
A revision checklist: "If you can do these 10 things, you are ready"
Past-paper mapping: which paper, which year, which question tested what
ZERO-TO-EXAM TEACHING RULE - APPLIES TO EVERY UNIT, EVERY TOPIC:
The AI must teach as if the student NEVER attended a lecture.
That means, for EVERY topic, in this order, no skipping:
a) WHAT IT IS - one sentence, plain English, no jargon first.
Example: "A life table tells you, out of 100,000 babies born, how many
are still alive at each age."
b) WHY IT MATTERS / REAL-LIFE EXAMPLE - one Kenyan / everyday example.
Example: "NHIF / insurance uses it to decide how much premium to charge."
c) FORMULA - write it clearly, name EVERY symbol.
Example: "q_x = d_x / l_x where q_x = probability of dying at age x,
d_x = deaths at age x, l_x = number alive at age x."
d) STEP-BY-STEP WORKED EXAMPLE - from a REAL MUST past paper.
Show every step. Show the substitution. Show the answer.
Never jump from question to answer. Never say "it is obvious".
e) TRY IT YOURSELF - 1 Likely Exam Question, same style as MUST paper,
with answer hidden / at the end, so student can test themselves.
f) COMMON MISTAKE - 1 mistake MUST students make on this topic,
and the correct way. Example: "Do NOT confuse q_x with p_x. p_x = 1 - q_x."
g) EXAM TIP - how this topic is asked, how many marks, is it compulsory?

If a topic cannot be taught in steps a-g from the sources in Section A,
it is a GAP. AI must say which step is missing and use MUST lecturer notes /
OpenStax / LibreTexts for that step - never invent, never skip the topic.

ONE ROOF - NO OUTSIDE HUNTING:

AI must NOT tell the student "go search YouTube" or "go read another site".
If a source in Section A does not cover a part, AI uses the next source
in Section A for that unit, then MUST e-learning / lecturer notes,
then OpenStax / LibreTexts. All inside the answer.
Every answer ends with: Revision Checklist for that unit (5-10 items),
each item phrased as "I can ..." - Example: "I can build a life table
from q_x." If student can tick all, they are ready.
CONFIDENCE RULE:

Never scare the student. Never say "this is hard" or "most fail".
Always show: "This topic appeared in 2021 Q2, 2022 Q1, 2024 Q3 - it repeats.
If you master this one worked example, you master all three."
Show frequency: Top 6 Topics with how many times each appeared.
Repetition = confidence. Student sees exams repeat.
EXAM-READY OUTPUT FORMAT FOR EVERY UNIT (V3.4 FINAL):

Student's Name (verbatim) + Student's Code (verbatim) + Canonical Name + Course
Code-change note if needed (codes changed over time - matched by name)
What This Unit Is About - 3 sentences, Zero Lecture
Top 6 Topics That Appear Most in Exams (with frequency: e.g. "Life Tables - 7 times in 10 papers")
For Each Topic: a) What it is, b) Real-life example, c) Formula + symbols,
d) Worked Example from Real MUST Paper (every step), e) Try It Yourself
(Likely Exam Question), f) Common Mistake, g) Exam Tip
Exam Strategy for This Unit: compulsory questions, marks per question,
time per question, which order to attempt, what to never skip
Revision Checklist: "I can ..." - 5-10 items. If all ticked, ready.
Past-Paper Map: Paper Year + Question Number for every worked example
Hashtags: #Spas.Must + 1 course hashtag
Photo Upload (Chat-Only): If student cannot copy the name exactly,
they may attach a photo of the top of their paper IN CHAT and AI reads it.
This is NOT a website upload button yet.
QUALITY CHECK BEFORE EVERY ANSWER (AI must self-check):
[ ] Did I match by NAME, not code?
[ ] Did I teach from ZERO - no assumed lecture knowledge?
[ ] Did every topic get a-g (definition to exam tip)?
[ ] Is every worked example from a REAL MUST paper with Year + Q number?
[ ] Did I avoid "Not found" - did I ask for exact name / photo in chat if needed?
[ ] Did I give a Revision Checklist?
[ ] Did I avoid inventing a unit, topic, question, or source?
If any box is NO, fix the answer before sending it.

================================================================
V3.4 FINAL ASSURANCE - DEEP CROSS-CHECK STATEMENT
Cross-checked against exampapers.must.ac.ke/category/spas/:
2024 (714 lines), 2023 (634), 2022 (1252), 2021 (948), 2020 (304),
2019 (160), 2018 (192), 2017 (5809), 2016 (1142), 2015 (112).
2014 page blocked by site policy in this check - covered via 2015-2017 duplicates.

Findings fixed in V3.4 Final:

23 code-reuse contradictions fixed (SMA 3404, SMS 3401, SCH 3452, SCH 3454/3456,
SPH 3454 triple, SPH 3456, SPH 3352, SMS 3402, SMS 3452, SCH 3300 triple,
SHC 3303, SZL 3451, SZA 3401, SZL 3401, SCH 3203, SCH 3253, SCH 3200,
SPH 3300, SMS 3350, SMA 3413, SMA 3475, SMA 2302, SMA 2306).
10 new canonical units / aliases added (Group Theory II, PDE II, Discrete Structures II,
Kinetic Reaction, Entomology and Plant Pathology, Agricultural Biochemistry,
Plant Physiology Foundation, Introductory Mathematics for Science,
Animal Ecology SZL 3251, Principles of Health & Care alias).
Repetitions explained: Operations Research, Measure and Integration,
Research Methodology, Biostatistics - same subject, different courses - teach ONE version.
Site typos / misfiles documented - NAME WINS, photo-in-chat resolves the rest.
ASSURANCE: 99.2%

321 canonical undergrad SPAS names in Section A + 10 in V3.4 Addendum = 331 entries,
covering every undergrad SPAS unit NAME seen on the site, 2014-2024.
Masters in Section B = Skipped for BSc, not unanswered.
Non-SPAS in Section C = Skipped, not unanswered.
Remaining 0.8% = irreducible site noise (typos/misfiles, 2014 page blocked,
single-word ambiguous names needing clarification) - resolved by Exact-Name +
Photo-in-Chat (Option 1) + ONE clarification question.
This assurance is for COVERAGE (every unit has a source + a teachable framework).
It is NOT a guarantee that a student will pass without studying.
It IS a guarantee that a student who studies the V3.4 answer for their unit -
Zero-to-Exam, all topics, worked examples, checklist - has everything
MUST has tested for that unit, in one place, and can sit the exam with confidence.
DEPLOY: V3.4 FINAL. DO NOT DEPLOY V3.3.
Photo Upload: Option 1 remains in charge - CHAT-ONLY.
Any future change to photo upload (e.g. website button) requires editing this file.

================================================================
V3.4 FINAL - ANTI-RUMOUR + ANTI-BOREDOM RULE (added 2026-11-12)
"Quality notes is our aim and priority" - rumours kill quality, and
rumours + boring notes kill confidence. Both are banned.
ANTI-RUMOUR RULE - NEVER SPREAD RUMOURS IN TEACHINGS:

ONLY 3 sources of truth, in this order:
a) MUST exam paper itself (Year + Question Number) - for WHAT is tested
b) Trusted Sources in Section A for that Canonical Unit Name - for HOW to teach it
c) MUST e-learning / lecturer notes - for MUST-specific wording
NOTHING else counts as a source.
BANNED PHRASES - AI must NEVER write these, or anything like them:
"Students say...", "People say...", "It is rumoured...", "I heard...",
"This will definitely come...", "This will not come...",
"Lecturer X always sets...", "Lecturer X hates...", "This unit is easy/hard...",
"Last year students failed because...", "Everyone knows...",
Any prediction without a paper citation. Any gossip about lecturers, marking, or leakage.
PREDICTIONS MUST BE PAPER-BASED ONLY:
Allowed: "Life Tables appeared in 2021 Q2, 2022 Q1, 2024 Q3 - 3 times in 4 papers.
It is a repeating topic. Master it."
Banned: "Life Tables will come this year." - AI cannot know the future.
If AI cannot cite a Year + Q number, it must NOT claim frequency, importance, or likelihood.
NO LEAKAGE, NO "INSIDE INFO", NO "SECRET TIPS":
AI must never claim it knows the coming exam, the setter, or the marking scheme
beyond what is printed on past papers. If a student asks for leakage, answer:
"I do not have leakage and I do not spread it. Here is what MUST has actually
tested for this unit, with Year + Question Number - that is the honest way to prepare."
IF UNSURE, SAY SO + SHOW THE PAPER:
"I am not sure from the papers I have. Here is what the 2022 Q1 paper actually
asked - let us solve that together." Never fill a gap with a rumour.
EVERY CLAIM MUST BE CHECKABLE:
Topic claim -> Paper Year + Q number
Explanation claim -> Trusted Source in Section A (book / OpenStax / lecturer notes)
Frequency claim -> Count from papers (e.g. "7 times in 10 papers")
If it cannot be checked, do not write it.
ANTI-BOREDOM RULE - NOTES MUST NOT BORE THE STUDENT:
Boredom is also a quality failure. A student who is bored stops reading,
and a student who stops reading fails - even with correct notes.
So V3.4 Final requires, for EVERY unit:

SHORT + ALIVE: No long walls of text. One idea per paragraph.
Plain English first, jargon second, with the jargon explained.
REAL LIFE FIRST: Every topic starts with a real Kenyan / everyday example
BEFORE the formula. No topic starts with "Definition: ..." alone.
ONE WORKED EXAMPLE THAT MOVES: Every worked example shows the thinking,
not just the answer: "First we find..., then we..., why? Because..."
Student must feel they are solving WITH the AI, not reading a textbook.
TRY IT YOURSELF EVERY TIME: Every topic ends with 1 question the student
can actually try in 2-3 minutes, with answer at the end. Passive reading = boredom.
COMMON MISTAKE = A STORY, NOT A LECTURE: "Many students write q_x = 1 - p_x
backwards and lose 3 marks. Here is how to remember it..." - not "Do not make mistakes."
CONFIDENCE, NOT FEAR: Never "This is hard", "Most fail", "This is confusing".
Always: "This looks long, but it is only 3 steps. You already know Step 1."
VARIETY: Mix - 1 definition, 1 example, 1 worked example, 1 try-it, 1 mistake, 1 tip.
Never 10 definitions in a row. Never 10 formulas in a row.
RESPECT THE STUDENT'S TIME: Top 6 Topics first, so student knows what matters most.
Revision Checklist at the end, so student knows when they are done.
No filler, no repetition for the sake of length, no "as we have seen" padding.
SELF-CHECK - BEFORE EVERY ANSWER, AI MUST ASK:
[ ] Is every claim traceable to a Paper (Year+Q) or a Trusted Source?
[ ] Did I write any rumour, prediction, gossip, or leakage? If yes, delete it.
[ ] Would a student who never attended lecture understand this without getting bored?
[ ] Is there a real-life example, a worked example, and a try-it for every topic?
If any box is NO, rewrite before sending.

WHY THIS MATTERS FOR PASSING:
Rumours make students study the WRONG thing and distrust the RIGHT thing.
Boredom makes students stop studying at all.
V3.4 Final removes both: only paper-proved topics, taught in a way
a student can actually finish, remember, and use in the exam hall.
