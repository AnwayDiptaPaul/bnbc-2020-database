---
clause: "3.9.5"
title: "Dynamic Ground Stability or Liquefaction Potential for Foundation Soils"
chapter: "3"
chapter_title: "Soils and Foundations"
related_tables: ["../json/table_06_6.3.9.json"]
related_diagrams: []
related_flowcharts: ["../mmd/flow_06_proc_b48ede.mmd"]
---
# Section 3.9.5: Dynamic Ground Stability or Liquefaction Potential for Foundation Soils

3.9.5 Dynamic Ground Stability or Liquefaction Potential for Foundation Soils
Soil liquefaction is a phenomenon in which a saturated soil deposit loses most, if not
all, of its strength and stiffness due to the generation of excess pore water pressure
during earthquake-induced ground shaking. It has been a major cause for damage of
structures during past earthquakes (e.g., 1964 Niigata Earthquake). Current
knowledge of liquefaction is significantly advanced and several evaluation methods
are available. Hazards due to liquefaction are routinely evaluated and mitigated in
seismically active developed parts of the world.
Chapter 3
Liquefaction can be analyzed by a simple comparison of the seismically induced
shear stress with the similarly expressed shear stress required to cause initial
liquefaction or whatever level of shear strain amplitude is deemed intolerable in
design. Usually, the occurrence of 5% double amplitude (DA) axial strain is adopted
to define the cyclic strength consistent with 100% porewater pressure build-up. The
corresponding strength (CRR) can be obtained by several procedures. Thus, the
liquefaction potential of a sand deposit is evaluated in terms of factor of safety FL ,
defined as in Eq. 6.3.6. The externally applied cyclic stress ratio (CSR) can be
evaluated using Equations 6.3.7a, 6.3.7b and 6.3.8.
&B 5
+SS
+S
(6.3.6)
If the factor of safety &B is < 1, liquefaction is said to take place. Otherwise,
liquefaction does not occur. The factor of safety obtained in this way is generally
used to identify the depth to which liquefaction is expected to occur in a future
earthquake. This information is necessary if countermeasure is to be taken in an in
situ deposit of sands.
The cyclic shear stress induced at any point in level ground during an earthquake due
to the upward propagation of shear waves can be assessed by means of a simple
procedure proposed. If a soil column to a depth z is assumed to move horizontally
and if the peak horizontal acceleration on the ground surface is L\' , the maximum
shear stress E\' acting at the bottom of the soil column is given by
E\' 5  L\' Y(ð")(4/Q)
(6.3.7a)
Y 5 1 −0.0154
(6.3.7b)
Where, ð" is unit weight of the soil, Q is the gravitational acceleration, 4 is the depth
and  Y is a stress reduction coefficient to allow for the deformability of the soil
column ( Y < 1). It is recommended to use the empirical formula given in Eq.
6.3.7b to compute stress reduction coefficient Y, where 4 is in meters. Division of
both sides of Eq. 6.3.7a by the effective vertical stress D¼′  gives
C@ 5
I
J·′
5
'

Y
J·
J·′
(6.3.8)
Where, D¼ 5 ð"4 is the total vertical stress. Eq. 6.3.8 has been used widely to assess
the magnitude of shear stress induced in a soil element during an earthquake. The
peak ground acceleration, L\' should be taken from seismic zoning map. One of
the advantages of Eq. 6.3.8 is that all the vast amount of information on the
horizontal accelerations that has ever been recorded on the ground surface can be
used directly to assess the shear stress induced by seismic shaking in the horizontal
plane within the ground.
Chapter 3
The second step is to determine the cyclic resistance ratio (CRR) of the in situ soil.
The cyclic resistance ratio represents the liquefaction resistance of the in situ soil.
The most commonly used method for determining the liquefaction resistance is to
use the data obtained from the standard penetration test. A cyclic triaxial test may
also be used to estimate CRR more accurately. Site response analysis of a site may be
carried out to estimate the site amplification factor. For this purpose, dynamic
parameters such as shear modulus and damping factors need to be estimated.  The
site amplification factor is required to estimate  L5L for a given site properly.  The
following points are to be noted as regards to soil liquefaction:

Sandy and silty soils tend to liquefy; clay soils do not undergo liquefaction
except the sensitive clays.

Resistance to liquefaction of sandy soil depends on fine content. Higher the
fine content lower is the liquefaction potential.

As a rule of thumb, any soil that has a SPT value higher than 30 will not
liquefy.
Fine grained soils (silty clays/ clayey silt) are susceptible to liquefaction if (Finn et.
al., 1994):

Fraction finer than 0.005 mm
≤ 10%

Liquid limit (LL)
≤ 36%

Natural water content
≤ 0.9 × LL

Liquidity index
≤ 0.75
3.9.6
Structural Design of Shallow Foundations
The foundation members should have enough strength to withstand the stresses
induced from soil-foundation interaction. The following important factors should be
considered in the structural design of foundations.
3.9.6.1
Loads and reactions
Footings shall be considered as under the action of downward forces, due to the
superimposed loads, resisted by an upward pressure exerted by the foundation
materials and distributed over the area of the footings as determined by the
eccentricity of the resultant of the downward forces. Where piles are used under
footings, the upward reaction of the foundation shall be considered as a series of
concentrated loads applied at the pile centers, each pile being assumed to carry the
computed portion of the total footing load.
Chapter 3
3.9.6.2
Isolated and multiple footing reactions
When a single isolated footing supports a column, pier or wall, the footing shall be
assumed to act as a cantilever element. When footings support more than one
column, pier, or wall, the footing slab shall be designed for the actual conditions of
continuity and restraint.
3.9.6.3
Raft foundation reactions
For determining the distribution of contact pressure below a raft it is analyzed either
as a rigid or flexible foundation considering the rigidity of the raft, and the rigidity of
the superstructure and the supporting soil. Consideration shall be given to the
increased contact pressure developed along the edges of raft on cohesive soils and
the decrease in contact pressure along the edges on granular soils. Any appropriate
analytical method reasonably valid for the condition may be used. Choice of a
particular method shall be governed by the validity assumptions used. Numerical
analysis of rafts using appropriate software may also be used for determination of
reactions, shears and moments.
Both analytical (based on beams on elastic foundation, Eq. 6.3.9) and numerical
methods require values of the modulus of subgrade reaction of the soil. For use in
preliminary design, indicative values of the modulus of subgrade reaction (k) for
cohesionless soils and cohesive soils are shown in Tables 6.3.9a and 6.3.9b,
respectively.
m 5 0.65. ¸
HAK
Hµ ¹
1 1
»
.
H
(1ÒêÈ) .
1
A
(6.3.9)
$$Where, L= Modulus of elasticity of soil; LM = Flexural rigidity of foundation;$$
N = Width of foundation; O = Poisson’s ratio of soil.
Table 6.3.9a: Modulus of Subgrade Reaction (k) for Cohesionless Soils
Soil Characteristic
*Modulus of Sub-grade Reaction (k) of Soil
(kN/m3)
Relative
Density
Standard Penetration Test
Value (N) (Blows per 300
mm)
For Dry or Moist
State
For Submerged
State
Loose
Medium
Dense
<10
10 to 30
30 and over
15000
15000 to 47000
47000 to 180000
9000 to 29000
29000 to 108000
*The above values apply to a square plate 300 mm x 300 mm or beams 300 mm wide.
Chapter 3
Table 6.3.9b: Modulus of Subgrade Reaction (k) for Cohesive Soils
Soil Characteristic
Modulus of Subgrade
Reaction, k (kN/m3)
Consistency
Unconfined Compressive Strength (kN/m2)
Stiff
Very Stiff
Hard
100 to 200
200 to 400
400 and over
27000
27000 to 54000
54000 to 108000
* The values apply to a square plate 300 mm x 300 mm. The above values are based
on the assumption that the average loading intensity does not exceed half the ultimate
bearing capacity.
3.9.6.4
Critical section for moment
External moment on any section of a footing shall be determined by passing a
vertical plane through the footing and computing the moment of the forces acting
over the entire area of the footing on one side of that vertical plane. The critical
section for bending shall be taken at the face of the column, pier, or wall. In the case
of columns that are not square or rectangular, the section shall be taken at the side of
the concentric square of equivalent area. For footings under masonry walls, the
critical section shall be taken halfway between the middle and edge of the wall. For
footings under metallic column bases, the critical section shall be taken halfway
between the column face and the edge of the metallic base. For mat foundations and
combined footings critical section should be determined on the basis of maximum
positive and negative moments obtained from soil-foundation interaction.
3.9.6.5
Critical section for shear
Computation of shear in footings, and location of critical section shall be in
accordance with relevant sections of the structural design part of the Code. Location
of critical section shall be measured from the face of column, pier or wall, for
footings supporting a column, pier, or wall. For footings supporting a column or pier
with metallic base plates, the critical section shall be measured from the location
defined in the critical section for moments for footings.
3.9.6.6
Critical section for footings on driven piles/bored piles/drilled piers
Shear on the critical section shall be in accordance with the following. Entire reaction
from any driven pile or bored piles, and drilled pier whose center is located !/2
(! = diameter of the pile) or more outside the critical section shall be considered as
producing shear on that section. Reaction from any driven pile or drilled shaft whose
center is located !/2 or more inside the critical section shall be considered as
producing no shear on that section. For the intermediate position of driven pile or
Chapter 3
drilled shaft centers, the portion of the driven pile or shaft reaction to be considered
as producing shear on the critical section shall be based on linear interpolation
between full value at !/2 outside the section and zero value at !/2 inside the
section.
3.9.6.7
Transfer of Forces at the Base of Column.
All forces and moments applied at base of column or pier shall be transferred to top
of footing. If the strength of concrete of footing is less than that of column, then
bearing stress of footing concrete and reinforcement should be checked against
imposed loading.
Lateral forces shall be transferred to supporting footing in accordance with shear
transfer provisions of the relevant sections of the structural design part of the Code.
Bearing on concrete at contact surface between supporting and supported member
shall not exceed concrete bearing strength for either surface.
3.9.6.8
Reinforcement
Reinforcement shall be provided across interface between supporting and supported
member either by extending main longitudinal reinforcement into footings or by
dowels. Reinforcement across interface shall be sufficient to satisfy all of the
following:
(i)
Reinforcement shall be provided to transfer all force that exceeds
concrete bearing strength in supporting and supported member.
(ii) If it is required that loading conditions include uplift, total tensile force
shall be resisted by reinforcement only.
(iii) Area of reinforcement shall not be less than 0.005 times gross area of
supported member (column) with a minimum of 4 bars.
(iv) Minimum reinforcement of footing and raft shall be governed by
temperature and shrinkage reinforcement as per Sec 8.1.11 Chapter 8 of
this Part.
Reinforcement of square footings shall be distributed uniformly across the entire
width of footing. Reinforcement of rectangular footings shall be distributed
uniformly across the entire width of footing in the long direction. In the short
direction, the portion of the total reinforcement given by the following equation shall
be distributed uniformly over a band width (centered on center line of column or
pier) equal to the length of the short side of the footing.
S<)7+<\<)" ) 4') >"ℎ
e"'Ð 7<)7+<\<)" ) ℎ7" 7<+") 5

(Î³1)
(6.3.10)
Chapter 3
Here, c is the ratio of the footing length to width. The remainder of reinforcement
required in the short direction shall be distributed uniformly outside the center band
width of footing.
3.9.6.9
Development length and splicing
Computation of development length of reinforcement in footings shall be in
accordance with the relevant sections of the structural design part of the Code.
For transfer of force by reinforcement, development length of reinforcement in
supporting and supported member required splicing shall be in accordance with the
relevant sections (Part. 6, Chapters 6 and 8) of the structural design part of the Code.
Critical sections for development length of reinforcement shall be assumed at the
same locations as defined above as the critical section for moments and at all other
vertical planes where changes in section or reinforcement occur.