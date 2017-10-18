---
layout: project_item
title: AW Livecore
date_begin: Oct, 2014
date_end: Sept, 2017
category: Professional
company: Analog Way
team_number: 10
---
<a href="/static/projects/AW/visuel2-17227.png" class="thickbox"><img class="img-project-item" src="/static/projects/AW/visuel2-17227.png" alt="Yocto architecture" align="right" /></a>
<h2><b>Concept</b></h2>
<hr>
Analog Way provide video mixers/switchers designed to meet any demand, whether it's live events, conferences or integrations. These devices offer a multitude of inputs (analog and digital) and offer multi-format mixer, scaler, soft-edge, matrix, with a variety of transitions and dynamic effects. For self-training or shows preparation upstream of the performance, the rental of these devices is expensive.
<br/><br/>
The creation of a devices simulator avoids the extra cost of renting a device. Because the program had to simulate machines with different capacities and functionalities, it was necessary to generalize a maximum of treatments. The goal of this is to avoid the creation of specific code according to the machines that one wishes to simulate.
<br/><br/>
To do this, the software has been coded in C++, the adaptative features motor of the devices is in Lua, the web interface driving the simulator (choice of the machine to simulate) is in HTML/CSS/PHP/JAVASCRIPT and everything is embedded in a virtual machine where the operating system was created using Yocto.
<h3><b>Major Points</b></h3>
<hr>
<div class="row">
   <div class="col-md-4 col-sm-4 col-xs-12">
      <div class="tiles m-b-10">
         <div class="tiles-body">
            <div class="tiles-title">Analysis</div>
            <hr class="red-underline">
            Writing expressions of needs and software specifications.
         </div>
      </div>
   </div>
   <div class="col-md-4 col-sm-4 col-xs-12">
      <div class="tiles m-b-10">
         <div class="tiles-body">
            <div class="tiles-title">Coding</div>
            <hr class="red-underline">
				The coding of this project was done gradually, with the heart of the engine first. In parralère, the site of controls and the behavior scripts were coded. The operating system was the purpose of this project.
         </div>
      </div>
   </div>
   <div class="col-md-4 col-sm-4 col-xs-12">
      <div class="tiles m-b-10">
         <div class="tiles-body">
            <div class="tiles-title">Result</div>
            <hr class="red-underline">
            Official release 13 months after the start of the project from scratch
         </div>
      </div>
   </div>
</div>
<h2><b>Focus on</b></h2>
<hr>
To make the application as light as possible, we chose to create an operating system (using Yocto) adapted to the needs of the project. This creation follows the reflexion not to force the user to install a web server (interface controls of the machine) on his workstation, to avoid being intrusive.
<blockquote cite="https://www.yoctoproject.org">The Yocto Project is an open source collaboration project that provides templates, tools and methods to help you create custom Linux-based systems for embedded products regardless of the hardware architecture. It was founded in 2010 as a collaboration among many hardware manufacturers, open-source operating systems vendors, and electronics companies to bring some order to the chaos of embedded Linux development.</blockquote>
<blockquote cite="hhttps://www.yoctoproject.org/docs/2.1/yocto-project-qs/yocto-project-qs.html">The Yocto Project through the OpenEmbedded build system provides an open source development environment targeting the ARM, MIPS, PowerPC, and x86 architectures for a variety of platforms including x86-64 and emulated ones. You can use components from the Yocto Project to design, develop, build, debug, simulate, and test the complete software stack using Linux, the X Window System, GTK+ frameworks, and Qt frameworks.</blockquote>
<center><a href="/static/projects/AW/yocto-environment.png" class="thickbox"><img src="/static/projects/AW/yocto-environment.png" width="80%" height="80%" alt="Yocto architecture" /></a></center>