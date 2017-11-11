---
layout: project_item
title: AW Livecore
date_begin: Oct, 2014
date_end: Sept, 2017
category: Professional
company: Analog Way
team_number: 10
---
<a href="/static/projects/awLivecore/livrecodeFlycase.jpg" class="thickbox"><img class="img-project-item" src="/static/projects/awLivecore/livrecodeFlycase.jpg" alt="Livecore in a rack" align="right" /></a>
<h2><b>Concept</b></h2>
<hr>
Analog Way builds video mixers/switchers designed to meet any demand, whether it is live events, conferences or integrations. These devices offer a multitude of inputs (analog and digital) and offer multi-format mixer, scaler, soft-edge and matrix, with a variety of transitions and dynamic effects.
<br/><br/>
The livecore plateform is the featured product of analog way, it can manage up to 4 full HD outputs and 12 inputs. It also includes a link feature that enables it to be connected to an other livecore to double its performances (24 inputs, 8 outputs).
<br/><br/>
As part of my position at analogway I was developing the software embedded in the microcontrolers of the devices. The 14 ARM microcontrolers needs to communicate with one another at all time to time video effects to the frame, and configure the multiple components that each board embed to generate the composed feed requested by the user.

<h3><b>Major Points</b></h3>
<hr>
<div class="row">
   <div class="col-md-6 col-sm-6 col-xs-12">
      <div class="tiles m-b-10">
         <div class="tiles-body">
            <div class="tiles-title">Analysis</div>
            <hr class="red-underline">
            Taking back a project that have already been developed to an advanced state, it was necessary for me to analyze the existing code well in order to integrate in the most organic way possible the new features that I was developing.
         </div>
      </div>
   </div>
   <div class="col-md-6 col-sm-6 col-xs-12">
      <div class="tiles m-b-10">
         <div class="tiles-body">
            <div class="tiles-title">Coding</div>
            <hr class="red-underline">
                The coding of this project was challenging in the constraints around it. The microcontrolers where already either full or lacking enough processing power. The new features needed to be very lean to be able to fit on-board.
         </div>
      </div>
   </div>
</div>
<h2><b>Focus on</b></h2>
<hr>
To make the application as light and fast as possible, many techniques where used including :
<ul>
   <li>Structure optimization</li>
   <li>Structure packing</li>
   <li>Bit-field usage</li>
   <li>Non blocking state machines</li>
</ul>

<center><a href="/static/projects/awLivecore/webrcs.jpg" class="thickbox"><img src="/static/projects/awLivecore/webrcs.jpg" width="70%" alt="WebRCS" /></a></center>