---
clause: "2.5.12"
title: "Non-Linear Static Analysis (NSA)"
chapter: "2"
chapter_title: "Loads on Buildings and Structures"
related_tables: []
related_diagrams: []
related_flowcharts: []
---
# Section 2.5.12: Non-Linear Static Analysis (NSA)

2.5.12 Non-Linear Static Analysis (NSA)
Nonlinear static analysis (NSA), also popularly known as pushover analysis, is a
simplified method of directly evaluating nonlinear response of structures to
strong earthquake ground shaking. It is an alternative to the more complex
nonlinear time history analysis (NTHA). The building is subjected to
monotonically increasing static horizontal loads under constant gravity load.
2.5.12.1
Modeling (NSA)
A mathematical model of the structure shall be constructed to represent the
spatial distribution of mass and stiffness of the structural system considering
the effects of element nonlinearity for deformation levels that exceed the
proportional limit. P-Delta effects shall also be included in the analysis.
For regular structures with independent orthogonal seismic-force-resisting
systems, independent two-dimensional models may be used to represent each
system. For structures having plan irregularities or structures without
independent orthogonal systems, a three-dimensional model incorporating a
minimum of three degrees of freedom for each level of the structure, consisting
of translation in two orthogonal plan directions and torsional rotation about the
vertical axis, shall be used. Where the diaphragms are not rigid compared to the
vertical elements of the seismic-force-resisting system, the model should
include representation of the diaphragm flexibility.
Unless analysis indicates that an element remains elastic, a nonlinear force
deformation model shall be used to represent the stiffness of the element before
onset of yield, the yield strength, and the stiffness properties of the element
after yield at various levels of deformation. Strengths of elements shall not
Chapter 2
exceed expected values considering material over-strength and strain
hardening. The properties of elements and components after yielding shall
account for strength and stiffness degradation due to softening, buckling, or
fracture as indicated by principles of mechanics or test data.
A control point shall be selected for the model. For normal buildings, the control
point shall be at the center of mass of the highest level (roof) of the structure.
2.5.12.2
Analysis procedure (NSA)
The lateral forces shall be applied at the center of mass of each level and shall be
proportional to the distribution obtained from a modal analysis for the
fundamental mode of response in the direction under consideration. The lateral
loads shall be increased incrementally in a monotonic manner.
At the  d"3 increment of lateral loading, the total lateral force applied to the
model shall be characterized by the term . The incremental increases in
applied lateral force should be in steps that are sufficiently small to permit
significant changes in individual element behavior (such as yielding, buckling or
failure) to be detected. The first increment in lateral loading shall result in linear
elastic behavior. At each loading step, the total applied lateral force,  the
lateral displacement of the control point,  and the forces and deformations in
each element shall be recorded. The analysis shall be continued until the
displacement of the control point is at least 150 percent of the target
displacement determined in accordance with Sec.2.5.12.3. The structure shall be
designed so that the total applied lateral force does not decrease in any load
increment for control point displacements less than or equal to 125 percent of
the target displacement.
2.5.12.3
Effective period and target displacement (NSA)
A bilinear curve shall be fitted to the capacity curve, such that the first segment
of the bilinear curve coincides with the capacity curve at 60 percent of the
effective yield strength, the second segment coincides with the capacity curve at
the target displacement, and the area under the bilinear curve equals the area
under the capacity curve, between the origin and the target displacement. The
effective yield strength, H corresponds to the total applied lateral force at the
intersection of the two line segments. The effective yield displacement, H
corresponds to the control point displacement at the intersection of the two line
segments. The effective fundamental period, E< of the structure in the direction
under consideration shall be determined using Eq. 6.2.51 as follows:
y
y
e
V
V
T
T

1
1
1

(6.2.51)
Chapter 2
Where, 1, 1, and E1 are determined for the first increment of lateral load. The
target displacement of the control point, e shall be determined as follows:
g
T
S
C
C
e
a
T
2
1
0
2 








(6.2.52)
Where, the spectral acceleration, Sa, is determined at the effective fundamental
period, Te, using Eq. 6.2.34, g is the acceleration due to gravity. The coefficient Co
shall be calculated as :




n
i
i
i
n
i
i
i
o
w
w
C
1
2
1


(6.2.53)
Where,
[ = the portion of the seismic weight, W, at level i, and
k = the amplitude of the shape vector at level i.
Where the effective fundamental period, Te, is greater than TC (defined in Sec.
2.5.4.3), the coefficient C1 shall be taken as 1.0. Otherwise, the value of the
coefficient C1 shall be calculated as follows:











e
s
d
d
T
T
R
R
C
1
1
1
1
(6.2.54)
Where, Rd is given as follows:
W
V
S
R
y
a
d 
(6.2.55)
2.5.12.4
Structure member design (NSA)
For each nonlinear static analysis the design response parameters, including the
individual member forces and member deformations shall be taken as the values
obtained from the analysis at the step at which the target displacement is reached.
Chapter 2
The adequacy of individual members and their connections to withstand the
member forces and member deformations shall be evaluated based on
laboratory test data for similar components. The effects of gravity and other
loads on member deformation capacity shall be considered in these evaluations.
The deformation of a member supporting gravity loads shall not exceed (i) two-
thirds of the deformation that results in loss of ability to support gravity loads,
and (ii) two-thirds of the deformation at which the member strength has
deteriorated to less than 70 percent of the peak strength of the component
model. The deformation of a member not required for gravity load support shall
not exceed two-thirds of the value at which member strength has deteriorated
to less than 70 percent of the peak strength of the component model.