---
clause: "2.5.7.9"
title: "P-delta effects"
chapter: "2"
chapter_title: "Loads on Buildings and Structures"
related_tables: ["../json/table_06_6.2.19.json"]
related_diagrams: []
related_flowcharts: []
---
# Section 2.5.7.9: P-delta effects

2.5.7.9 P-delta effects
The P-delta effects on story shears and moments, the resulting member forces
and moments, and the story drifts induced by these effects are not required to
be considered if the stability coefficient (θ) determined by the following
equation is not more than 0.10:
d
sx
x
x
C
h
V
P 


(6.2.48)
Where,
; 5  Total vertical design load at and above level ; where
computing ;, no individual load factor need exceed 1.0
∆ 5  Design story drift occurring simultaneously with 
 5 Storey shear force acting between levels  and  −1
ℎ 5 Storey height below level
5 Deflection amplification factor given in Table 6.2.19
The stability coefficient g shall not exceed g\' determined as follows:
25
0
5
0
.
.
max


d
C


(6.2.49)
Chapter 2
Where, c is the ratio of shear demand to shear capacity for the story between
levels  and  −1. This ratio is permitted to be conservatively taken as 1.0.
Where, the stability coefficient g is greater than 0.10 but less than or equal
to g\', the incremental factor related to P-delta effects on displacements and
member forces shall be determined by rational analysis. Alternatively, it is
permitted to multiply displacements and member forces by
1
(1−g).
Where, g is greater than g\', the structure is potentially unstable and shall be
redesigned.
Where, the P-delta effect is included in an automated analysis, Eq. 6.2.49 shall
still be satisfied, however, the value of g computed from Eq. 6.2.48 using the
results of the P-delta analysis is permitted to be divided by (1 + g) before
checking Eq. 6.2.49.
2.5.8
Dynamic Analysis Methods
Dynamic analysis method involves applying principles of structural dynamics to
compute the response of the structure to applied dynamic (earthquake) loads.