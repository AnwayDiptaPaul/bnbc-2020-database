---
clause: "2.5.11"
title: "Non-Linear Time History Analysis (NTHA)"
chapter: "2"
chapter_title: "Loads on Buildings and Structures"
related_tables: []
related_diagrams: []
related_flowcharts: ["../mmd/flow_06_proc_835e30.mmd"]
---
# Section 2.5.11: Non-Linear Time History Analysis (NTHA)

2.5.11 Non-Linear Time History Analysis (NTHA)
Nonlinear time history analysis (NTHA) shall consist of analysis of a
mathematical model of the structure which incorporates the nonlinear
hysteretic behavior of the structure’s components to determine its response,
through methods of numerical integration, to ground acceleration time histories
compatible with the design response spectrum for the site. The analysis shall be
performed in accordance with the requirements of this Section. For the
purposes of analysis, the structure shall be permitted to be considered to be
fixed at the base or, alternatively, it shall be permitted to use realistic
assumptions with regard to the stiffness of foundations. The acceleration time
history (ground motion) is applied at the base of the structure. The advantage of
this procedure is that actual time dependent behavior of the structural response
considering inelastic deformations in the structure can be obtained.
2.5.11.1
Modeling (NTHA)
A mathematical model of the structure shall be constructed that represents the
spatial distribution of mass throughout the structure. The hysteretic behavior of
elements shall be modeled consistent with suitable laboratory test data and
shall account for all significant yielding, strength degradation, stiffness
degradation, and hysteretic pinching indicated by such test data. Strength of
elements shall be based on expected values considering material over-strength,
strain hardening, and hysteretic strength degradation. As a minimum, a bilinear
force deformation relationship should be used at the element level. In
reinforced concrete and masonry buildings, the elastic stiffness should
correspond to that of cracked sections. Linear properties, consistent with the
provisions of Chapter 5 shall be permitted to be used for those elements
demonstrated by the analysis to remain within their linear range of response.
The structure shall be assumed to have a fixed base or, alternatively, it shall be
permitted to use realistic assumptions with regard to the stiffness and load
carrying characteristics of the foundations consistent with site-specific soils
data and rational principles of engineering mechanics.
For regular structures with independent orthogonal seismic-force-resisting
systems, independent two dimensional models shall be permitted to be
constructed to represent each system. For structures having plan irregularity or
structures without independent orthogonal systems, a three-dimensional model
incorporating a minimum of three dynamic degrees of freedom consisting of
Chapter 2
translation in two orthogonal plan directions and torsional rotation about the
vertical axis at each level of the structure shall be used. Where the diaphragms
are not rigid compared to the vertical elements of the lateral-force-resisting
system, the model shall include representation of the diaphragm’s flexibility and
such additional dynamic degrees of freedom as are required to account for the
participation of the diaphragm in the structure’s dynamic response.
2.5.11.2
Ground motion (NTHA)
The actual time-dependent inelastic deformation of the structure is modeled.
For inelastic analysis method, the real design acceleration response spectrum
(Sec 2.5.4.3) is obtained using Eq. 6.2.34 with R51 and I51.  The real design
acceleration response spectrum is the true representation of the expected
ground motion (design basis earthquake) including local soil effects and
corresponds to a peak ground acceleration (PGA) value of

2 KC.
At least three appropriate acceleration time histories shall be used in the
analysis. Ground motion shall conform to the requirements of this Section.
Two-dimensional analysis
Where two-dimensional analyses are performed, each ground motion shall
consist of a horizontal acceleration time history selected from an actual
recorded event. Appropriate acceleration histories shall be obtained from
records of events having magnitudes, fault distance, and source mechanisms
that are consistent with those that control the maximum considered earthquake.
Where the required number of appropriate ground motion records are not
available, appropriate simulated ground motion time histories shall be used to
make up the total number required. The ground motions shall be scaled such
that for each period between 0.2T and 1.5T (where T is the natural period of the
structure in the fundamental mode for the direction considered) the average of
the five-percent-damped response spectra for each acceleration time history is
not less than the corresponding ordinate of the real design acceleration
response spectrum, as defined here.
Three-dimensional analysis
Where three-dimensional analysis is performed, ground motions shall consist of
pairs of appropriate horizontal ground motion acceleration time histories (in
two orthogonal horizontal directions) that shall be selected and scaled from
individual recorded events. Appropriate ground motions shall be selected from
Chapter 2
events having magnitudes, fault distance, and source mechanisms that are
consistent with those that control the maximum considered earthquake. Where
the required number of recorded ground motion pairs are not available,
appropriate simulated ground motion pairs shall be used to make up the total
number required. For each pair of horizontal ground motion components, an
SRSS spectrum shall be constructed by taking the square root of the sum of the
squares of the five-percent-damped response spectra for the components
(where an identical scale factor is applied to both components of a pair). Each
pair of motions shall be scaled such that for each period between 0.2T and 1.5T
(where T is the natural period of the fundamental mode of the structure) the
average of the SRSS spectra from all horizontal component pairs is not less than
1.3 times the corresponding ordinate of the real design acceleration response
spectrum.
2.5.11.3
Structure response (NTHA)
For each scaled acceleration time history, the maximum values of base shear
and other structure response quantities shall be obtained from the nonlinear
time history analysis. For three dimensional analysis, orthogonal pair of scaled
motions are applied simultaneously. If number of earthquake records (or pairs)
used in the analysis is less than seven, the maximum structural response
obtained corresponding to different earthquake records shall be considered as
the design value. If the number is at least seven, then the average of maximum
structural responses for different earthquake records shall be considered as the
design value. Since real expected earthquake motion input and model
incorporating real nonlinear behavior of the structure is used, the results as
obtained are directly used (no scaling as in LTHA or RSA is required) for
interpretation and design.
2.5.11.4
Structure member design (NTHA)
The adequacy of individual members and their connections to withstand the
design deformations predicted by the analyses shall be evaluated based on
laboratory test data for similar components. The effects of gravity and other
loads on member deformation capacity shall be considered in these evaluations.
Member deformation shall not exceed two thirds of the smaller of: the value that
results in loss of ability to carry gravity loads or the value at which member
strength has deteriorated to less than 67 percent of peak strength.
Chapter 2
2.5.11.5
Design review (NTHA)
Special care and expertise is needed in the use of nonlinear dynamic analysis
based design. Checking of the design by competent third party is recommended.
A review of the design of the seismic-force-resisting system and the supporting
structural analyses shall be performed by an independent team consisting of
design professionals with experience in seismic analysis methods and the
theory and application of nonlinear seismic analysis and structural behavior
under extreme cyclic loads. The design review shall include the following: (i)
Review of development of ground motion time histories (ii) Review of
acceptance criteria (including laboratory test data) used to demonstrate the
adequacy of structural elements and systems to withstand the calculated force
and deformation demands (iii) Review of structural design.