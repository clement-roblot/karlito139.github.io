---
layout: project_item
title: AW Edid editor
date_begin: September, 2016
date_end: October, 2016
category: Professional
company: Analog Way
team_number: 1
---
<a href="/static/projects/awEdidEditor/formats.png" class="thickbox"><img class="img-project-item" src="/static/projects/awEdidEditor/formats.png" alt="EDID editor interface" align="right" /></a>
<h2><b>Concept</b></h2>
<hr>
Analog Way builds video mixers/switchers designed to meet any demand, whether it is live events, conferences or integrations. These devices offer a multitude of inputs (analog and digital) and offer multi-format mixer, scaler, soft-edge and matrix, with a variety of transitions and dynamic effects.
<br/><br/>
Every video input of the equipements uses an EDID memory. It is used to specify the capabilities of the said input (maximum vidéo formats supported, audio support, bit-rate, ...).
<br/><br/>
In order to build the EDID, analogway developped a software making it more user friendly than writing every bits of the memory by hand (256 Bytes in total).
<br/><br/>
I work to refactor most of this application and improoved it by adding the support of the new version of the standard that define those types of memories. This application is developped using C++/QT.
<h3><b>Major Points</b></h3>
<hr>
<div class="row">
   <div class="col-md-6 col-sm-6 col-xs-12">
      <div class="tiles m-b-10">
         <div class="tiles-body">
            <div class="tiles-title">User interface</div>
            <hr class="red-underline">
            The user friendlyness was the most important part of this project. That is why a lot of attention was given to the UX of the application.
         </div>
      </div>
   </div>
   <div class="col-md-6 col-sm-6 col-xs-12">
      <div class="tiles m-b-10">
         <div class="tiles-body">
            <div class="tiles-title">Implementation</div>
            <hr class="red-underline">
				The coding of this project was done gradually, with the refactoring of the existing application first. Then the new part of the standard was added.
         </div>
      </div>
   </div>
</div>
<h2><b>Focus on</b></h2>
<hr>
Today this application is used by the R&D team at Analog way but also by many other leading companies accros the world. You can download it <a href="http://www.analogway.com/en/products/software-and-tools/aw-edid-editor/" target="_blank">here</a>.