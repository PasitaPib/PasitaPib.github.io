---
title: Composites Flow and Fiber Orientation Prediction
subtitle: Developed a simulation workflow to model the fiber-reinforced polymer composites deposition process using smooth particle hydrodynamic (SPH) to guide appropriate selection of process parameter
alt: 

caption:
  title: Composites Flow and Fiber Orientation Prediction
  subtitle: Research/Simulation
  thumbnail: assets/img/portfolio/Flow_Proj/4steps.gif
---
<div style="text-align: justify">
A printing process of Extrusion Deposition Additive Manufacturing (EDAM) in the Composite Additive Manufacturing Research Instrument (CAMRI) looks like this in slow motion. 
</div>
<br> 
<img class="img-fluid" src="assets/img/portfolio/Flow_Proj/CroppedTamperGIF.gif" alt="" style="padding-top=10px">
<div style="text-align: justify">
A numerical framework was developed in this study to investigate the influence of relevant Extrusion Deposition Additive Manufacturing (EDAM) processing conditions on the final fiber orientation, inter-bead void and cross-sectional geometry of the bead laid down as the extrudate. 

Specifically, four key processes of the EDAM process are studied. The simulations utilize an anisotropic viscous flow model implemented using the smoothed particle hydrodynamics method in Abaqus and fiber orientation vectors are evolved under the assumption of affine motion.The Abaqus user material (VUMAT) is from  <a href="https://pubs.aip.org/sor/jor/article/62/6/1443/1001527/Simulation-of-prepreg-platelet-compression-molding">2018 Favaloro et al. </a>

</div>
<br>
<div class="row">
      <div class="col-lg-6 mx-auto text-center align-self-center">
        <div class="large">
          (i) flow of 90° angle turn as the extrudate exits the nozzle and is laid down on the previous layer or the substrate
          <img class="img-fluid" src="assets/img/portfolio/Flow_Proj/FirstBeadDepo_1_NH3_V1_gif.gif">
        </div>
      </div>
      <div class="col-lg-6 mx-auto text-left align-self-center">
        <div class="large">
          (ii) flow of the bead during compaction
          <img class="img-fluid" src="assets/img/portfolio/Flow_Proj/FirstTamp_0785_NH3_1.gif">
        </div>
      </div>
</div>

<div class="row">
      <div class="col-lg-6 mx-auto text-center align-self-center">
        <div class="large">
          (iii) flow of an extrudate deposited adjacent to the previously compacted bead
          <img class="img-fluid" src="assets/img/portfolio/Flow_Proj/SecondDepo_0785_394OL_gif03.gif">
        </div>
      </div>
      <div class="col-lg-6 mx-auto text-left align-self-center">
        <div class="large">
          (iv) flow of the adjacent bead during compaction
          <img class="img-fluid" src="assets/img/portfolio/Flow_Proj/SecondTamp_0785_NH3_3.94-2.gif">
        </div>
      </div>
</div>

<div style="text-align: justify">
The simulation results are compared with experiments for printed bead geometries produced and this comparison was shown to validate the modeling approach as useful for predicting fiber orientation, bead geometry, and bead-to-bead contact interface geometry. 
</div>
<div class="row">
      <div class="col-lg-6 mx-auto text-center align-self-center">
        <div class="large">
          <img class="img-fluid" src="assets/img/portfolio/Flow_Proj/Print_EXP.gif">
        </div>
      </div>
      <div class="col-lg-6 mx-auto text-left align-self-center">
        <div class="large">
          <img class="img-fluid" src="assets/img/portfolio/Flow_Proj/EXP_vs_SPH.png">
        </div>
      </div>
</div>

<div style="text-align: justify">
The processing parameters considered are nozzle height from the substrate, the ratio of the print speed to the extrusion speed (V_b/V_e), and the bead-to-bead lateral overlap distance. A series of virtual experiments were conducted, and the following observations were noted: (i) the bead printed with a high nozzle height has significantly more fiber alignment in the printing direction than the lower nozzle height, (ii) the ratio of the print speed and extrudate speed, V_b/V_e, of greater than unity results in greater fiber alignment than for V_b/V_e<1.

</div>
<br> 
<img class="img-fluid" src="assets/img/portfolio/Flow_Proj/PrintParam.png" alt="">
<br>

The results of the finding is current on going. 

