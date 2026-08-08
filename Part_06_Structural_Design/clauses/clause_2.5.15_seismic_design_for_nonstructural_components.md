---
clause: "2.5.15"
title: "Seismic Design For Nonstructural Components"
chapter: "2"
chapter_title: "Loads on Buildings and Structures"
related_tables: ["../json/table_06_6.2.22.json"]
related_diagrams: []
related_flowcharts: []
---
# Section 2.5.15: Seismic Design For Nonstructural Components

2.5.15 Seismic Design For Nonstructural Components
This Section establishes minimum design criteria for nonstructural components
that are permanently attached to structures and for their supports and
attachments. The following components are exempt from the requirements of
this Section.
(1) Architectural components in Seismic Design Category B, other than
parapets supported by bearing walls or shear walls, where the
component importance factor, .+ is equal to 1.0.
(2) Mechanical and electrical components in Seismic Design Category B.
(3) Mechanical and electrical components in Seismic Design Category C
where the importance factor, .+ is equal to 1.0.
(4) Mechanical and electrical components in Seismic Design Category D
where the component importance factor, .+ is equal to 1.0 and either
(a) flexible connections between the components and associated
ductwork, piping, and conduit are provided, or (b) components are
mounted at 1.2 m or less above a floor level and weigh 1780 N or less.
Chapter 2
(5) Mechanical and electrical components in Seismic Design Category C
or D where the component importance factor, .+ is equal to 1.0 and
(a) flexible connections between the components and associated
ductwork, piping, and conduit are provided, and (b) the components
weigh 89 N or less or, for distribution systems, which weigh 73 N/m
or less.
Where the individual weight of supported components and non-building
structures with periods greater than 0.06 seconds exceeds 25 percent of the
total seismic weight W, the structure shall be designed considering interaction
effects between the structure and the supported components.
Testing shall be permitted to be used in lieu of analysis methods outlined in this
Chapter to determine the seismic capacity of components and their supports
and attachments.
2.5.15.1
Component importance factor
All components shall be assigned a component importance factor. The
component importance factor, .+ shall be taken as 1.5 if any of the following
conditions apply:
(1) The component is required to function after an earthquake,
(2) The component contains hazardous materials, or
(3) The component is in or attached to a occupancy category IV building
and it is needed for continued operation of the facility.
All other components shall be assigned a component importance factor, .+ equal
to 1.0.
2.5.15.2
Component force transfer
Components shall be attached such that the component forces are transferred to
the structure. Component attachments that are intended to resist seismic forces
shall be bolted, welded, or otherwise positively fastened without consideration
of frictional resistance produced by the effects of gravity. A continuous load path
of sufficient strength and stiffness between the component and the supporting
structure shall be verified. Local elements of the supporting structure shall be
designed for the component forces where such forces control the design of the
elements or their connections. In this instance, the component forces shall be
those determined in Sec 2.5.15.3, except that modifications to &! and @! due to
anchorage conditions need not be considered. The design documents shall
include sufficient information concerning the attachments to verify compliance
with the requirements of these Provisions.
Chapter 2
2.5.15.3
Seismic design force
The seismic design force, Fc, applied in the horizontal direction shall be centered
at the component’s center of gravity and distributed relative to the component's
mass distribution and shall be determined as follows:







h
z
R
I
W
a
F
c
c
c
h
c
c
2
1

(6.2.57)
Where,
0.75L3I+.+ ≤&+ ≤1.5L3I+.+
a+ 5 component amplification factor which varies from 1.0 to 2.5 (Table
6.2.22 or Table 6.2.23).
L3 5 expected horizontal peak ground acceleration (in g) for design 5
0.67ZS
I+ 5 weight of component
@+ 5 component response reduction factor which varies from 1.0 to
12.0 (Table 6.2.22 or Table 6.2.23)
4 5 height above the base of the point of attachment of the component,
but z shall not be taken less than 0 and the value of 4/ℎ need not
exceed 1.0
h 5 roof height of structure above the base
The force &+ shall be independently applied in at least two orthogonal horizontal
directions in combination with service loads associated with the component. In
addition, the component shall also be designed for a concurrent vertical force of
± 0.5ahWc.
Where non-seismic loads on nonstructural components exceed &+ such loads
shall govern the strength design, but the seismic detailing requirements and
limitations shall apply.
2.5.15.4
Seismic relative displacements
The relative seismic displacement, #+ for two connection points on the same
structure A, one at a height ℎ and other at height ℎH, for use in component
design shall be determined as follows:
yA
xA
c
D




(6.2.58)
Chapter 2
#+ shall not exceed #+ \' given by:


sx
aA
y
x
c
h
h
h
D



max
(6.2.59)
Where,
w 5 Deflection at level x of structure A
Hw 5 Deflection at level y of structure A
∆'w 5 Allowable story drift for structure A
hx = Height (above base) of level x to which upper connection point is
attached.
hy = Height (above base) of level y to which lower connection point is
attached.
hsx = Story height used in the definition of the allowable drift a
For two connection points on separate structures, A and B, or separate structural
systems, one at level x and the other at level y, Dc shall be determined as follows:
yB
xA
c
D




(6.2.60)
Dc shall not exceed Dc max given by:
sx
aB
y
sx
aA
x
c
h
h
h
h
D




max
(6.2.61)
Where,
$$HA = Deflection at level y of structure B$$
$$∆'A = Allowable story drift for structure B$$
The effects of relative seismic relative displacements shall be considered in
combination with displacements caused by other loads as appropriate.