---
layout: home
---

<style>
  body {
    font-family: 'Avenir', serif;
    color: #333333;
  }

  a {
    color: #1a0dab;
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }

  img.profile {
    max-width: 200px;
    border-radius: 50%;
    display: block;
    margin: 0 auto; /* Centers the image */
  }

  .research-item {
    display: flex;
    align-items: center;
    margin-bottom: 20px;
  }

  .research-thumb {
    width: 150px;
    margin-right: 20px;
    border-radius: 10px; /* Rounded rectangle */
    overflow: hidden; /* Ensures the border-radius affects the image */
  }

  .research-thumb img {
    width: 100%;
    display: block; /* Removes bottom gap */
  }

  .research-text {
    flex: 1;
    font-size: 16px;
  }

  .research-text h2, 
  .research-text p, 
  .research-text a {
    font-size: inherit;
    margin: 0;
    padding: 0;
  }

  .research-text h2 {
    margin-bottom: 0.5em;
  }

  .underline {
    text-decoration: underline;
  }

  .conference {
    font-style: italic;
  }

  /* Added styles for smaller font size */
  .contact-info {
    font-size: 14px; /* Adjust this value to make it smaller or larger */
    text-align: center; /* Centers the text */
  }

  .reward-note {
    font-style: italic;
    font-weight: bold;
  }

</style>

<div style="display: flex; align-items: center; margin-bottom: 20px;">
  <div style="flex: 1; margin-right: 20px;">
    Hi! I'm a PhD student in the CS Department at UC Santa Barbara, co-advised by 
    <a href="https://web.ece.ucsb.edu/~psen/">Prof. Pradeep Sen</a> and 
    <a href="https://sites.cs.ucsb.edu/~sra/index.html">Prof. Misha Sra</a>. I earned a double B.S.'s 
    in CS as well as Applied and Computational Mathematical Sciences (ACMS) from the 
    University of Washington.

    <br><br>
    I am broadly interested in Machine Learning, Computer Vision, and Human-Computer 
    Interaction, with a primary focus on multi-modal image analysis and generation (GenAI).
  </div>
  <div>
    <img src="images/sherry.jpeg" alt="Profile photo of Sherry X. Chen" class="profile">
    <div class="contact-info">
      Email: xchen774 [at] ucsb [dot] edu
      <br>
      <a href="https://www.linkedin.com/in/sherry-x-chen">LinkedIn</a> | 
      <a href="https://scholar.google.com/citations?user=Lb5eUYMAAAAJ">Google Scholar</a> | 
      <a href="https://github.com/SherryXTChen">GitHub</a>
    </div>
  </div>
</div>

<br>
## Research

<div class="research-item">
  <div class="research-thumb">
    <img src="images/instructclip.png" alt="Thumbnail for Instruct-CLIP">
  </div>
  <div class="research-text">
    <p><strong>InstructCLIP: Improving Instruction-Guided Image Editing with Automated Data Refinement Using Contrastive Learning</strong></p>
    <p><span class="underline">Sherry X. Chen</span>, Misha Sra, Pradeep Sen</p>
    <p class="conference">CVPR 2025</p>
    <p><a href="https://arxiv.org/abs/2503.18406">PDF</a> | <a href="https://github.com/SherryXTChen/Instruct-CLIP">Code</a></p>
  </div>
</div>

<div class="research-item">
  <div class="research-thumb">
    <img src="images/sico.png" alt="Thumbnail for SiCo">
  </div>
  <div class="research-text">
    <p><strong>SiCo: An Interactive Size-Controllable Virtual Try-On Approach for Informed Decision-Making</strong></p>
    <p><span class="underline">Sherry X. Chen</span>, Alex Christopher Lim, Yimeng Liu, Pradeep Sen, Misha Sra</p>
    <p class="conference">DIS 2025 <span class="reward-note">(Honorable Mention)</span></p>
    <p><a href="http://arxiv.org/abs/2408.02803">PDF</a> | <a href="https://github.com/SherryXTChen/SiCo">Code</a></p>
  </div>
</div>

<div class="research-item">
  <div class="research-thumb">
    <img src="images/aidappeal.png" alt="Thumbnail for AID-AppEAL">
  </div>
  <div class="research-text">
    <p><strong>AID-AppEAL: Automatic Image Dataset and Algorithm for Content Appeal Enhancement and Assessment Labeling</strong></p>
    <p><span class="underline">Sherry X. Chen</span>, Yaron Vaxman, Elad Ben Baruch, David Asulin, Aviad Moreshet, Misha Sra, Pradeep Sen</p>
    <p class="conference">ECCV 2024</p>
    <p><a href="https://arxiv.org/abs/2407.05546v2">PDF</a> | <a href="https://github.com/SherryXTChen/AID-Appeal">Code</a></p>
  </div>
</div>

<div class="research-item">
  <div class="research-thumb">
    <img src="images/tinoedit.png" alt="Thumbnail for TiNO-Edit">
  </div>
  <div class="research-text">
    <p><strong>TiNO-Edit: Timestep and Noise Optimization for Robust Diffusion-Based Image Editing</strong></p>
    <p><span class="underline">Sherry X. Chen</span>, Yaron Vaxman, Elad Ben Baruch, David Asulin, Aviad Moreshet, Kuo-Chin Lien, Misha Sra, Pradeep Sen</p>
    <p class="conference">CVPR 2024</p>
    <p><a href="https://arxiv.org/abs/2404.11120">PDF</a> | <a href="https://github.com/SherryXTChen/TiNO-Edit">Code</a></p>
  </div>
</div>

<div class="research-item">
  <div class="research-thumb">
    <img src="images/echat.png" alt="Thumbnail for EChat">
  </div>
  <div class="research-text">
    <p><strong>EChat: An Emotion-Aware Adaptive UI for a Messaging App</strong></p>
    <p>Radha Kumaran, Viral Niraj Doshi, <span class="underline">Sherry X. Chen</span>, Avinash Aji Nargund, Tobias Höllerer, Misha Sra</p>
    <p class="conference">UIST 2023</p>
    <p><a href="https://dl.acm.org/doi/10.1145/3586182.3616698">PDF</a></p>
  </div>
</div>

<div class="research-item">
  <div class="research-thumb">
    <img src="images/pairdetr.png" alt="Thumbnail for Pair DETR">
  </div>
  <div class="research-text">
    <p><strong>Pair DETR: Toward Faster Convergent DETR</strong></p>
    <p>Seyed Mehdi Iranmanesh, <span class="underline">Sherry X. Chen</span>, Kuo-Chin Lien</p>
    <p class="conference">ICASSP 2023</p>
    <p><a href="https://ieeexplore.ieee.org/document/10095608">PDF</a></p>
  </div>
</div>

<div class="research-item">
  <div class="research-thumb">
    <img src="images/patchtrack.png" alt="Thumbnail for PatchTrack">
  </div>
  <div class="research-text">
    <p><strong>PatchTrack: Multiple Object Tracking Using Frame Patches</strong></p>
    <p><span class="underline">Xiaotong Chen</span>, Seyed Mehdi Iranmanesh, Kuo-Chin Lien</p>
    <p class="conference">arXiv 2022</p>
    <p><a href="https://arxiv.org/abs/2201.00080">PDF</a></p>
  </div>
</div>

<div class="research-item">
  <div class="research-thumb">
    <img src="images/intothevideos.png" alt="Thumbnail for IntoTheVideos">
  </div>
  <div class="research-text">
    <p><strong>IntoTheVideos: Exploration of Dynamic 3D Space Reconstruction From Single Sports Videos</strong></p>
    <p><span class="underline">Xiaotong Chen</span>, Misha Sra</p>
    <p class="conference">UIST 2021</p>
    <p><a href="https://dl.acm.org/doi/10.1145/3474349.3480215">PDF</a></p>
  </div>
</div>
