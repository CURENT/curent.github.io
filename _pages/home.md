---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/CURENT_Logo_NameOnWhite.png
  overlay_filter: rgba(0, 0, 0, 0.5) # Optional: Add a filter for better contrast
  actions:
    - label: "<i class='fas fa-vial'></i> Try on Binder"
      url: "https://mybinder.org/v2/gh/curent/ams/master"
    - label: "<i class='fas fa-code'></i> Source code"
      url: "https://github.com/CURENT"
    - label: "<i class='fas fa-university'></i> CURENT Center"
      url: "https://curent.utk.edu/"
    - label: "<i class='fas fa-file-alt'></i> Factsheet"
      url: "/factsheet/"
excerpt: >
  CURENT Large-scale Testbed (LTB) is a platform for power system development and testing. <br/>
  <!-- <small><a href="https://github.com/mmistakes/minimal-mistakes/releases/tag/4.26.2">Latest release v4.26.2</a></small> -->
feature_row:
  - title: "Extensible"
    excerpt: "Modeling blocks designed for rapid prototyping of controllers, formulations, and algorithms."
  - title: "Interoperable"
    excerpt: "Seamlessly integrates scheduling and transient simulation tools."
  - title: "Scalable"
    excerpt: "Handles large-scale cases effortlessly, maintaining optimal performance."    
---

{% include feature_row %}


<head>
  <!-- Other HTML head elements -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
  <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" />
  <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"></script>
</head>

<style>
  h1 {
      /* font-family: "Monaco", cursive; */
      font-size: 48px;
  }
  h2 {
      /* font-family: "Monaco", cursive; */
      font-size: 36px;
  }
  partner-logo {
      height: 10px;
  }

  .icon-label {
  font-size: 24px;
  /* font-family: "Monaco", cursive; */
  }
  .icon-container {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    gap: 20px; /* Adjust the value to increase or decrease the space between icons */
  }

  .logo-gallery {
    text-align: left;
  }
  .logo-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin-top: 20px;
  }

    /* First kind logo */
  .partner-logo {
    display: flex;
    align-items: center;
    /* justify-content: center; */
    /* Set a fixed height for uniformity */
    height: 100px;
    /* Allow the width to adjust based on the image aspect ratio */
    width: auto;
    margin: 0px;
  }
  .partner-logo img {
    height: 100%; /* Set the image height to 100% of the container */
    width: auto; /* Allow the width to adjust based on the image aspect ratio */
    object-fit: contain; /* Preserve aspect ratio and fit the whole image within the container */
  }

  /* Second kind logo, given height */
  .partner-logo2 {
    display: flex;
    align-items: center;
    /* justify-content: center; */
    /* Set a fixed height for uniformity */
    height: 80px;
    /* Allow the width to adjust based on the image aspect ratio */
    width: auto;
    margin: 0px;
  }
  .partner-logo2 img {
    height: 100%; /* Set the image height to 100% of the container */
    width: auto; /* Allow the width to adjust based on the image aspect ratio */
    object-fit: contain; /* Preserve aspect ratio and fit the whole image within the container */
  }

  /* Third kind logo, given width */
  .partner-logo3 {
    display: flex;
    align-items: center;
    /* justify-content: center; */
    /* Set a fixed height for uniformity */
    height: auto;
    /* Allow the width to adjust based on the image aspect ratio */
    width: 300px;
    margin: 0px;
  }
  .partner-logo3 img {
    height: auto; /* Set the image height to 100% of the container */
    width: 100%; /* Allow the width to adjust based on the image aspect ratio */
    object-fit: contain; /* Preserve aspect ratio and fit the whole image within the container */
  }
</style>

<div class="row">
  <div class="small-12 columns">
    <h2>Overview</h2>

      <p>
        The CURENT Large-scale Testbed (LTB) is a state-of-the-art research facility designed for rapid prototyping of power systems.
        It is a tightly integrated, closed-loop platform consisting of four major independent packages:
        <b><i>ANDES</i></b> for transient stability modeling and simulation;
        <b><i>AMS</i></b> for scheduling modeling and simulation;
        <b><i>AGVis</i></b> for grid geographical visualization;
        and <b><i>DiME</i></b> for distributed messaging environment.
        These LTB packages can work independently while being interoperable with each other, making it a versatile and comprehensive
        platform for power system research and development.
      </p>

    <h2>Why LTB?</h2>
    {% include feature_row %}

    <h2>Design Philosophy</h2>
    <p>The purpose of LTB is to offer a rapid prototyping environment for power system research and development.
        We kindly ask that you cite the following papers if LTB is used in your research.
        <ol>
            <li>F. Li, K. Tomsovic and H. Cui, "A Large-Scale Testbed as a Virtual Power Grid: For Closed-Loop Controls in Research and Testing,"
                in IEEE Power and Energy Magazine, vol. 18, no. 2, pp. 60-68, March-April 2020, doi: <a href="https://ieeexplore.ieee.org/document/9007798" target="_blank">10.1109/MPE.2019.2959054</a>.
                <span class="__dimensions_badge_embed__" data-doi="10.1109/MPE.2019.2959054" data-style="small_rectangle"></span>    </li>
            <li>H. Cui, F. Li and K. Tomsovic, "Hybrid Symbolic-Numeric Framework for Power System Modeling and Analysis,"
                in IEEE Transactions on Power Systems, vol. 36, no. 2, pp. 1373-1384, March 2021, doi: <a href="https://ieeexplore.ieee.org/document/9169830" target="_blank">10.1109/TPWRS.2020.3017019</a>.
                <span class="__dimensions_badge_embed__" data-doi="10.1109/TPWRS.2020.3017019" data-style="small_rectangle"></span>
            </li>
            <li>J. Wang et al., "Dynamics-Incorporated Modeling Framework for Stability Constrained Scheduling Under High-Penetration of Renewable Energy,"
                in IEEE Transactions on Sustainable Energy, vol. 16, no. 3, pp. 1673-1685, July 2025, doi: <a href="https://ieeexplore.ieee.org/document/10836855" target="_blank">10.1109/TSTE.2025.3528027</a>.
                <span class="__dimensions_badge_embed__" data-doi="10.1109/TSTE.2025.3528027" data-style="small_rectangle"></span>
            </li>
            <li>N. Parsly, J. Wang, N. West, Q. Zhang, H. Cui and F. Li, "DiME and AGVis: A Distributed Messaging Environment and Geographical
                Visualizer for Large-Scale Power System Simulation," 2023 North American Power Symposium (NAPS), Asheville, NC, USA, 2023, pp. 1-5,
                doi: <a href="https://ieeexplore.ieee.org/document/10318583" target="_blank">10.1109/NAPS58826.2023.10318583</a>.
                <span class="__dimensions_badge_embed__" data-doi="10.1109/NAPS58826.2023.10318583" data-style="small_rectangle"></span>
            </li>
        </ol>
    </p>
    <script async src="https://badge.dimensions.ai/badge.js" charset="utf-8"></script>

  </div>
</div>

<div class="row">
  <h2>Partners & Users</h2>
  <div id="map" style="height: 600px; width: 1200px; margin: 0 auto; border: 1px solid #ccc;"></div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/PapaParse/5.3.0/papaparse.min.js"></script>
    <script src="/assets/js/map.js"></script>

  <div class="logo-container">
    <div class="partner-logo2">
      <img src="/assets/images/logos/CURENT.png" alt="CURENT">
    </div>
    <div class="partner-logo2">
      <img src="/assets/images/logos/UTK.png" alt="UTK">
    </div>
  </div>

  <div class="logo-container">
    <div class="partner-logo">
      <img src="/assets/images/logos/NSF2.png" alt="US National Science Foundation">
    </div>
    <div class="partner-logo">
      <img src="/assets/images/logos/DOE.png" alt="US Department of Energy">
    </div>
  </div>

  <div class="logo-container">
    <div class="partner-logo2">
      <img src="assets/images/logos/NCSU.png" alt="North Carolina State University">
    </div>
    <div class="partner-logo2">
      <img src="/assets/images/logos/MSU.png" alt="Mississippi State University">
    </div>
    <div class="partner-logo2">
      <img src="assets/images/logos/Clemson.png" alt="Clemson University">
    </div>
  </div>

  <div class="logo-container">
    <div class="partner-logo2">
      <img src="/assets/images/logos/MST.png" alt="Missouri S&T University">
    </div>
    <div class="partner-logo2">
      <img src="/assets/images/logos/LLNL.png" alt="Lawrence Livermore National Laboratory">
    </div>
    <div class="partner-logo2">
      <img src="/assets/images/logos/ACHL2.png" alt="Achillea Research">
    </div>
    <div class="partner-logo2">
      <img src="/assets/images/logos/UDenver.png" alt="University of Denver">
    </div>
    <div class="partner-logo2">
      <img src="/assets/images/logos/RTX2.png" alt="Raytheon Technologies">
    </div>
    <div class="partner-logo2">
      <img src="/assets/images/logos/NREL.jpeg" alt="National Renewable Energy Laboratory">
    </div>
  </div>

  <div class="logo-container">
    <div class="partner-logo2">
      <img src="/assets/images/logos/OSU.png" alt="Oklahoma State University">
    </div>
    <div class="partner-logo2">
      <img src="/assets/images/logos/PNNL3.png" alt="Pacific Northwest National Laboratory">
    </div>
  </div>

  <p style="margin-top: 20px;">
    If you want to add your map point or logo, please open an issue using the template
    <strong><a href="https://github.com/CURENT/curent.github.io/issues">Add Affiliation to LTB</a></strong>.
  </p>
</div>
