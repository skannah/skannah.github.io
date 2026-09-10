---
layout: home
---

<!-- Global subtle fade-in animation -->
<style>
@keyframes fadein {
  from { opacity: 0; transform: translateY(10px); }
  to { opacity: 1; transform: translateY(0); }
}
</style>

# Surender Kannah — Autonomous Systems & Robotics

## Affiliations

<p align="left" style="animation: fadein 0.6s;">
  <img src="lm.png" alt="Lockheed Martin" height="40" style="margin-right:20px;">
  <img src="nsf.png" alt="NSF" height="40" style="margin-right:20px;">
  <img src="ut.png" alt="UT Austin" height="40" style="margin-right:20px;">
  <img src="cu.png" alt="CU Boulder" height="40">
</p>

## About Me

I’m an autonomy and robotics engineer focused on **safety‑critical systems**, **robust GNC**, **dense perception**, and **multi‑sensor fusion**. My work spans **orbital docking**, **SLAM‑based navigation**, **embedded ML**, and **mission‑critical defense autonomy**.

Outside of engineering, I’m passionate about product building, early‑stage startups, and applied AI systems.

This page highlights selected projects and demos that reflect my trajectory toward **orbital‑grade autonomy** and **mission‑critical robotics**.

## Resume
[Download Resume](https://skannah.github.io/Kannah_Surender_Resume.pdf)

---

# Featured Projects

<div style="display:grid; grid-template-columns:repeat(auto-fit, minmax(280px, 1fr)); gap:35px; margin-top:30px; margin-bottom:40px; animation: fadein 0.6s;">

  <!-- Project 1 -->
  <div style="position:relative; text-align:center; padding:10px; transition:0.25s; transform:translateY(0);"
       onmouseover="this.style.transform='translateY(-6px)'; this.style.boxShadow='0 8px 22px rgba(0,0,0,0.15)'"
       onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='none'">

    <a href="https://youtu.be/rvvRkMmm3tA" style="display:block; position:relative;">
      <img src="https://img.youtube.com/vi/rvvRkMmm3tA/0.jpg"
           style="width:100%; border-radius:10px;">

      <!-- Hover Overlay -->
      <div style="
        position:absolute; top:0; left:0; width:100%; height:100%;
        background:rgba(0,0,0,0.55); color:white; opacity:0;
        border-radius:10px; display:flex; align-items:center;
        justify-content:center; font-size:20px; transition:0.25s;"
        onmouseover="this.style.opacity='1'"
        onmouseout="this.style.opacity='0'">
        View Project
      </div>
    </a>

    <h3>Multi‑Sensor Fusion & Tracking</h3>
    <p>EKF fusion + JPDA/MHT multi‑hypothesis tracking.</p>

    <!-- Tags -->
    <p style="font-size:14px; color:#666;">
      <span style="background:#eee; padding:4px 8px; border-radius:6px; margin-right:6px; transition:0.2s;"
            onmouseover="this.style.background='#ddd'" 
            onmouseout="this.style.background='#eee'">Fusion</span>

      <span style="background:#eee; padding:4px 8px; border-radius:6px; margin-right:6px; transition:0.2s;"
            onmouseover="this.style.background='#ddd'" 
            onmouseout="this.style.background='#eee'">Tracking</span>

      <span style="background:#eee; padding:4px 8px; border-radius:6px; transition:0.2s;"
            onmouseover="this.style.background='#ddd'" 
            onmouseout="this.style.background='#eee'">EKF</span>
    </p>
  </div>

  <!-- Project 2 -->
  <div style="position:relative; text-align:center; padding:10px; transition:0.25s; transform:translateY(0);"
       onmouseover="this.style.transform='translateY(-6px)'; this.style.boxShadow='0 8px 22px rgba(0,0,0,0.15)'"
       onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='none'">

    <a href="https://youtu.be/gd0OGeUqW24" style="display:block; position:relative;">
      <img src="https://img.youtube.com/vi/gd0OGeUqW24/0.jpg"
           style="width:100%; border-radius:10px;">

      <div style="
        position:absolute; top:0; left:0; width:100%; height:100%;
        background:rgba(0,0,0,0.55); color:white; opacity:0;
        border-radius:10px; display:flex; align-items:center;
        justify-content:center; font-size:20px; transition:0.25s;"
        onmouseover="this.style.opacity='1'"
        onmouseout="this.style.opacity='0'">
        View Project
      </div>
    </a>

    <h3>TurtleBot3 Navigation — SLAM + Nav2</h3>
    <p>Full SLAM + AMCL + Nav2 stack with custom tuning.</p>

    <p style="font-size:14px; color:#666;">
      <span style="background:#eee; padding:4px 8px; border-radius:6px; margin-right:6px; transition:0.2s;"
            onmouseover="this.style.background='#ddd'" 
            onmouseout="this.style.background='#eee'">SLAM</span>

      <span style="background:#eee; padding:4px 8px; border-radius:6px; margin-right:6px; transition:0.2s;"
            onmouseover="this.style.background='#ddd'" 
            onmouseout="this.style.background='#eee'">Nav2</span>

      <span style="background:#eee; padding:4px 8px; border-radius:6px; transition:0.2s;"
            onmouseover="this.style.background='#ddd'" 
            onmouseout="this.style.background='#eee'">Robotics</span>
    </p>
  </div>

  <!-- Project 3 -->
  <div style="position:relative; text-align:center; padding:10px; transition:0.25s; transform:translateY(0);"
       onmouseover="this.style.transform='translateY(-6px)'; this.style.boxShadow='0 8px 22px rgba(0,0,0,0.15)'"
       onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='none'">

    <a href="https://youtu.be/SDDUo-M2lAQ" style="display:block; position:relative;">
      <img src="https://img.youtube.com/vi/SDDUo-M2lAQ/0.jpg"
           style="width:100%; border-radius:10px;">

      <div style="
        position:absolute; top:0; left:0; width:100%; height:100%;
        background:rgba(0,0,0,0.55); color:white; opacity:0;
        border-radius:10px; display:flex; align-items:center;
        justify-content:center; font-size:20px; transition:0.25s;"
        onmouseover="this.style.opacity='1'"
        onmouseout="this.style.opacity='0'">
        View Project
      </div>
    </a>

    <h3>Robotic Arm</h3>
    <p>Hardware + ML + Software Integration.</p>

    <p style="font-size:14px; color:#666;">
      <span style="background:#eee; padding:4px 8px; border-radius:6px; margin-right:6px; transition:0.2s;"
            onmouseover="this.style.background='#ddd'" 
            onmouseout="this.style.background='#eee'">Hardware</span>

      <span style="background:#eee; padding:4px 8px; border-radius:6px; margin-right:6px; transition:0.2s;"
            onmouseover="this.style.background='#ddd'" 
            onmouseout="this.style.background='#eee'">ML</span>

      <span style="background:#eee; padding:4px 8px; border-radius:6px; transition:0.2s;"
            onmouseover="this.style.background='#ddd'" 
            onmouseout="this.style.background='#eee'">Control</span>
    </p>
  </div>

  <!-- Project 4 -->
  <div style="position:relative; text-align:center; padding:10px; transition:0.25s; transform:translateY(0);"
       onmouseover="this.style.transform='translateY(-6px)'; this.style.boxShadow='0 8px 22px rgba(0,0,0,0.15)'"
       onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='none'">

    <a href="https://youtu.be/WRZVafBsNlI" style="display:block; position:relative;">
      <img src="https://img.youtube.com/vi/WRZVafBsNlI/0.jpg"
           style="width:100%; border-radius:10px;">

      <div style="
        position:absolute; top:0; left:0; width:100%; height:100%;
        background:rgba(0,0,0,0.55); color:white; opacity:0;
        border-radius:10px; display:flex; align-items:center;
        justify-content:center; font-size:20px; transition:0.25s;"
        onmouseover="this.style.opacity='1'"
        onmouseout="this.style.opacity='0'">
        View Project
      </div>
    </a>

    <h3>Julia CV — Multi‑Camera Workflow</h3>
    <p>NSF I‑Corps CV workflow for defect detection across multi‑camera systems.</p>

    <p style="font-size:14px; color:#666;">
      <span style="background:#eee; padding:4px 8px; border-radius:6px; margin-right:6px; transition:0.2s;"
            onmouseover="this.style.background='#ddd'" 
            onmouseout="this.style.background='#eee'">CV</span>

      <span style="background:#eee; padding:4px 8px; border-radius:6px; margin-right:6px; transition:0.2s;"
            onmouseover="this.style.background='#ddd'" 
            onmouseout="this.style.background='#eee'">I‑Corps</span>

      <span style="background:#eee; padding:4px 8px; border-radius:6px; transition:0.2s;"
            onmouseover="this.style.background='#ddd'" 
            onmouseout="this.style.background='#eee'">Multi‑Camera</span>
    </p>
  </div>

</div>

For more detail, see the [Projects](projects.md) page.

---

## Coursework
See selected graduate coursework: [Courses](courses.md)

## Research
Explore my autonomy research interests: [Research](research.md)

---

## Contact

<div style="display:flex; gap:20px; align-items:center; animation: fadein 0.6s;">

  <a href="mailto:surender@gmail.com">
    <img src="email.svg" height="32" style="transition:0.2s;" 
         onmouseover="this.style.opacity='0.7'" 
         onmouseout="this.style.opacity='1'">
  </a>

  <a href="https://github.com/skannah">
    <img src="github.svg" height="32" style="transition:0.2s;" 
         onmouseover="this.style.opacity='0.7'" 
         onmouseout="this.style.opacity='1'">
  </a>

  <a href="https://www.linkedin.com/in/surenderkannah">
    <img src="linkedin.png" height="32" style="transition:0.2s;" 
         onmouseover="this.style.opacity='0.7'" 
         onmouseout="this.style.opacity='1'">
  </a>

</div>

**Email:** surender@gmail.com  
**LinkedIn:** /in/surenderkannah  
**GitHub:** skannah
