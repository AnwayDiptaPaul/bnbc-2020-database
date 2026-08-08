---
clause: "10.3.2.1.2"
title: "Second-order analysis by amplified first-order elastic analysis"
chapter: "10"
chapter_title: "Steel Structures"
related_tables: []
related_diagrams: []
related_flowcharts: ["../mmd/flow_06_proc_1df2c6.mmd"]
---
# Section 10.3.2.1.2: Second-order analysis by amplified first-order elastic analysis

10.3.2.1.2 Second-order analysis by amplified first-order elastic analysis
The following is an approximate second-order analysis procedure for calculating the
required flexural and axial strengths in members of lateral load resisting systems. The
required second-order flexural strength,, and axial strength, H, shall be determined as
follows:
(6.10.3a)
(6.10.3b)
Chapter 10
Where,
 =
@
E¡M¢ M£¤
⁄
œ 1
(6.10.4)
For members subjected to axial compression, B1 may be calculated based on first-order
For members in which B1 ≤ 1.05, it is conservative to amplify the sum of the non-sway and
sway moments (as obtained, for instance, by a first-order elastic analysis) by the B2
amplifier, in other words, Mr = B2 ( Mnt + Mlt ).
 =

œ 1
(6.10.5)
And,
i  = 1.00(LRFD)            α = 1.60 (ASD)
 = required second-order flexural strength using LRFD or ASD load
combinations,N-mm
no lateral translation of the frame, N-mm
translation of the frame only, N-mm
$$H= required second-order axial strength using LRFD or ASD load combinations, N$$
is no lateral translation of the frame, N
combinations, including gravity column loads, N
translation of the frame only, N
$$Cm = a coefficient assuming no lateral translation of the frame whose value shall be$$
taken as follows:
For beam-columns not subject to transverse loading between supports in the plane of
bending,
 = 0.6 −0.4( 
⁄
)
(6.10.6)
Chapter 10
Where, M1 and M2, calculated from a first-order analysis, are the smaller and larger
moments, respectively, at the ends of that portion of the member unbraced in the plane of
bending under consideration. M1 / M2 is positive when the member is bent in reverse
curvature, negative when bent in single curvature.
For beam-columns subjected to transverse loading between supports, the value of Cm shall
be determined either by analysis or conservatively taken as 1.0 for all cases.
Pe1= elastic critical buckling resistance of the member in the plane of bending, calculated
based on the assumption of zero sidesway, N
H =
«©'L
(¬¤))©
(6.10.7)
$$∑H= elastic critical buckling resistance for the story determined by sideway buckling$$
analysis, N
For moment frames, where sidesway buckling effective length factors K2 are determined
for the columns, it is permitted to calculate the elastic story sidesway buckling resistance as
$$∑H = ∑«©'L$$
(¬©))©
(6.10.8a)
For all types of lateral load resisting systems, it is permitted to use
$$∑H = J"$$
∑.)
-®
(6.10.8b)
Where,
= modulus of elasticity of steel = 200 000 MPa
$$J = 1.0 for braced-frame systems;$$
= 0.85 for moment-frame and combined systems, unless a larger value is justified
by analysis
:
= moment of inertia in the plane of bending, mm4
=
= story height, mm
< = effective length factor in the plane of bending, calculated based on the
assumption of no lateral translation, set equal to 1.0 unless analysis indicates that a
smaller value may be used
Chapter 10
< = effective length factor in the plane of bending, calculated based on a sideway
buckling analysis
Δ. = first-order interstory drift due to lateral forces, mm. Where Δ. varies over the
plan area of the structure, Δ. shall be the average drift weighted in proportion to
vertical load or, alternatively, the maximum drift.
$$∑2= story shear produced by the lateral forces used to computeΔ., N$$
10.3.2.2
Design requirements
These requirements apply to all types of braced, moment, and combined framing systems.
Where the ratio of second-order drift to first-order drift is equal to or less than 1.5, the
required strengths of members, connections and other elements shall be determined by one
of the methods specified in Sections 10.3.2.2.1 or 10.3.2.2.2, or by the Direct Analysis
Method of Sec 10.14. Where the ratio of second-order drift to first-order drift is greater
than 1.5, the required strengths shall be determined by the Direct Analysis Method of Sec
10.14.
For the methods specified in Sections 10.3.2.2.1 or 10.3.2.2.2:
Analyses shall be conducted according to the design and loading requirements specified in
either Section 10.2.3.3 (LRFD) or Section 10.2.3.4 (ASD).
The structure shall be analyzed using the nominal geometry and the nominal elastic
stiffness for all elements.