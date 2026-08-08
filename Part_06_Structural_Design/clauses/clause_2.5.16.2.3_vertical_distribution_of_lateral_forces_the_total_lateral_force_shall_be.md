---
clause: "2.5.16.2.3"
title: "Vertical distribution of lateral forces: The total lateral force shall be"
chapter: "2"
chapter_title: "Loads on Buildings and Structures"
related_tables: []
related_diagrams: []
related_flowcharts: ["../mmd/flow_06_proc_f05ea2.mmd"]
---
# Section 2.5.16.2.3: Vertical distribution of lateral forces: The total lateral force shall be

2.5.16.2.3 Vertical distribution of lateral forces: The total lateral force shall be
distributed over the height of the structure above the isolation interface in
accordance with Eq. 6.2.68 as follows:



n
i
i
i
x
x
s
x
h
w
h
w
V
F
1
(6.2.68)
Chapter 2
Where:
 5
Total seismic lateral design force on elements above the
isolation system.
ℎ, ℎ 5
Height above the base, to Level i or Level x, respectively.
[, [ 5  Portion of W that is located at or assigned to Level i or Level
x, respectively.
At each Level x the force, & shall be applied over the area of the structure in
accordance with the distribution of mass at the level. Stresses in each structural
element shall be determined by applying the lateral forces, & at all levels above the
base to an analytical model.
2.5.16.2.4
Storey drift:  The storey drift shall be calculated as in Sec 2.5.7.7 except
that Cd for the isolated structure shall be taken equal to RI and importance factor
equal to 1.0. The maximum storey drift of the structure above the isolation system
shall not exceed 0.015hsx.
2.5.16.3
Dynamic analysis
Response spectrum analysis may be conducted if the behavior of the isolation system
can be considered as equivalent linear. Otherwise, non-linear time history analysis
shall be used where the true non-linear behaviour of the isolation system can be
modeled.  The mathematical models of the isolated structure including the isolation
system shall be along guidelines given in Sections 2.5.9.1 and 2.5.11.1, and other
requirements given in Sec 2.5.16.
The isolation system shall be modeled using deformational characteristics developed
and verified by testing. The structure model shall account for: (i) spatial distribution
of isolator units; (ii) consideration of translation in both horizontal directions, and
torsion of the structure above the isolation interface considering the most
disadvantageous location of eccentric mass; (iii) overturning/uplift forces on
individual isolator units; and (iv) effects of vertical load, bilateral load, and the rate
of loading if the force-deflection properties of the isolation system are dependent on
such attributes.
A linear elastic model of the isolated structure (above isolation system) may be used
provided that: (i) stiffness properties assumed for the nonlinear components of the
isolation system are based on the maximum effective stiffness of the isolation
system, and (ii) all elements of the seismic-force-resisting system of the structure
above the isolation system behave linearly.
Chapter 2
2.5.16.3.1
Response Spectrum Analysis:  Response spectrum analysis shall be
performed using a modal damping value for the fundamental mode in the direction
of interest not greater than the effective damping of the isolation system or 30
percent of critical, whichever is less. Modal damping values for higher modes shall
be selected consistent with those that would be appropriate for response spectrum
analysis of the structure above the isolation system assuming a fixed base.
Response spectrum analysis used to determine the total design displacement and the
total maximum displacement shall include simultaneous excitation of the model by
100 percent of the ground motion in the critical direction and 30 percent of the
ground motion in the perpendicular, horizontal direction. The design basis
earthquake shall be used for the design displacement, while the maximum
considered earthquake shall be used for the maximum displacement. The maximum
displacement of the isolation system shall be calculated as the vectorial sum of the
two orthogonal displacements.
For the design displacement, structures that do not require site-specific ground
motion evaluation, shall be analyzed using the design acceleration response spectrum
in accordance with Sec 2.5.4.3. The maximum design spectrum to be used for the
maximum considered earthquake shall not be less than 1.5 times the design
acceleration response spectrum.
The response spectrum procedure is based on an equivalent linear model, where the
effective stiffness and effective damping is a function of the displacement, this
formulation is thus an iterative process.  The effective stiffness must be estimated,
based on assumed displacement, and then adjusted till obtained displacement agree
with assumed displacement.
The design shear at any story shall not be less than the story shear resulting from
application of the story forces calculated using Eq. 6.2.68 with a value of  equal to
the base shear obtained from the response spectrum analysis in the direction of
interest.
2.5.16.3.2
Nonlinear Time History Analysis: Where a time history analysis
procedure is performed, not fewer than three appropriate ground motions shall be
used in the analysis as described below.
Chapter 2
Ground motions shall consist of pairs of appropriate horizontal ground motion
acceleration components that shall be selected and scaled from individual recorded
events. Appropriate ground motions shall be selected from events having
magnitudes, fault distance, and source mechanisms that are consistent with those that
control the maximum considered earthquake. If required number of recorded ground
motion pairs are not available, appropriate simulated ground motion pairs shall be
used to make up the total number required. For each pair of horizontal ground-
motion components, a square root of the sum of the squares (SRSS) spectrum shall
be constructed by taking the SRSS of the 5 percent damped response spectra for the
scaled components (where an identical scale factor is applied to both components of
a pair). Each pair of motions shall be scaled such that for each period between 0.5TD
and 1.25TM (where TD and TM are defined in Sec 2.5.16.2.1) the average of the SRSS
spectra from all horizontal component pairs does not fall below 1.3 times the
corresponding ordinate of the design response spectrum (Sec 2.5.16.4), by more than
10 percent.
Each pair of ground motion components shall be applied simultaneously to the model
considering the most disadvantageous location of eccentric mass. The maximum
displacement of the isolation system shall be calculated from the vectorial sum of the
two orthogonal displacements at each time step.
The parameters of interest shall be calculated for each ground motion used for the
time history analysis. If at least seven ground motions are used for the time history
analysis, the average value of the response parameter of interest is permitted to be
used for design. If fewer than seven ground motions are analyzed, the maximum
value of the response parameter of interest shall be used for design.
2.5.16.3.3
Storey drift: Maximum story drift corresponding to the design lateral
force including displacement due to vertical deformation of the isolation system shall
not exceed the following limits:
1. The maximum story drift of the structure above the isolation system
calculated by response spectrum analysis shall not exceed 0.015ℎ.
2. The maximum story drift of the structure above the isolation system
calculated by nonlinear time history analysis shall not exceed 0.020ℎ.
The storey drift shall be calculated as in Sec 2.5.7.7 except that Cd for the isolated
structure shall be taken equal to RI and importance factor equal to 1.0.
Chapter 2
2.5.16.4
Testing
The deformation characteristics and damping values of the isolation system used in
the design and analysis of seismically isolated structures shall be based on test results
of isolator units. The tests are for establishing and validating the design properties of
the isolation system and shall not be considered as satisfying the manufacturing
quality control tests.
The following sequence of tests shall be performed on isolator units for the
prescribed number of cycles at a vertical load equal to the average dead load plus
one-half the effects due to live load on all isolator units of a common type and size:
(1)
Twenty fully reversed cycles of loading at a lateral force corresponding to
the wind design force.
(2)
Three fully reversed cycles of loading at each of the following increments
of the total design displacement-0.25DD, 0.5DD, 1.0DD, and 1.0DM where
DD and DM are as determined in Sec 2.5.16.2.1.
(3)
Three fully reversed cycles of loading at the total maximum
displacement, 1.0DTM.
(4)
Not less than ten fully reversed cycles of loading at 1.0 times the total
design displacement, 1.0DTD.
For each cycle of each test, the force-deflection and hysteretic behavior of each
isolator unit shall be recorded. The effective stiffness is obtained as the secant value
of stiffness at design displacement while the effective damping is determined from
the area of hysteretic loop at the design displacement.
2.5.16.5
Design review
A design review of the isolation system and related test programs shall be performed
by an independent team of design professionals experienced in seismic analysis
methods and the application of seismic isolation. Isolation system design review shall
include, but need not be limited to, the following:
(1)
Review of site-specific seismic criteria including the development of site-
specific spectra and ground motion time histories and all other design
criteria developed specifically for the project;
Chapter 2
(2)
Review of the preliminary design including the determination of the total
design displacement of the isolation system and the lateral force design
level;
(3)
Overview and observation of prototype (isolator unit) testing
(4)
Review of the final design of the entire structural system and all
supporting analyses; and
(5)
Review of the isolation system quality control testing program.