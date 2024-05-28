## Abstract
<p align="justify">The main concepts proposed in this chapter have the aim of expressing the fundamental rules on which the geometrical specification of workpieces can be based through a global approach that includes all the geometrical tools needed for GPS. Indeed, in an increased globalisation market environment, the exchange of technical product information and the need to unambiguously express the geometry of mechanical workpieces, are of great importance. The symbols, terms, and rules of the GPS language that are given in the ISO 17450, ISO 1101 and ISO 14660 standards are presented in this chapter through tools and concepts that allow an engineer to perfectly specify the imperfect geometry of a component, and to understand the impact of the drawing specifications on inspection.</p>
## 2.1 General Concepts
<p align="justify">The current industrial situation is characterised more and more by a continuous evolution towards increasingly dynamic interaction models between clients and suppliers, thereby putting traditional technical communication methodologies under greater pressure.</p>
<p align="justify">In a market environment of increased globalisation, the exchange of technical product information and the need to unambiguously express the geometry of mechanicalworkpieces is of great importance. Consequently, the codification associated with the functional geometrical variations of the macro- and micro-geometries of workpiece specifications needs to be unambiguous and complete. An ever increasing requirement of accuracy has been observed in the description and in the interpretation of the functional requirements, and, consequently in the drawing up of the technical designs and documents in the mechanical subcontracting sector, which must be coherent and complete and able to adequately support the co-design and outsourcing requirements of a production.</p>
<p align="justify">In addition, the rapid development of the coordinatemeasuring technique indicates that some specifications based on measurements with gauges and calibres, that were used in the last quarter of the XXth century, may be interpreted differently and produce different measurement results.</p>
<p align="justify">Today, the importance of international standards in the technical documentation field is growing at the same rate as the globalisation of production; a simple, clear, univocal and concise three-dimensional description of the designed components is therefore necessary.</p>
<p align="justify">For this reason, a remarkable effort is under way to develop a coherent and innovative management scheme of geometric tolerances, in order to obtain a better definition of the correlation between the functional requirements, geometrical specifications and relative control procedures, which can be summarised as the Geometrical Product Specification—GPS and Geometric Dimensioning and Tolerancing— GD&T principles, and which, if implemented correctly and coherently, allow the drawbacks of the present methodologies to be overcome and intra and inter-company communication to be revolutionised.</p>
<p align="justify">Although the discussion of the new rules pertaining to the GD&T methodology is put off until the next section, it is here considered opportune to recall some basic definitions in the context of what is now defined, in the rules and in practice, as GPS, that is, Geometrical Product Specification.</p>
<p align="justify">Geometrical product specifications (GPS) defines a number of new concepts that have the potential of revolutionising the specification and verification domain, thereby enabling a designer to completely and unambiguously express the functional requirements in the technical documentation of products.</p>
<p align="justify">The basic tools of the GPS language are given in the ISO 17450 and ISO 14660 standards. According to the ISO 14660/1 standard, the geometrical features can be found in three domains:</p>

 - the specification domain, where several representations of the future workpiece are imaged by the designer;
- the workpiece domain, that is, the physical world domain;
- the inspection domain, where a representation of a given workpiece is used through the sampling of the workpiece with measuring instruments.
<p align="justify">Table 2.1 shows some basic concepts of ISO 14660/1, which are often referred to in the ISO 17450/1 standard as the definitions of integral, associated and derived features.</p>
<p align="justify">An integral feature is a geometrical feature that pertains to the real surface of a workpiece or to a surface model. An associated feature is an ideal feature that is established from a non-ideal surface model or from a real feature through an association operation. A derived feature is a geometrical feature that does not exist physically on the real surface of a workpiece, but which can be established from a nominal feature, an associated feature, or an extracted feature. The centre of a sphere is a derived feature obtained from a sphere, which is itself an integral feature. The median line of a cylinder is a derived feature that is obtained from the cylindrical surface, which is an integral feature (Fig. 2.1). The axis of a nominal cylinder is a nominal derived feature.</p>
<p align="justify">In metrology, through the use of a CMMmeasuringmachine, the extracted feature (integral or derived, that is, an approximated representation of the real feature, which is acquired by extracting a finite number of points) is obtained from the real integral feature (Fig. 2.2). A perfect associated feature (a cylinder or the derived axis, which can be used, for example, as a datum) can thus be obtained from the extracted features.</p>
<center>Table 2.1 Relationship of the three domains and the feature types</center>
![](https://pics.caxer.net/2024/05/81aefab004b174b9ef88092f41c313d4.png)
![](https://pics.caxer.net/2024/05/d9a18f0b442904e0603540efdd26d608.png)
<center>Fig. 2.1 Illustration of the process adopted to build an extracted median line: an extracted median line is a set of 2D-associated centres</center>
![](https://pics.caxer.net/2024/05/f9c7d9576f77c37ce15afb6fe6f49e29.png)
<center>Fig. 2.2 The ISO 14660/1 standard provides terms that allow an engineer to understand the impact of the drawing specifications on inspection. A nominal integral feature is a theoretically exact feature that has been defined in a technical drawing. A nominal derived feature is an axis that has been derived from one or more integral features. Extracted and associated features are parts of the inspection domain. An associated integral feature is an integral feature of a perfect form associated with the extracted integral feature. An associated derived feature is an axis or centerplane of a perfect form.</center>
<p align="justify">The “world” of manufacturing disappears in ISO 17450/1:2011, where it is replaced by the “world” of specification. ISO 17450 is in fact aimed at expressing the fundamental concepts on which the geometrical specification of workpieces can be based, including all the geometrical tools needed in GPS.</p>
According to this standard, the geometrical features exist in three “worlds”:

1. <p align="justify">the nominal definition world, where an ideal representation of the workpiece is defined by a designer with a perfect form, i.e. with the shape and dimensions necessary to meet the functional requirements (Fig. 2.3). This workpiece is called the “nominal model”, and it is impossible to produce or inspect since each manufacturing or measuring process has its own variability or uncertainty.</p>
2. <p align="justify">the specificationworld, where a designer, from the nominal geometry, imagines a model of this real surface, which represents the variations that could be expected on the real surface of the workpiece. This model, which represents the imperfect geometry of the workpiece, is called the “non-ideal surface model”. The nonideal surface model is used to simulate variations of the surface at a conceptual level (see Fig. 2.4), thereby optimising the maximum permissible limit values for which the function is downgraded but still ensured. Thesemaximum permissible limit values define the tolerances of each characteristic of the workpiece.</p>
3.  <p align="justify">the verification world, where a metrologist defines the sequence of operations that will be used during the measuring process. Themetrologist reads the specification of the non-ideal surface model, in order to define the individual steps of the verification plan, (i. e. the mathematical and physical operations of the sampling of the workpiece). The measurement, through the so-called duality principle defined in ISO 17450–1, can mirror the specification operation for operation. Conformance is then determined by comparing the specified characteristics with the result of the measurement (see Fig. 2.5).</p>
<p align="justify">The specification process is the first process to take place in the definition of a product or a system. The purpose of this process is to translate the designer’s intent into a requirement or requirements for specific GPS characteristics. The designer is responsible for the specification process, which comprises ensuring the following steps (Fig. 2.6):</p>
1.  feature functionality, i. e. the desired design intent of the GPS specification;
2.  GPS specification, which consists of a number of GPS specification elements each of which controls one or more specification operations;
3. specification operations, which are defined as an ordered set of operations and can be thought of as a virtual measurement instruction, where each operation and the parameters that define such an operation are steps in the measuring process.
![](https://pics.caxer.net/2024/05/b7b87d2f8c5c54435106dfeb8907b6d1.png)
<center>Fig. 2.4 The non-ideal surface model is used to simulate variations of the surface at a conceptual level, thus optimising the maximum permissible limit values for which the function is downgraded but still ensured</center>
<p align="justify">Aspecification operator is necessary to define, for example, a possible specific “diameter” in a cylinder (two-point diameter, minimum circumscribed circle diameter, maximum inscribed circle diameter, least squares circle diameter, etc.), instead of the generic “diameter” concept. A specification involves expressing the field of permissible deviations of a characteristic of a workpiece as the permissible limits. There are two ways of specifying the permissible limits: by considering the dimension or by specifying the zone that limits the permissible deviation of a non-ideal feature inside a space.</p>
<p align="justify">This is a new, more complicated approach than the previous methodologies, but it offers the designer more opportunities and more powerful tools to define the expected functional requirements with the maximum allowed tolerance.</p>
![](https://pics.caxer.net/2024/05/696d6759d51a86118ae88ab70b461fdd.png)
<center>Fig. 2.5 The GPS duality principle pertaining to the specification and verification procedures: the metrologist reads the specification of the non-ideal surface model, in order to define the individual steps of the verification plan. Conformance is then determined by comparing the specified characteristics with the measurement result</center>
## 2.2 Classification of Geometric Tolerances
<p align="justify">It is necessary to reiterate that dimensional errors (pertaining to the length and diameters) and form errors can be encountered in the manufacturing of a component, but also in the orientation and/or location between two features of a part, such as in the previous examples; geometrical type tolerances can in fact be divided into four categories:</p>
1. <p align="justify">Form tolerances, which establish the variation limits of a surface or a single feature of the ideal form indicated in the design. The form of an isolated feature is correct when the distance of each of the points of an ideal geometric surface, which are in contact with the datum, is equal to or less than the indicated tolerance; it should be pointed out that the tolerances on the profiles constitute a group on their own, in that they not only establish the limits of variation of the absolute form, but also the location and orientation of a surface or of any line, with respect to a possible datum.</p>
2. <p align="justify">Orientation tolerances, which establish the limits of variation of a surface o a single feature with respect to one or more features assumed as a datum. The datum feature may be an already existing feature of the part, and its form should be sufficiently precise for it to be used as such.</p>
3. <p align="justify">Location tolerances, which establish the limits of variation of a surface or a single feature with respect to an ideal location, as established in the design process, and to one or more features assumed as a datum.</p>
4. <p align="justify">Run-out tolerances, which establish the limits of variation of a surface or single feature with respect to a form and a location, established in the design phase, during the rotation of a piece around a reference feature.</p>
![](https://pics.caxer.net/2024/05/9dbcdc8cdeb28ddb329c761b2d2ef373.png)
<center>Fig. 2.6 The specification operations, defined as an ordered set of operations can be thought of as a virtual measurement instruction, where each operation and the parameters that define such an operation are steps in the measuring process. The permissible limits are specified by the application of the tolerance zones according to the ISO 1101:2017 standard</center>
<p align="justify">The chart in Table 2.2 shows the characteristic geometrical symbols used for geometrical tolerancing and the four tolerance types into which these symbols are divided. The symbols are explained in more detail later on.</p>
<p align="justify">As can be seen from the table, some non-associable tolerances (for instance, planarity, roundness, etc.) do not refer to other features of a part, taken as a datum; some geometrical characteristics require a datum (such as parallelism or the location of a hole) and other tolerances that may ormay not be associated with another feature, such as tolerances on profiles.</p>
<p align="justify">In other words, while a form error concerns an isolated feature (such as a flat surface), an orientation or location error is associated with another feature of the workpiece, which is known as the datum feature (more details of which will be presented in the next sections, together with details on how such a feature should be indicated). In short, a geometrical tolerance defines a space (either bi-dimensional or three-dimensional)within which the feature that has to be controlledmust remain. For example, a feature of a plane, forwhich one wishes to control the straightness, should remain within the area defined by two straight parallel lines at the same distance as the tolerance value; the tolerance zone in the 3D space should be a cylinder with a
perfectly straight axis and generatrix, and with the diameter equal to the tolerance value.</p>
<p align="justify">Some typical forms of tri-dimensional tolerance zones are visible in Fig. 2.7, together with indications on the relative dimensions.</p>
<center>Table 2.2 Classification, types and symbols of geometrical tolerances</center>

| Tolerances          | Geometric attributes                              | Datum  | Geometrical characteristic                                                    |     
| ------------------- | ------------------------------------------------- | ------ | ----------------------------------------------------------------------------- |
| Form                | Does not control<br>size, orientation or location | NO     | Straightness<br>Flatness<br>Roundness<sup>2</sup><br>Cylindricity             |    
| Profile             | Form, size, orientation<br>and location control   | YES/NO | Line profile<sup>3</sup><br>Surface profile<sup>4</sup>                       |   
| Orientation         | Does not control size or location<sup>5</sup>     | YES    | Parallelism<br>Perpendicularity<br>Angularity                                 |    
| Location            | Does not control form or size                     | YES    | Position <br>Concentricity<sup>6</sup> and coaxiality<br>Symmetry<sup>6</sup> |   
| Run-out<sup>7</sup> | Does not control size                             | YES    | Circular run-out<br>Total run-out                                             |     


<sup>2</sup> Circularity in ASME

<sup>3</sup> Profile of a line in ASME

<sup>4</sup> Profile of a surface in ASME

<sup>5</sup> The orientation controls form when applied to a flat surface

<sup>6</sup> Both concentricity and symmetry have been removed from the ASME Y14.5:2018

<sup>7</sup> Runout in ASME

![](https://pics.caxer.net/2024/05/9cd992ad050654d5a44f088ed66c10e4.png)
<center>Fig. 2.7 Some typical forms of three-dimensional tolerance zones</center>
## 2.3 The SpecificationWorld: Types and Symbols of Geometrical Tolerances
### 2.3.1 ISO Tolerance Indicator
<p align="justify">According to the aforementioned standard, that is, ISO 1101, geometrical tolerances should be indicated on drawings by means of a rectangular frame (ISO: tolerance indicator, ASME: feature control frame) divided into two or more compartments (Fig. 2.8). The compartments should contain, from left to right, the following indications in the same order:</p>
1. <p align="justify">the symbol of the geometrical tolerance, according to Table 2.2;</p>
2. <p align="justify">the total tolerance value of themeasurement unit used for the linear dimensions. This value is preceded by the sign Ø if the tolerance zone is round or cylindrical; another indication can be given in this compartment, that is, a capital letter inserted into a circle, which is used to prescribe the so-called “modifiers”, such as, for example, the application of the requirement of the maximum material, and so on, which modify the tolerance value;</p>

3. <p align="justify">the letter or letters that identify the datum features, whenever necessary, which may be followed by the indication of modifiers.</p>
![](https://pics.caxer.net/2024/05/71077347e63a2c567c204210d88a2324.png)
<center>Fig. 2.8 The tolerance indicator decoding process</center>

<p align="justify">Any necessary annotations may be written either above or close to the tolerance indicator (for example, “6 x”, as in Fig. 2.9) or joined to the frame by means of a leader line. If more than one geometrical tolerance is indicated on the same feature, the indications should be reported in overlapping compartments, as shown in Fig. 2.10.</p>
![](https://pics.caxer.net/2024/05/bf46fa0830a50816e91eff88a9ce34c2.png)
<center>Fig. 2.9 Examples of geometrical specifications with a tolerance indicator. The geometrical specification indication should be connected to the leader line by a reference line. The reference line should be attached to the mid-point of the left-hand side or the right-hand side of the tolerance indicator</center>
![](https://pics.caxer.net/2024/05/134a87dd88f1f7f58df424183f3764bb.png)
<center>Fig. 2.10 If more than one geometrical tolerance is indicated on the same feature, the indications should be reported in overlapping compartments. In this case, it is recommended that the tolerance indicators are arranged so that the tolerance values are shown in descending order, from top to bottom</center>
### 2.3.2 Drawing Geometrical Specifications
The tolerance frame is connected to a toleranced feature by a leader line, with an arrow at the end:

1. <p align="justify">on the contour line of the feature or on an extension line of the contour (but clearly separate from a measurement line), if the tolerance is applied to a line or surface (Fig. 2.11); it is also possible to use a reference line that points directly to the surface.</p>
2. <p align="justify">According to ISO/CD 16792:2011, pertaining to the definition of 3D digital products, leader lines that have the aim of representing line elements should terminate with an arrowhead, see Fig. 2.12. When an indicated element is a surface, the leader line should terminate with a dot within the bounds of the surface.</p>
3. <p align="justify">as an extension of the dimension line, if the tolerance applies to a derived feature (axis, median line, median surface or a centre point, Fig. 2.13).</p>
![](https://pics.caxer.net/2024/05/319a9e2acc332c59312a63467744172b.png)
<center>Fig. 2.11 Indication of an integral feature specification</center>
![](https://pics.caxer.net/2024/05/d829865482cf0d39fb6f30112f42cb96.png)
<center>Fig. 2.12 In 3D annotation, when an indicated element is a surface, the leader line should terminate with a dot within the bounds of the surface</center>
![](https://pics.caxer.net/2024/05/845743d91dee06cafb609385c4718280.png)
<center>Fig. 2.13 Indication of a derived feature specification</center>
<p align="justify">The direct joining of a reference element to the frame through a leader line, with the omission of the datum letter, should be avoided. The practice of directly connecting a tolerance indicator with a leader line terminating with an arrow directly to the axis has been deprecated (Fig. 2.14); see Fig. 2.13 for the preferred indications.</p>
<p align="justify">The letter that indicates the datum feature should be reported in the frame, as shown in Fig. 2.15. Although a single datum feature is identified by just one single capital letter (Fig. 2.15a), a common datum, established from two features, should be identified by two different letters separated by a hyphen (Fig. 2.15b).</p>
<p align="justify">As will be seen later on, the datum system is not only useful to establish the functional relationships between several features, but also to indicate the sequence that has to be followed to control the geometrical tolerance of a part; this means that, in the case of several datums, the relative letters should be indicated in consecutive compartments in the frame (Fig. 2.15c), in priority order from left to right.</p>
![](https://pics.caxer.net/2024/05/8eb6fa65af7a01d29d86a8c6724f1955.png)
<center>Fig. 2.14 It was former practice to connect the tolerance indicator directly to the datum feature by means of a leader line or to connect the tolerance indicator by a leader line terminating with an arrow directly to the axis</center>
![](https://pics.caxer.net/2024/05/35d54c1442265ccaba65a3e7e6ee47b9.png)
<center>Fig. 2.15 Indication of a single datum feature (a), a common datum established from two features (b) and three datums, in priority order, from left to right (c)</center>
<p align="justify">If the tolerance is applicable to a limited length, which is not defined as a location, the value of this length should be added to the tolerance value and separated from it by an oblique stroke. If a more restrictive tolerance on a limited length is added to another tolerance on a feature, the tolerance indicator should be placed below the other, as indicated in Fig. 2.16.</p>
<p align="justify">If the tolerance (or datum) only has to be applied to a restricted area of a feature, it should be identified (with locations and dimensions defined according to Theoretically Exact Dimensions (TED), as indicated in Fig. 2.17, using a chain line (line 4.2 in ISO 128–24).</p>
<p align="justify">Inserting a circle, in correspondence to the junction of the leader line of the tolerance (Fig. 2.18), indicates that the geometric control applies to the entire external boundary (all around), while two circles indicate that a profile tolerance, or other specification, applies over the entire three-dimensional profile of a part (all over). An “all around” or “all over” symbol should always be combined with an SZ (separate zones), CZ (combined zone) or UF (united feature) specification element, except for when the referenced datum system locks all non-redundant degrees of freedom (see the next section).</p>
![](https://pics.caxer.net/2024/05/b96d45a7e61b22ecd3e3225cb7a114ee.png)
<center>Fig. 2.16 Indication of restrictive specifications. If two or more specifications of the same feature have to be indicated, they may be combined. they may be combined</center>

### 2.3.3 Additional Symbols of the ISO 1101 and ISO 5458 Standards
<p align="justify">The ISO 1101:2017 standard has defined a newsymbol to specify the derived features of a revolute surface (axis or median line), that is, the modifier A (median feature) is placed in the tolerance section of the tolerance indicator. In this case, the leader line does not have to terminate at the dimension line, but can terminate with a dot on the integral feature, an arrow on the outline or an extension line, as shown in Fig. 2.19.</p>
<p align="justify">Another useful indication that is used to specify the constraints on the tolerance zone is the Combined Zone, which is indicated as CZ, and which is used to control the tolerance zone applied to several surfaces with the aim of establishing a common tolerance zone that can be applied simultaneously to the indicated surfaces (Fig. 2.20). In this case, all the relative tolerance zones should be individually constrained, as far as the location and orientation between each other are concerned, even through the Fuse of either explicit or implicit theoretically exact dimensions (TED) (Fig. 2.21).</p>
![](https://pics.caxer.net/2024/05/fb06e8d58cc94094093c3f83e0a0a094.png)
<center>Fig. 2.17 Indication of a restrictive area toleranced feature</center>
#### 2.3.3.1 Indications Adjacent to the Tolerance Indicator
<p align="justify">A geometrical specification indication consists of a tolerance indicator with some optional adjacent indications.When there is only one tolerance indicator, indications in the upper/lower adjacent indication areas and in the in-line adjacent indication area mean the same. In this case, only one adjacent indication area should be used and it is preferable to use the upper adjacent indication area, if possible (Fig. 2.22).</p>
<p align="justify">Table 2.3 shows other additional symbols (plane and feature indicators), that can be used to control the geometrical errors and allowthe verificationmethodology to be specified in an unambiguous manner. Intersection plane, orientation plane, direction feature and collection plane indicators can be indicated in the in-line adjacent to the tolerance indicator.</p>
![](https://pics.caxer.net/2024/05/de2134868b9f00564b78f1729ecfa660.png)
<center>Fig. 2.18 All around specification: a geometrical specification is applied to the outlines of the cross-sections or when it is applied to all features represented by a closed outline. The all over symbol indicates that a geometrical specification is applied to all integral features of a workpiece</center>
![](https://pics.caxer.net/2024/05/7102569ebd28ebdb19cf02c375edc372.png)
<center>Fig. 2.19 In the case of a revolute, the derived median line can be indicated by a modifier (median feature) placed in a specific section of the tolerance indicator. In this case, the leader line does not have to terminate on the dimension line</center>
![](https://pics.caxer.net/2024/05/fc2d35e9cf6a6b2ccc9a3cb6d6e33e9e.png)
<center>Fig. 2.20 The CZ symbol for the combined zone specification that applies to several features</center>
![](https://pics.caxer.net/2024/05/80c3cc13f462560f6cf067147853ecb7.png)
<center>Fig. 2.21 All the related individual tolerance zones should be constrained in location and in orientation between each other using either explicit theoretically exact dimensions (TED), or implicit TEDs</center>
<p align="justify">For example, the use of the intersection plane indications (specified through the use of an intersection plane indicator placed, as an extension, to the right of the tolerance indicator) makes the identification of the bi-dimensional tolerance zone possible, regardless of which projection is used (Fig. 2.23), and it is therefore very useful for 3D dimensioning (Fig. 2.24).</p>
![](https://pics.caxer.net/2024/05/bb7f0cb3b9e4993c101bf8cb90e1e57b.png)
<center>Fig. 2.22 Indications adjacent to the tolerance indicator</center>

<center>Table 2.3 Roles and symbols that can be used with intersection plane, orientation plane, direction feature and collection plane indicators</center>
![](https://pics.caxer.net/2024/05/9d2fefa34cc88b5caaa6afaa69b18b49.png)
<p align="justify">The letter that identifies the datum used to establish the intersection plane is placed in the second section of the intersection plane indicator. The symmetry symbol is used to indicate that the intersection plane includes the datum. </p>
<p align="justify">Figure 2.25 illustrates the use of a straightness tolerance on a flat surface as indicated in the ASME Y14.5:2018 standard. The intersection plane is not used, but the direction of the prescribed straightness tolerance is indicated by means of an orthographic view or by a line as a supplemental geometry in the 3D model.</p>
![](https://pics.caxer.net/2024/05/e57888277049d0d55c1074a04eaceec7.png)
<center>Fig. 2.23 Specification using an intersection plane indicator. The toleranced feature is made up of all the lines of a feature in a given direction, and the intersection plane is used to identify the orientation of the line requirements</center>
![](https://pics.caxer.net/2024/05/ceea1e60eca92abe678c1b602958b5b0.png)
<center>Fig. 2.24 In 3D annotation, the intersection plane should be indicated to avoid misinterpretation of the toleranced feature</center>
![](https://pics.caxer.net/2024/05/75a4cc54c062a6cd46e9fbf1136c8917.png)
<center>Fig. 2.25 Straightness applied to control line elements in multiple directions on a flat surface in the ASME Y14.5:2018 standard; the direction of the prescribed straightness tolerance is indicated by two lines as a supplemental geometry in the 3D model</center>
<p align="justify">The orientation plane indicator controls both the orientation of the planes that limit the tolerance zone (directly, by means of the datum and the symbol in the indicator) and the orientation of the width of the tolerance zone (indirectly, perpendicular to the planes), or the orientation of the axis for a cylindrical tolerance zone. A typical application used to control the angle of an axis is shown in Fig. 2.26, as an alternative to the previous methodology, which foresaw the indication of two datums.</p>
![](https://pics.caxer.net/2024/05/bb431273977ddc17cc8715fdbba145fe.png)
<center>Fig. 2.26 The cylindrical tolerance zone is parallel to datum plane B and inclined at the specified angle to datum plane A; the orientation plane is used to avoid the presence of two datum features in the tolerance indicator</center>
<p align="justify">The new standard, that is, standard 1101 of 2017, has also clarified a misunderstanding that had existed for some time pertaining to the previous versions and which has finally been resolved, that is, the indication of the direction of the tolerance zone of roundness.</p>

<p align="justify">In fact, the old 1101 standard foresaw, in Sect. 8.1, that “the amplitude of all the roundness tolerance zones, if not otherwise expressed, shall always be developed in an orthogonal direction to the surface of the feature that had to be controlled”. However, just a few lines later, at the end of the section, two lines, which stated “in the case of roundness, the amplitude of the tolerance zone shall be applied in an orthogonal direction to the nominal axis of the piece” appeared in a cryptic way.</p>
<p align="justify">Instead, in the new version, in Sect. 7.1, the new standard specifically states, notwithstanding what is prescribed by default, that the new “direction feature” symbols should be used for surfaces that are not round or cylindrical to specify how the tolerance is applied. Therefore, a direction indicator should always be indicated for the roundness of conical features. In Fig. 2.27, for both the cylindrical and conical surfaces, the extracted circumferential line, in any cross-section of the surfaces, should be contained between two coplanar concentric circles, with a difference in radii of 0,03. This is the default value for the cylindrical surface and is indicated by means of the direction feature indicator for the conical surface.</p>
<p align="justify">The tolerance zone defined by the specification in Fig. 2.28 is limited, in the considered cross-section, by two circles on a conical surface 0,1 mm apart along the surface.</p>
![](https://pics.caxer.net/2024/05/a9926d3c76640064c803dfe6d00ac25d.png)
<center>Fig. 2.27 The extracted circumferential line should be contained between two coplanar concentric circles, with a difference in radii of 0,03, for both cylindrical and conical surfaces, in any crosssection of the surfaces perpendicular to an axis. This is the default value for the cylindrical surface and it is indicated by means of the direction feature indicator for a conical surface</center>
![](https://pics.caxer.net/2024/05/47d9e617aee34dbd76d595f9a7dca731.png)
<center>Fig. 2.28 The extracted circumferential line in the conical component on the right should be contained between two circles on the intersecting cone, 0.1 apart. The tolerance zone is perpendicular to the surface of the toleranced feature, as indicated by the direction indicator</center>
<p align="justify">The collection plane symbol establishes a family of parallel planes, which identifies a closed boundary of contiguous features covered by the “all around” symbol. Indeed, if a geometrical specification is applied to all the features represented by a closed outline, it should be indicated by the “all around” symbol together with a collection plane indicator in order to make the drawing unambiguous (see Fig. 2.29), especially for 3D annotations.</p>
<p align="justify">In Fig. 2.30, as the “all around” symbol is used with a UF modifier (Unified Feature), the tolerance applies to a united feature which includes the features that make up the periphery of the workpiece when seen in a plane parallel to datum B, as indicated by the collection plane indicator. Basically, a collection plane identifies a set of single features whose intersection with any plane parallel to the collection plane is a line or a point.</p>
<p align="justify">If the specification applies to any cross section or any longitudinal section of a feature, it should be indicated with the “ACS” specification modifier for any cross section orwith the “ALS” specificationmodifier for any longitudinal section. The two symbols can be placed above the tolerance frame (see Fig. 2.31a) or after the datum letter symbol in the tolerance frame (see Fig. 2.31b), with no change in meaning.</p>
![](https://pics.caxer.net/2024/05/506789d95204ac228151ab01a7fdddd6.png)
<center>Fig. 2.29 Without any indication of the collection plane, the symbol “all around” symbol is
ambiguously applied to all the features represented by a closed outline</center>
![](https://pics.caxer.net/2024/05/3d3d7b36c7071dc3dc4fda51dfc9672d.png)
<center>Fig. 2.30 Since the “all around” symbol and the UF modifier are used, the tolerance applies to a united feature consisting of the features that make up the periphery of the workpiece when seen in a plane parallel to datum B, as indicated by the collection plane indicator</center>
![](https://pics.caxer.net/2024/05/4f8084938c70ff4b483a8a6048032f9d.png)
<center>Fig. 2.31 The ACS and ALS symbols can both be placed above the tolerance frame (a, c) or after the datum letter symbol in the tolerance frame (b, d), with no change in meaning
</center>

<p align="justify">When the ACS modifier is indicated, the toleranced feature and the datum feature are defined in the same cross-section. The intersection plane that defines the toleranced feature is by definition a plane perpendicular to the median feature of the associated feature, as established from the extracted integral surface.</p>
<p align="justify">Indicating “ALS” above the tolerance frame (see Fig. 2.31c) or after the datum letter symbol (see Fig. 2.31d), allows the datum feature to be defined as any longitudinal section of the integral feature (concurrently with the toleranced feature). The datum feature is the intersection of the real integral feature used to establish the datum and the section plane. A longitudinal section is defined as a half plane that includes an axis.</p>
<p align="justify">Figure 2.32 shows an example of the use of a rank-order specification with ALS and ACS modifiers, according to ISO 14405/1.</p>
<p align="justify">Figure 2.33 indicates the use of the between symbol adjacent to the tolerance indicator and identifies the two locations where each value applies. In this case, a proportional variation is defined from one value to another, between two specified locations, on the considered feature.</p>
![](https://pics.caxer.net/2024/05/f64b858cc661033b32c0c97b89595dbc.png)
<center>Fig. 2.32 Example of the use of a rank-order specification with ALS and ACS modifiers. For the upper indication, an upper limit (0,004) applies to the range of the two-point size values defined in any cross section. For the lower indication, an upper limit (0,006) applies to the range of the two-point size values defined in any longitudinal section</center>

![](https://pics.caxer.net/2024/05/ac78ce73e11bcd89117e6e9649050a5a.png)
<center>Fig. 2.33 Drawing with indications of the variable width specification using the between symbol</center>

<p align="justify">In the ASME Y14.5:2018 standard, the profile tolerance, with a proportional variation between two specified locations on the considered feature, is indicated with the new From-To symbol, which is located below the tolerance frame. In Fig. 2.34, the tolerance width varies proportionally from 0.1 at S to 0.3 at T.</p>
#### 2.3.3.2 Associated Toleranced Feature Specification Elements


<p align="justify">Another important novelty of ISO 1101 is the introduction of newmodifiers that allow the tolerance to be applied, not to the extracted feature (derived or integral), as the standard default foresees, but to an associated feature, utilising various association criteria, with the letters C,G,N, T and X. In fact, in the case of Fig. 2.35, a location error is prescribed to which the real feature should not be subjected, but rather the associated feature, for example, with the maximum envelope criterion (modifier X), or the associated tangent plane (modifier T, which already existed in the ASME standard). Considering that an associated feature is ideal (and therefore without form errors), this option can only be applied to orientation or location tolerances.</p>
<p align="justify">As can be seen in Sect. 2.1, an associated feature is an ideal feature that is established from a real feature through an association operation. By default, the reference feature association is the minimax (Chebyshev) association without constraints and it can be used for form specifications, but it is also possible, as an alternative, to indicate the reference feature association specification element as in Fig. 2.36. Table 2.4 shows the symbols and the relative meanings of the associated criteria. E, I should be used to indicate the criteria association with the constraint external (E) and internal (I) to the material.</p>
<p align="justify">The filter specification is an optional specification element which is indicated by a combination of two specification elements, that is, the type of filter and the nesting index or indices for the filter (Fig. 2.37).</p>
![](https://pics.caxer.net/2024/05/9724f3a72bbbed85cb5a9fecdd70b220.png)
<center>Fig. 2.34 The profile tolerance in the ASME Y14.5:2018 standard, with a proportional variation between two specified locations on the considered feature, is indicated with the newFrom-To symbol located below the tolerance frame. The tolerance width in the figure varies proportionally between 0.1 at S and 0.3 at T</center>
![](https://pics.caxer.net/2024/05/c90696e704c9632fa15580d8ee066724.png)
<center>Fig. 2.35 The location error to which the real feature should not be subjected, but an associated feature, for example, a position specification that applies to the associated maximum inscribed feature (modifier X) is instead prescribed here</center>
![](https://pics.caxer.net/2024/05/f2f387d90faf8107e29dc524215e91b6.png)
<center>Fig. 2.36 Cylindricity control with indication of the association of the two reference features (maximum inscribed and Gaussian association). The modifier X maximises the size of the reference feature, while maintaining it entirely inside the toleranced feature. G should be used to indicate the least squares (Gaussian) association. It minimises the square of the local deviations of the toleranced feature to the reference feature</center>
<center>Table. 2.4 Associated toleranced feature specification elements. The symbol inside the circle in the second column indicates that the tolerance is applied to the associated element. The symbol in the third column indicates the association criterion and is usually applied to form tolerances</center>

|                          | Associated toleranced feature | Reference feature association |
| ------------------------ | ----------------------------- | ----------------------------- |
| Minimax (Chebyshev)      | C                             | C, CE, CI                     |
| Least squares (Gaussian) | G                             | G, GE, GI                     |
| Minimum circumscribed    | N                             | N                             |
| Maximum inscribed        | X                             | X                             |
| Tangent feature          | T                             | --                            |

![](https://pics.caxer.net/2024/05/29c10a9ff11113676b6c675e12d959a3.png)
<center>Fig. 2.37 Roundness specification with a minimum circumscribed reference feature after the application of a Gaussian long-wave pass filter with a cutoff value of 50 UPR</center>


### 2.3.4 New Symbols and Specification Modifiers of ISO 5458:2018

<p align="justify">The new ISO 5458:2018 standard establishes rules that may be considered complementary rules to ISO 1101 to apply to pattern specifications. According to the independency principle (ISO 8015:2011, 5.5), a geometrical specification that applies to more than one single feature by default also applies to those features independently. The tolerance zones defined by one tolerance indicator or by several tolerance indicators should therefore be considered independently by default.</p>
<p align="justify">The new standard has introduced a new definition of internal constraints (location constraint and/or orientation constraints between the individual tolerance zones of the tolerance zone pattern) using the CZ,CZR or SIM modifiers (Table 2.5).</p>
<p align="justify">There are two ways of creating a tolerance zone pattern, that is, either by using a single indicator pattern specification with the CZ or CZR modifiers, or by using a multiple indicator pattern specification using SIM modifiers (Fig. 2.38).</p>
<center>Table. 2.5 Symbols and specification modifiers in the ISO 5458:2018 standard</center>
<table>  
    <tr>  
      <th>Applied to</th>  
      <th>Symbol</th>  
      <th>Description</th>  
      <th>Constraint</th>  
    </tr>  
    <tr>  
      <td>Toleranced feature</td>  
      <td>UF</td>  
      <td>United feature</td>  
      <td>Not applicable</td>  
    </tr>  
    <tr>  
      <td rowspan="4">Tolerance zone</td>  
      <td>SZ</td>  
      <td>Separate zones</td>  
      <td>None</td>  
    </tr>  
        <tr>  
      <td>SIM i</td>  
      <td>Simultaneous requirement No. i</td>  
      <td>Orientation and location</td>  
    </tr>  
    <tr>  
      <td>CZ</td>  
      <td>Combined zone</td>  
      <td>Orientation and location</td>  
    </tr>  
    <tr>  
      <td>CZR</td>  
      <td>Combined zone rotational only</td>  
      <td>Orientation constraint only</td>  
    </tr>  
</table>

![](https://pics.caxer.net/2024/05/aa966eacff341df76bcf270109b95b16.png)
<center>Fig. 2.38 There are two ways of creating a tolerance zone pattern, that is, either by using a single indicator pattern specification with the CZ or CZR modifiers or by using a multiple indicator pattern specification using SIM modifiers</center>


