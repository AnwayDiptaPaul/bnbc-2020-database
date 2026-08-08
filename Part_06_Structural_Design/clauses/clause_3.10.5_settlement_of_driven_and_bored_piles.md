---
clause: "3.10.5"
title: "Settlement of Driven and Bored Piles"
chapter: "3"
chapter_title: "Soils and Foundations"
related_tables: ["../json/table_06_6.3.7.json", "../json/table_06_6.3.13.json", "../json/table_06_6.3.9.json", "../json/table_06_6.3.14.json"]
related_diagrams: []
related_flowcharts: ["../mmd/flow_06_proc_02e546.mmd"]
---
# Section 3.10.5: Settlement of Driven and Bored Piles

3.10.5 Settlement of Driven and Bored Piles
The settlement of axially loaded piles and pile groups at the allowable loads shall be
estimated. Elastic analysis, load transfer and/or finite element techniques may be
used. The settlement of the pile or pile group shall not exceed the tolerable
movement limits as recommended for shallow foundations (Table 6.3.7). When a pile
is loaded, two things would happen involving settlement.

The pile would settle into the soil

The pile material would compress due to load
The settlement of a single pile can be broken down into three distinct parts.

Settlement due to axial deformation, C'

Settlement at the pile tip, C!"

Settlement due to skin friction, C
C"()Ð<) 5 C' + C!" + C
(6.3.35a)
Chapter 3
Moreover, piles acting in a group could undergo long term consolidation settlement.
Settlement due to axial deformation of a single pile can be estimated as :
C' 5
ÔRT³'RÕB
wHU
(6.3.35b)
Where,
?! = Load transferred to the soil at tip level
? = Total skin friction load
$$L  = Length of the pile$$
$$A  = Cross section area of the pile$$
$$%A = Young’s modulus of pile material$$
$$L = 0.5 for clay and silt soils$$
= 0.67 for sandy soil
Pile tip settlement, C!" can be estimated as :
C!" 5
+TRT
3>Ý
(6.3.35c)
Where,
?! = Load transferred to the soil at tip level
# = Diameter of the pile
X = Ultimate end bearing capacity
! = Empirical coefficient as given in Table 6.3.13
Table 6.3.13: Typical Values of "V for Settlement Calculation of Single Pile
Soil Type
Values of "V
Driven Pile
Bored Pile
Dense Sand
0.02
0.09
Loose Sand
0.04
0.18
Stiff Clay
0.02
0.03
Soft Clay
0.03
0.06
Dense Silt
0.03
0.09
Loose Silt
0.05
0.12
Chapter 3
Skin friction acting along the shaft would stress the surrounding soil. Skin friction
acts upward direction along the pile. The force due to pile on surrounding soil would
be in downward direction. When the pile is loaded, the pile would slightly move
down. The pile would drag the surrounding soil with it. Hence, the pile settlement
would occur due to skin friction as given by :
C 5
+R
3>Ý
(6.3.36)
Where,
 = Empirical coefficient 5 ¸0.93 + 0.16
B
3¹ !
! = Empirical coefficient as given in Table 6.3.9
? = Total skin friction load
# = Diameter of the pile
X = Ultimate end bearing capacity
Short Term Pile Group Settlement
Short term or elastic pile group settlement can be estimated using the following
relation.
C 5 C"()Ð<) ¸
A
3¹
=.r
(6.3.37)
Where,
C = Settlement of the pile group
C"()Ð<) = Total settlement of a single pile
= Smallest dimension of the pile group
# = Diameter of the pile
Interestingly, geometry of the group does not have much of an influence on the
settlement. As such, Group Settlement Ratio, @ of a pile group consisting of n
number of piles can be approximated as follows :
@ 5
Þ
*(ÚÞWX) 5 (*)=.r
(6.3.38)
The settlement of the group can be estimated as the highest value as obtained from
Equations 6.3.37 and 6.3.38.
Chapter 3
Long Term Settlement for Pile Group
For pile groups, settlement due to consolidation is more important than for single
piles.  Consolidation settlement of pile group in clay soil is computed using the
following simplified assumptions.

The pile group is assumed to be a solid foundation with a depth 2/3rd the
length of the piles

Effective stress at mid-point of the clay layer is used to compute
settlement
If soil properties are available, the consolidation settlement (S) may be obtained from
the following equation. The depth of significant stress increase (10%) or the depth of
bed rock whichever is less should be taken for computation of settlement. Stress
distribution may be considered as 2 vertical to 1 horizontal.
C 5
+G
1³<Ý VSQ
σÝ′
(6.3.39)
Where,
+  = Compression index of soil
P  = initial void ratio
-   = Thickness of the clay layer
σ
′  = Initial effective stress at mid-point of the clay layer
σ!
′ = Increase in effective stress at mid-point of the clay layer due to pile
load.
In absence of soil properties the following empirical equations may be used to
estimate the long term consolidation settlement of clay soils.
For clay:
C 5
G
2 Ln ¸
σÍ′

(6.3.40)
For sand:
C 5
G
2 Y¸
σÍ′

−¸
σÝ′

Z
(6.3.41)
Chapter 3
Where,
- = Thickness of the clay layer
σ′  = Initial effective stress at mid-point of the clay layer
σ1
′  = New effective stress at mid-point of the clay layer after pile load.
σ7′  = Reference stress (100 kPa)
9 = Dimensionless modulus number as obtained from Table 6.3.14
d = Stress exponent as obtained from Table 6.3.14.
Table 6.3.14: Settlement Parameters
Soil
Density
Modulus
Number, M
Stress
Exponent, j
Till
V. Dense to Dense
1000  - 300
1.0
Gravel
-
400  - 40
0.5
Sand
Dense
400 - 250
0.5
Sand
Medium Dense
250  - 150
0.5
Sand
Loose
150  - 100
0.5
Silt
Dense
200  - 80
0.5
Silt
Medium Dense
80  - 60
0.5
Silt
Loose
60  - 40
0.5
Silty Clay
Stiff
60  - 40
0.5
Silty Clay
Medium Stiff
20  - 10
0.5
Silty Clay
Soft
10  - 5
0.5
Marine Clay
Soft
20  - 5
0.0
Organic Clay
Soft
20  - 5
0.0
Peat
-
5  - 1
0.0