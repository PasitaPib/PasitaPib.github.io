---
title: Additive Manufactured Autoclave Mold Durability
subtitle: Investigation of Creep Deformation of a Printed Autoclave Tool

caption:
  title: Additive Manufactured Autoclave Mold Durability
  subtitle: Testing/Data Analysis
  thumbnail: assets/img/portfolio/proj8/Picture2.png
---
<p style="text-align:justify">
<strong>Project Team</strong>: Pasita Pibulchinda, Vasudha Kapre, Dr. Eduardo Barocio, Dr. R. Byron Pipes<br>

<p style="text-align:justify">
Overview: The shape of a curvilinear tool printed with 50% wt. PET polyester glass fiber-filled structural compound was characterized after performing 10 autoclave cycles at 350 °𝐹 (180 °𝐶), 80 𝑃𝑆𝐼 (5.52 𝐵𝑎𝑟). A deviation analysis was carried out with respect to the initial shape of the printed tool to investigate the creep deformation accumulated after each autoclave cycle. The surface deviations after ten autoclave cycles were on average within +3.5 𝑚𝑚 and −3.0 𝑚𝑚.  

</p>
<figure>
<img src="/assets/img/portfolio/proj8/Picture1.png" alt="EDAM systems" width="100%">
<figcaption>Fig. 1 - Tool geometry for autoclave testing of the additively manufactured Arnite ID8527</figcaption>

<p style="text-align:justify">
<strong>Composite Layup</strong>:
A layup was designed with all the fibers oriented in the same direction. The figure below shows the geometry of the plies obtained by flattening the surface of the tool. The warp and weft in the plain weave were oriented along the X-direction and Y-direction, respectively. Plies were cut with a numerically controlled Gerber cutter.

</p>
<figure>
<img src="/assets/img/portfolio/proj8/Picture2.png" alt="EDAM systems" width="100%">
<figcaption>Fig. 2 - Ply geometry utilized in the composite layup </figcaption>

<p style="text-align:justify">
<strong>Tool Surface Conditioning</strong>:The tool was additively manufactured in a Big Area Additive Manufacturing (BAAM) system with 50% by weight of glass fiber (GF) reinforced polyethylene terephthalate (PET). The surface was smoothed by a CNC, cleaned, sealed, and coated with a semi-permanent release agent.
</p>
<figure>
<img src="/assets/img/portfolio/proj8/Picture3.png" alt="EDAM systems" width="100%">
<figcaption>Fig. 3 - Tool Printing and Surface Conditioning</figcaption>

<p style="text-align:justify">
<strong>Test Method</strong>:
A layup consisting of three plies of plain weave carbon fiber-epoxy prepreg IM7-8552. Followed by one layer of release film (PTFE) and one of breather material to distribute the vacuum across the tool. Synthetic rubber tape (tacky tape) was applied along the edges of the tool to install the vacuum bag. Ports were also installed to supply vacuum to the setup. Lastly, a 5-minute vacuum test was conducted before transferring to autoclave. The standard cure cycle was carried out with a maximum temperature of 350 °𝐹 and with 80 𝑃𝑆𝐼 of pressure. The tool was subjected to ten autoclave cycles.


</p>
<figure>
<img src="/assets/img/portfolio/proj8/Picture4.png" alt="EDAM systems" width="100%">
<figcaption>Fig. 4 - Tool Printing and Surface Conditioning</figcaption>

<p style="text-align:justify">
<strong>Parts Produced with printed tool</strong>:After completing the autoclave cure cycle, the vacuum bag was removed, and the composite part was released from the tool. The leftover resin on the tool was also removed.

</p>
<figure>
<img src="/assets/img/portfolio/proj8/Picture6.jpg" alt="EDAM systems" width="100%">
<figcaption>Fig. 5 - Demolded parts</figcaption>

<p style="text-align:justify">
<strong>Shape Change Measurement</strong>:
The shape change of the tool was characterized utilizing a Faro® ScanArm® HD equipped with a laser line scanner. Point clouds were collected after each curing cycle and post-processed using Geomagic Wrap® 2015. A deviation analysis was carried out with respect to the baseline and each point cloud was trimmed and filtered, aligned to the baseline’s point cloud. The deviations computed in Geomagic Wrap® 2015 correspond to the normal distance measured from the surface of the baseline to each of the points in the point cloud. 
</p>
<figure>
<img src="/assets/img/portfolio/proj8/Picture7.png" alt="EDAM systems" width="100%">
<figcaption>Fig. 6 - Shape changes measurement process</figcaption>

<p style="text-align:justify">
<strong>Result</strong>:
The printed tool deformed after the first cycle and continued changing shape in subsequent autoclave cycles. The figure below shows the surface deviation after the first, the fifth, and the tenth autoclave cycles. Surface deviations are computed with respect to the baseline surface. The surface deviations after ten autoclave cycles were on average within +3.5 𝑚𝑚 and −3.0 𝑚𝑚.
</p>
<figure>
<img src="/assets/img/portfolio/proj8/Picture8.png" alt="EDAM systems" width="100%">
<figcaption>Fig. 7 - Evolution of the surface deviation (A) after one cycle (B) five (C) ten autoclave cycles. Red regions displaced upwards and blue regions displaced downwards.</figcaption>
 
<p style="text-align:justify">
Cracks were visually identified around the edges of the tool on the seventh and subsequent cycles. These cracks spanned the thickness of the tool and located at the interfaces between adjacent layers.The deformation observed at the bottom surface of the tool also confirmed the pronounced increase in deviation observed after the first autoclave cycle. The region indicated as “1” in the tool corresponds to the surface deviation shown in the figure above.

<figure>
<img src="/assets/img/portfolio/proj8/Picture9.png" alt="EDAM systems" width="100%">
<figcaption>Fig. 8 - Deformation of the tool after the first autoclave cycle.</figcaption>

<p style="text-align:justify">
One way to achieve the desired AM manufactured geometry is to is to model and simulate the creep behavior of the tool considering the effect of manufacturing. Such a functionality is available in Additive3D, a physics based simulation workflow developed for Abaqus®. However, more characterization tests have to be done to obtain the material card, also a better understanding of the deformation of the geometry is necessary. This experimental results can be used to verify the simulation results.


- Date: September 2019

