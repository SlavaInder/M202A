---
layout: page
title: About
permalink: /about/
---

<html>
  <body>
    <p>Electromyogram, or EMG, is an electrical signal produced through the contraction of muscle cells. Surface EMGs, or sEMGs, are EMG signals gathered specifically from the skin. Currently, there are a variety of devices that can capture this signal. Unfortunately, there exists flaws associated with each form of sEMG signal collection. Traditional methods of sEMG signal collection employ an excessive amount of electrodes (wires) and require special preparation to operate. This makes it too cumbersome to setup and use on a daily basis while also inhibiting the goals of an interactive environment. On the other hand, portable devices like the Myo Armband, while less accurate, are much more convenient to use. Regardless, they lack popularity with the general public and have yet to find a place in human-computer interaction. One of the reasons is that the number of gestures that can be reliably recognized by this hardware remains limited. Our work aims to build upon that and propose a real-time classification algorithm on a novel gesture set.</p>
      <h3>Specific Aims</h3>
      <p><ul>
        <li>Propose a specific set of gestures to recognize based on trade-offs between accuracy and ease</li>
        <li>Develop a feature extraction algorithm and implement neural network for gesture recognition</li>
        <li>Demonstrate translation of our gesture recognition algorithm via Android application</li>
      </ul></p>
      <h3>Today's Status and Novelty</h3>
      <p>Currently, there are no products that can adequately translate mimimal human motion into specific actions without environment-specific equipment or inefficient amounts of interactive hardware. Previous works utilizing the Myo Armband employ a common gesture set. This gesture sets utilizes the whole hand to produce dissimilar sEMG signals with a large amplitude including: open hand, wrist flexion, clenched hand, and wrist extensions. One of the most valuable resources we came across was the NinaPro DB5, the benchmark database for sEMG signal collection. The gestures captured within this dataset included finger extensions, finger adductions, and finger flexions, but all of these movements can be characterized by a large sweep of the finger which lead to higher sEMG signal amplitudes. Therefore, despite containing 53 separate gestures, this database still did not capture the gesture set we are aiming to differentiate. The expectation of this project is to demonstrate the capability of utilizing one Myo Armband to distinctively evaluate subtle single-finger gestures at a real-time speed. This will lay the basis of an new framework for human interaction with personal devices and IoT. </p>
      <!--<center><figure>
          <img class = "size" src="https://cnet1.cbsistatic.com/img/00XQEmFzx7Xio51Kw8V0E4zo_oE=/2017/11/21/b97d2dc7-e471-47b8-a2e0-9091b2d26bcd/fl-tapkeyboard-cnetstill.jpg" style="max-width:50%;">
          <center><figcaption>The Tap Strap translates the change in accelerometer readings to user input</figcaption></center>
        </figure></center>-->
  </body>
</html>
