---
description: Nullam urna elit, malesuada eget finibus ut, ac tortor.
readtime: 30
date: 2024-03-1
tags:
  - GT&T
  - Datum
---

# 6. Datums and Datum Systems
## Abstract 
<p align="justify">A datum system has the purpose of defining a set of two or more ideal features established in a specific order (for example, a system made up of a triad of mutually orthogonal planes) that allows not only the tolerance zones to be orientated and located, but also their origin to be defined for the measurement, and the workpiece to be blocked during the control. When it is not desirable to use a complete integral feature to establish a datum feature, it is possible to indicate portions of the single feature (areas, lines or points) and their dimensions and locations using datum targets. This chapter illustrates the main differences between the ISO 5459 and ASME standards for the specification of datums and highlight some theoretical and mathematical concepts. This section also provides simple rules to follow whenever choosing functional datums to ensure the part will function as intended, with the least possible amount of variation.</p>
## 6.1 Datum Systems
<p align="justify">A datum system represents one of the most advantageous instruments to pass on information about functional relationships and, at the same time, to transmit the modalities and sequences with which the control of the component should be carried out in such a way that the inspection measurement is univocal and repeatable.</p>
<p align="justify">The greatest disadvantage of the use of a datum system is that an adequate knowledge of the geometrical tolerance standards is necessary. In fact, a lack of attention to the functional aspects of geometrical dimensioning has led to some datum misconceptions. The first of these concerns the conviction that datums exist on a part, although the planes and axes taken as datums are in fact abstract concepts that are obtained through complex verification operations.</p>
<p align="justify">Another misconception is that datums are established directly during the manufacturing design phase; in fact, the datums derived from operational requirements often do not agree with the ones that are fixed during the design phase on the basis of the functional requirements. If a process engineer introduces any modifications, the functional requirements will no longer be respected, because of changes in the tolerances (which often become more reduced).</p>
<p align="justify">A datum should always be selected on the basis of the functions of a part, since choosing datums on the basis of the technological location of the workpieces can lead to a reduction in the available tolerances.</p>
<p align="justify">Adatum system (known as DRF, Datum Reference Frame in theASMEstandards) is a set of two or more ideal features established in a specific order from two or more datum features, with the aim of (Fig. 6.1):</p>
1. <p align="justify">defining the origin from which the location or geometric characteristics of the features of a part are established;</p>
2. <p align="justify">allowing the workpiece to be blocked during a control, so that the control is univocal and repeatable;</p>
3. <p align="justify">locating and orienting the tolerance zones.</p>
<p align="justify">In short, datums allow a datum system to be defined for the dimensioning of a drawing and they can be considered as a way of blocking the degrees of freedom of a tolerance zone.</p>
<p align="justify">The ISO 5459 standard specifies the terminology, rules and methodologies pertaining to the indication and comprehension of datums and of datum systems in the technical documentation of a product. The physical surfaces of real and imperfect parts are defined as datum features in the standard as they serve the purpose of constraining the rotational and translational degrees of freedom during the assembly processes and which can be used to define the datums (Fig. 6.2). In fact, each workpiece is considered to be made up of features that can have a size and an axis, or a symmetry plane (a feature of size such as a groove, a hole or a pin), or nondimensional features such as flat or cylindrical surfaces; as each feature can be considered as a datum, it is possible to have datums correlated to both sizeable and non-sizeable features, which are indicated on a drawing in different ways.</p>
![](https://pics.caxer.net/2024/06/fa6c229ae4bde89ca3ce40b6c28aa69c.png)
<center>Fig. 6.1 A datum system has the purpose of defining a set of two ormore ideal features, established in a specific order (for example, a system made up of a triad of mutually orthogonal planes), that allows not only the tolerance zones to be orientated and located, but also their origin to be defined for the measurement, and the workpiece to be blocked during the control</center>

<p align="justify">A datum is a theoretically exact point, straight line, or plane from which the location and orientation of features, or both, can be defined (Fig. 6.3). A datum specification refers to the concept of a situation feature, which is obtained through an association criterion with the datum feature, that is, an ideal feature (plane, point or straight line) is associated with the true (extracted and filtered) surface.</p>
![](https://pics.caxer.net/2024/06/f3fa8ea9c32a38bdf5bda3dd73c1413c.png)
<center>Fig. 6.2 Datum features are particular physical features of real, imperfect, labelled workpieces that have the purpose of constraining the rotational and translational degrees of freedom of relative parts. Datums are the surfaces of the workpiece that can be touched, and they are suitable for associating to a datum</center>
![](https://pics.caxer.net/2024/06/5e1350c1a39ca90354c29b7f2c3f76d8.png)
<center>Fig. 6.3 A datumis a theoretically exact point, straight line, or plane from which the location and orientation of features, or both, can be defined</center>
![](https://pics.caxer.net/2024/06/10c7f11c92fecf0bd2720e25a6ae1217.png)
<center>Fig. 6.4 According to ISO 5459, a datum is one or more situation features (plane, point and/or straight line) that is selected to define the location or orientation, or both, of a tolerance zone or an ideal feature that represents, for instance, a virtual condition</center>

<p align="justify">In short, a datum is one or more situation features of one or more features associated with one or more real integral features selected to define the location or orientation, or both, of a tolerance zone or an ideal feature that represents, for instance, a virtual condition (Fig. 6.4). Datums allow tolerance zones to be located or orientated and virtual conditions to be defined (for example, the maximum material virtual condition, according to ISO 2692).</p>
### 6.1.1 Association of Datums
<p align="justify">A datum is a theoretically exact point, axis, or plane that is obtained through an association criterion with the datum feature, that is, an ideal feature (plane, point or line) which is associated with the true (extracted and filtered) surface. The objective of such an association is to obtain an unambiguous identification of unique datums or datum systems.</p>
<p align="justify">In order to establish an associated feature, it is necessary to first perform a partition, then an extraction, a filtration and, finally, an association. The filtration should retain the highest points of the real integral feature.</p>
<p align="justify">For example, in the case of a datum feature made up of a flat surface of a part, the extracted surface of a true geometry is obtained, through a partition and extraction process, to which an ideal tangent plane of a perfect geometrical form is associated (situation feature, Fig. 6.5). In practice, the ideal tangent plane is approximated from the smooth surface of a matching plane of a control system, as shown in Fig. 6.6.</p>
<p align="justify">The associated features, used to establish the datums, simulate contact with the
real integral features in a way that ensures that the associated feature is outside the
material of the non-ideal feature. When the result of this process is ambiguous, then
the associated featuremustminimise the maximum distance (normal to the associated
feature) between the associated feature and the filtered feature (Fig. 6.7).</p>
<p align="justify">The association process adopted to obtain an axis datum, starting from a true
feature (integral) is shown in Fig. 6.8. The extracted feature is obtained through an
extraction and filtration process; the derived feature (axis of the associated cylinder),
and therefore the datum, are thus obtained through an association process with an
ideal cylinder. In the same way as for a planar surface, in the case of cylindrical
elements, the associated feature should minimise the maximum distance between
the associated feature and the filtered feature (Fig. 6.9).</p>
![](https://pics.caxer.net/2024/06/a8baa136ec24dc1383fb736406aaac3e.png)
<center>Fig. 6.5 The association process used to obtain a datum: the extracted surface is obtained from the true geometry, through a partition and extraction process, and an ideal tangent plane is associated with such a surface</center>
![](https://pics.caxer.net/2024/06/ec8dac2c64f1b206b3f0900d3276ea88.png)
<center>Fig. 6.6 If the datum feature is the flat surface of a workpiece, the associated feature is obtained from a theoretical envelope plane (e.g. a tangent plane) of perfect geometrical form, and it may be approximated from the matching granite plane of the control device</center>
![](https://pics.caxer.net/2024/06/b82a74daeeaca56dcc9b5a1f3ca98520.png)
<center>Fig. 6.7 The association method for a planar surface using the minimax criteria. 1. Outside the material tangent plane (datum). 2. Filtered feature. 3. Real integral feature</center>

### 6.1.2 Datum: Mathematical Concepts
<p align="justify">Datums and datum systems are theoretically exact geometric features used together with implicit or explicit theoretically exact dimensions (TED) to locate or orientate
the tolerance zones and virtual conditions.</p>
<p align="justify">Adatum consists of a set of situation features for an ideal feature (feature of perfect form) associated with the identified datum features of a workpiece. Since these ideal
features have the task of blocking the degrees of freedom of the tolerance zones, the
geometrical type of these associated features should be one of the invariance classes
reported in Table 6.1.</p>
![](https://pics.caxer.net/2024/06/30408e478fc6a113cbe523dcbb36e226.png)
<center>Fig. 6.8 The association and derivation process used to obtain a datum axis from a cylinder: 1. Nominal integral feature. 2. Nominal derived feature. 3. Real integral surface of the workpiece (datum feature). 4. Extracted integral feature; 5. Association with an ideal cylinder. 6. Derived feature (axis of the associated cylinder). 7. Datum (situation feature)</center>
![](https://pics.caxer.net/2024/06/4cfd5266f49c99fd069f5721c85de023.png)
<center>Fig. 6.9 The association method for a cylindrical surface using the minimax criteria. 1. Real
integral feature. 2. Filtered feature. 3. Maximum inscribed cylinder</center>

<p align="justify">Each feature has 6 degrees of freedom (translations along the x, y, z axes and
rotations around the x, y, z axes). The invariance class corresponds to the degrees of
freedom (which remain and are not locked). Such a class describes the displacement
of the feature (translation, rotation) for which the feature is kept identical in space.</p>
<p align="justify">In Table 6.1, all the surfaces are classified into seven classes on the basis of
the degrees of freedom for which the surface is invariant. Situation features (point,
straight line, plane) are defined for each class of surface.</p>
<p align="justify">When a single surface or a collection surface is identified as a datum feature,
the invariance degrees for which the surface is invariant should be identified and compared with Table 6.1 in order to determine the set of situation features (point,
straight line, plane, or a combination thereof) that constitutes the datum.</p>
![](https://pics.caxer.net/2024/06/e4478574ea051fb06b0cf7eb7d0c8d49.png)
<center>Table 6.1 All surfaces are classified into seven classes on the basis of the degrees of
freedom for which the surface is invariant</center>

## 6.2 Indication of Datum Features in Technical Documentation
<p align="justify">A datum feature is identified with a capital letter, written within a square, and connected to a triangle that is placed on the feature itself (Fig. 6.10). It is suggested to avoid the use of the letters I, O, Q, X, Y and Z, which could give rise to interpretation problems, while, in the case of complex drawings, it is possible to make use of double letters (AA, BB, etc.).</p>
<p align="justify">In the same way as for the tolerance indications, a triangle, with its identification letter, can be located:</p>
<p align="justify">(a) on the contour line of the feature surface or on an extension line of the feature outline (but clearly separated from the dimension line) if the datum feature is the surface itself (Fig. 6.11); it is also possible in this case to use a leader line that points directly towards the datum surface (Fig. 6.12).</p>
<p align="justify">(b) on an extension of the dimension line of a feature of size when the datum is the feature axis or centerplane of the thus dimensioned part (Fig. 6.13); in this case, for space reasons, it is possible to substitute one of the arrowheads of the measurement line with a datum triangle symbol.</p>
![](https://pics.caxer.net/2024/06/db9a74707a19500078b7c53db1288652.png)
<center>Fig. 6.10 The three ways of indicating a flat surface as a datum feature</center>

<p align="justify">It is necessary to pay particular attention to the correct indication of a datum applied to a feature of size on a drawing: the line of the symbol should coincide with the dimension line of the datum feature, and the indication errors shown in Fig. 6.14 should be avoided.</p>
![](https://pics.caxer.net/2024/06/07c5ec18849f8e334294aae5bc7c7b89.png)
<center>Fig. 6.11 Indications of a datum feature. A triangle does not need to be filled in</center>
![](https://pics.caxer.net/2024/06/beb9ee23d390fbcb730ace70bd2ef116.png)
<center>Fig. 6.12 Indications of a datum feature: the dashed leader line indicates that the datum is on the other side (when the considered surface is hidden)</center>
![](https://pics.caxer.net/2024/06/53edfbe3e15f6867ef5f07216af2b9e9.png)
<center>Fig. 6.13 Indication of a datum feature for a feature of size</center>
![](https://pics.caxer.net/2024/06/b6b726516db47c33f975d1d3c17917bf.png)
<center>Fig. 6.14 Possible errors in the indications of a datum axis. Cylindrical surfaces should not be used as datums. The symbol line should coincide with the dimension line of the datum feature</center>

<p align="justify">In light of all the definitions that have been given so far, does the datum symbol that is utilised in technical drawings indicate a datum or a datum feature (Fig. 6.15)? The symbol obviously indicates a datum feature and not a datum!</p>

## 6.3 The Datum Systems in ASME Y14.5
<p align="justify">TheASMEY14.5 standardmakes a clear distinction between the concept of a datum feature, a datum and a datum feature simulator Adatum is an abstract geometrical feature (point, axis or plane from which a dimensional measurement is made), which represents the perfect counterpart of a datum feature (e.g. an ideal plane or the axis of the perfect geometrical counterpart).</p>
![](https://pics.caxer.net/2024/06/1422e3ad38938e0a698146e735d7a89d.png)
<center>Fig. 6.15 Does the symbol, that is used in technical drawings, indicate a datum or a datum feature? The symbol obviously indicates a datum feature and not a datum</center>

<p align="justify">Simulated datums are conceptually perfect (almost physically perfect), and they represent a bridge between the imperfect real world of datum features and the perfect imaginary world of datums. Ultimately, it is opportune to distinguish between the real datum feature of a workpiece (named datum feature) and the datum, that is, the equivalent theoretical datum (plane, axis or centerplane), as simulated by the associated inspection or manufacturing equipment.</p>
<p align="justify">The datum system of a tool machine is shown in Fig. 6.16: the production equipment has the task of aligning the features of the workpiece with the datums of the machine (for example, datum feature A is aligned with the clamping machine and datum feature B is made to coincide with the z axis). In short, no datums exist on a workpiece, but they are simulated by the datum feature system of the tool machine.</p>
<p align="justify">The true geometric counterpart is the theoretically perfect boundary used to establish a datum from a specified datum feature. True geometric counterparts have a perfect form, and a basic orientation and location relative to other true geometric counterparts for all the datum references in a feature control frame. Furthermore, the true geometric counterparts are adjustable in size, when the datum feature applies an RMB (Regardless Material Boundary), and are fixed at the designated size, when an MMB(MaximumMaterial Boundary) or an LMB ( Least Material Boundary)  is specified.</p>
<p align="justify">The relationship between the primary datum feature and its true geometric counterpart constrains the degrees of freedom. Table 6.2 shows some examples of degrees of freedom constrained by primary datum features, RMB, in the same way as for the concept of invariance class.</p>
![](https://pics.caxer.net/2024/06/bcf290b8a187ed94c426dd84937a0bc1.png)
<center>Fig. 6.16 No datums exist on a workpiece, but they are simulated by the datum feature system of the tool machine (physical datum simulators)</center>

<center>Table 6.2 Constrained degrees of freedom for primary datum features</center>
![](https://pics.caxer.net/2024/06/ce90d8da45ac4084620fc7ff7e421810.png)

### 6.3.1 Establishing a Datum
<p align="justify">In the case of a datum surface made up of a flat surface of a component, the datum is supplied by a theoretical envelope plane (e.g. a tangent plane, the true geometric
counterpart), of perfect geometrical form, and the simulated datum feature is constituted,
for example, by the surface plate of the inspection device. As can be seen in
Fig. 6.17, it is also possible to define a theoretical envelope plane, of perfect form
(true geometric counterpart of a datum feature), on the surface plate; if the workpiece
is placed on the surface plate, the two theoretical planes might not coincide because
of the irregularities on the surfaces. In spite of this observation, a simulated datum is
in fact used as a datum in industrial practice. Such a distinctionmay appear excessive
but, in reality, many errors exist and much confusion arises in defining the datums
and in the inspection of the parts with measuring machines.</p>
<p align="justify">If, instead, the datum feature is a feature of size, the symbol should be associated with a linear dimension (subject to tolerance) and should therefore be placed directly
on the dimension, as shown in Fig. 6.18; in this case, the datum is made up of the axis or centerplane, which is established by an ideal envelope surface.</p>
![](https://pics.caxer.net/2024/06/6980a5e78cba8ed5b58e241c48ae2c25.png)
<center>Fig. 6.17 Establishment of a datum plane</center>
![](https://pics.caxer.net/2024/06/302e67bad838a54bb774f75758bb279c.png)
<center>Fig. 6.18 Placement of Datum Feature Symbols on Features of Size</center>
![](https://pics.caxer.net/2024/06/5f0c3364755b518ca0d5627b793a00d8.png)
<center>Fig. 6.19 When a cylindrical feature is designated as a datum feature, the datum axis is derived by placing the part in an adjustable gauge (self-centring chuck used as a datum feature simulator)</center>

<p align="justify">Figure 6.19 shows the case of a datum made up of the axis of a cylinder; again
in this case, it is possible to make a distinction between the axis of the smallest true
geometric counterpart and the simulated datum feature, defined as the axis of the
feature simulated by the verification gauge. As axes do not exist in the real world,
the equivalent theoretical feature is represented, in the case of external features, by
the axis of the smallest cylinder restricted by a perfect form. The datum is simulated
by the verification device, for example, with a gauge or a self-centring device.</p>
<p align="justify">In the case of cylindrical holes, the simulated datum can be established through the
use of a cylindrical gauge, with themaximum inscribable diameter, or an expandable
chuck; whatever the type of chuck, once inserted into the hole, it does not take on
a fixed shape, and it is necessary to regulate it so that any displacements are of the
same magnitude in all directions (it is obvious that no modifiers should be applied
to the datum).</p>
<p align="justify">In short, it is necessary to pay a great deal of attention to the characterisation
of the simulated theoretical cylinder (which the ASME standards define as Actual
Mating Envelope, AME). In the simplest case, the cylinder is orientated according
to the axis of the imperfect hole, but when the axis of the hole is defined on the basis
of one or two datums, the simulated cylinder (Related Actual Mating Envelope) is
arranged according to the DRF or Datum Reference Frame.</p>
<p align="justify">Figure 6.20 further clarifies the meaning of the related and unrelated Actual
Mating Envelopes: datum A is a plane, while datum B is the axis of a 34 mm
cylinder, orientated with an error of 0.05 mm with respect to plane A; the 10 mm
hole is located with respect to datums A and B. The axis of the feature of size is obtained from the smallest restricted orientated cylinder (the unrelated actual mating
envelope) and it is useful to verify a perpendicularity error with respect to datum A.
The smallest circumscribed cylinder perpendicular to A (the related actual mating
envelope) is used to determine the axis of datum B. The derived centerplane is a
curve made up of the central points of the transversal section perpendicular to the
axis of the feature of size, and it is used to determine the straightness error.</p>
<p align="justify">It is necessary to avoid confusing the axis of a feature of size (obtained through
the smallest circumscribed cylinder orientated according to the feature, Fig. 6.21)
for the axis of the datum B (perfect geometrical counterpart perpendicular to datum
A).</p>
![](https://pics.caxer.net/2024/06/a10995f6401dd7db4b5f1772195d46b9.png)
<center>Fig. 6.20 Related and Unrelated AME in the ASME standard</center>

### 6.3.2 Location of a Workpiece in a Datum Reference Frame
<p align="justify">Simulated datums have the purpose of defining a DRF (Datum Reference Frame),
that is, the datum system of 3 perpendicular planes that define the origin for the
measurements and which allow the workpiece to be blocked during an inspection
(Fig. 6.22). In short, the indications of aDRF system supply an immediate description
of the orientation and of the location of a workpiece (and of the tolerance zones),
thus making the inspection operations univocal and repeatable.</p>
<p align="justify">In order to limit the movement of a part so that repeatable measurements can be
made, it is necessary to restrict the six degrees of freedom. In fact, each piece that
has to be controlled or worked in a datum system has six degrees of freedom (3
linear and 3 rotational, Fig. 6.23). It is possible to show that, in order to eliminate
the 6 degrees of freedom, it is necessary to block the workpiece in a datum reference frame with 3 perpendicular planes, named the primary, secondary and tertiary planes,
respectively.</p>
![](https://pics.caxer.net/2024/06/28dc0a39458d9229c6d6a43d9a7632bb.png)
<center>Fig. 6.21 It is necessary to be careful not to confuse the axis of a feature size (obtained through the
largest circumscribed cylinder orientated according to the feature), which is useful to control the
perpendicularity of a 40 mm hole, with the axis of datum B (axis of the largest inscribable cylinder
perpendicular to datum A)</center>
![](https://pics.caxer.net/2024/06/7afccb9da9677be270cad252fc2ce76c.png)
<center>Fig. 6.22 DRF (Datum Reference Frame)</center>
![](https://pics.caxer.net/2024/06/b4eec13a036465e8b5ac3373acd70a1d.png)
<center>Fig. 6.23 The six degrees of freedom of a workpiece: any movement in the space can be attributed to three possible translations in the direction of the datum axes X, Y and Z and to three rotations, u, v and w, around the same axes</center>
<p align="justify">Let us consider the drawing of the component shown in Fig. 6.24, whose holes
are located with respect to the three datums A, B and C; in order to conduct a
measurement test, datum featureAis put into contact with datum feature simulator A,
thus establishing a primary datum with at least three points of contact, and eliminating
a degree of linear freedom Z and two rotational degrees of freedom, that is, u and v
(Fig. 6.25).</p>
<p align="justify">Datum feature B is then put in contact with datum feature simulator B, and in this
way secondary datum B is established, with a minimum of two points of contact and
elimination of a linear degree, X, and a rotational one w (Fig. 6.26). Finally, tertiary
datum C is defined with just a single point of contact and the last degree of freedom
Y is eliminated by putting datum feature C in contact with its simulator (Fig. 6.27).</p>
![](https://pics.caxer.net/2024/06/8a2758890b63c656eae3d5df571c026a.png)
<center>Fig. 6.24 In order to make the identification of a datum reference frame clearer, the ASME Y14.5
standard introduced the possibility of identifying the axes of the datum system on a drawing in
order to offer an immediate description of the orientation and location of a workpiece (and of the
relative tolerance zone), thus making the measurement test operations univocal and repeatable</center>
![](https://pics.caxer.net/2024/06/c1a59bfaee6a4ffee2e93f8772b78ba5.png)
<center>Fig. 6.25 Datum feature A of the component is put in contact with the datum feature simulator, and
in this way a primary datum is established, with a minimum of three contact points and elimination
of a degree of freedom Z and two rotational ones, that is, u and v. The X, Y and w degrees of
freedom still have to be constrained</center>
![](https://pics.caxer.net/2024/06/e0ed0eec6d618415f5ae62ca66a2b254.png)
<center>Fig. 6.26 Subsequently, datum feature B is put in contact with datum feature simulator B, and in this way the secondary datum is established, with a minimum of two contact points and elimination of a linear degree, X, and a rotational one w. The translation along Y still has to be constrained</center>
![](https://pics.caxer.net/2024/06/44e044bf60cae8cbf64a345c81f8f0d5.png)
<center>Fig. 6.27 Final blocking of the workpiece: tertiary datum C is defined with at least one point of contact (and elimination of the last degree of linear freedom Y), thus datum feature C is placed in relation to its simulator</center>
![](https://pics.caxer.net/2024/06/c35481333309cd8be9b6295a5539345a.png)
<center>Fig. 6.28 The order of the datums in the tolerance frame indicates the sequence of the inspection operations; as can be seen, the location dimension of the hole changes according to the datum plane on which the workpiece is placed</center>
<p align="justify">It is necessary to pay particular attention to the order of the datum sequence as
it influences the result of an inspection. In fact, if the inspection procedure of the
workpiece in Fig. 6.28 is considered, it can be noted that, as the location tolerances
have been indicated in the datum order A, B and C in the frame, the inspection
procedure should be conducted after locating the workpiece in the datum system
according to the exact same order. A change in this order (i.e. A, C, B) would
influence the measurement test, as can be seen in the same figure.</p>

### 6.3.3 Selection of Datum Features
<p align="justify">The starting point for a correct dimensioning is the identification of a datum reference
frame with 3 perpendicular planes (DRF), and in this way functioning and mating of
the parts are guaranteed. As previously mentioned, it is erroneous to think that the
datums should only be established in the manufacturing design phase on the basis
of the requirements of the various operations. Datums should in fact be selected
on the basis of the functional requirements of a part in order to allow the functional
relationships to be communicated on the drawing. The datums should instead always
be established on the basis of the functional requirements because, if the datums are
chosen on the basis of the technological location of the workpieces, the tolerance
available for manufacturing may be reduced.</p>
<p align="justify">The choice of the datum features should obviously be considered in function of
the assembly requirements of the parts, and their sequence very often reproduces
the logical assembly sequence. The case shown in Fig. 6.29 can be considered as an
example: the part with 2 holes should be mated to the plate by means of two fixed
fasteners. The logical sequence that allows an appropriate choice of the three datums
to be made is:</p>
1. <p align="justify">identification of the feature that orientates the workpiece in the assembly, in order to establish the primary datum; in Fig. 6.30, the feature that orientates the workpiece is constituted by mating surface A.</p>
2. <p align="justify">Identification of the feature that locates the workpiece in the assembly, in order to establish the secondary datum; datum feature B that locates the workpiece is represented by the axis of the two cylindrical features.</p>
3.  <p align="justify">Identification of the feature that blocks the workpiece in the assembly, in order to establish the tertiary datum. Finally, tertiary datum C that blocks the workpiece, which is constituted by the milled surface of the component and of the corresponding surface of the plate, is added.</p>
4.  <p align="justify">Qualification of the datum features through the application, orientation and location of opportune form tolerances.</p>
5. <p align="justify">Location of all the geometrical features with reference to the datum features, while utilising the profile tolerances to locate the surfaces.</p>

![](https://pics.caxer.net/2024/06/8a3468932a79bca14a5a9cde194579e7.png)
<center>Fig. 6.29 Choice of the functional datums for a mating with fixed fasteners</center>
![](https://pics.caxer.net/2024/06/cb93f568c018fd48d99f69d5500590e5.png)
<center>Fig. 6.30 The feature that is used to orientate the workpiece is made up of mating surface A (which is defined as the primary datum), while the feature that is considered to locate it is the axis of the two cylindrical features (which is defined as a secondary datum). Finally, the tertiary datum that blocks the workpiece, which is constituted by themilled surface of the component and of the corresponding surface of the plate, is added</center>

<p align="justify">The complete dimensioning of the upper component is reported in theASMEdrawing in Fig. 6.31. The dimensioning of the lower plate is obtained by following the same previously outlined rules.</p>
<p align="justify">However, it is not always necessary to use three datums. The case shown in
Fig. 6.32 can be considered as an example: the cover with the holes should be mated
with the tank through fixed fasteners; the feature that orientates the workpiece is
constituted by mating surface A (which is defined as the primary datum), while the
feature that locates it is represented by the axis of the cylindrical part (which is defined
as the secondary datum). When the axis of a cylinder is used as the datum feature, it is
necessary to imagine using two perpendicular planes, whose intersection determines
the datum axis, and which can rotate freely around the same axis (Fig. 6.33).</p>
![](https://pics.caxer.net/2024/06/a06d6c77524b1186e8c323b21682d274.png)
<center>Fig. 6.31 Complete dimensioning of a component with the 3 established functional datums. The primary datum is qualified with a planarity tolerance and the secondary one with a perpendicularity tolerance. Finally, the two holes in the plate are located with a location tolerance with respect to the three established datums</center>
<p align="justify">If the assembly of the cover takes place as in Fig. 6.34, that is, the tongue must
be mated with the relative groove, three datums are required, that is, it is necessary to add the tertiary datum that blocks the workpiece and which is constituted by the
centerplane of the groove.</p>
![](https://pics.caxer.net/2024/06/318ef5d8e8d27d76d411c288ea999460.png)
![](https://pics.caxer.net/2024/06/1b5e4a9476c7a7ca105ddd71562c3f6a.png)
<center>Fig. 6.32 Selection of the primary datum (used to orientate) and of the secondary datum (used to locate)</center>
![](https://pics.caxer.net/2024/06/b223f2aba867f0816e2406a3323cb4aa.png)
<center>Fig. 6.33 The axis of a cylinder that is used as a datum feature is associated with two imaginary perpendicular planes, whose intersection determines the datum axis, which can rotate freely around the same axis</center>
<p align="justify">In this case, the two imaginary planes can no longer rotate and are constrained in a precise location (Fig. 6.35). Table 6.3 summarises the main differences between
the ISO and ASME standards pertaining to the specification of a datum.</p>
![](https://pics.caxer.net/2024/06/f5dbb23dc722c5b1c15561b99e2b6e0d.png)
![](https://pics.caxer.net/2024/06/8d501a634cc3a05c03117dda727dbc98.png)
<center>Fig. 6.34 Selection of the primary datum (used to orientate), of the secondary datum (used to locate) and of the tertiary datum (used to block)</center>
![](https://pics.caxer.net/2024/06/d6ec619311b0d4ab3a09e9b45513b325.png)
<center>Fig. 6.35 The second datum is constituted by an axis and the third by a centerplane: the two imaginary planes can no longer rotate and are constrained in a precise location</center>







<script src="https://giscus.app/client.js"
        data-repo="gchongo/gchongo.github.io"
        data-repo-id="R_kgDOL1P4-w"
        data-category="General"
        data-category-id="DIC_kwDOL1P4-84Cf98Z"
        data-mapping="pathname"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="bottom"
        data-theme="preferred_color_scheme"
        data-lang="zh-CN"
        crossorigin="anonymous"
        async>
</script>