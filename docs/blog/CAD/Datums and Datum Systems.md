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
