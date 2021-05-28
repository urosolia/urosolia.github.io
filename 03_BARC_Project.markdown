---
layout: page
title: BARC Project
permalink: /BARC_Project/
---
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-180984784-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-180984784-1');
</script>

## The Berkeley Autonomous Race Car (BARC) Project
During my PhD I had the opportunity to test control algorithms on the Berkeley Autonomous Racing Car ([BARC](http://www.barc-project.com/)) platform developed at the MPC lab by my colleague [Jon Gonzales](http://www.jonmgonzales.com/).
{: style="text-align: justify"}

The BARC is an open source low cost platform developed for teaching vehicle dynamics and control algorithms. It is a platform for learning how to implement control algorithms in the real world and to understand the main challenges that we need to face when dealing with experimental systems.
{: style="text-align: justify"}

In the past years, Jon and I lead several projects spanning control, estimation and low level actuation. We were lucky to work with wonderful people which were very excited to work on the BARC. Each student did a great master thesis and brought an important contribution to the BARC project.
{: style="text-align: justify"}

Follows a list, in chronological order, of the students that worked on the Learning Model Predictive Control (LMPC) framework for autonomous racing on the BARC.
{: style="text-align: justify"}

___

# Visiting Master Students

<table style="border: 1px solid transparent;">
<tbody>
<tr>
<td style="text-align:justify;width: 500px; border: 1px solid transparent">
	<img align="left" src="/images/students/max.png" style="border: 10px solid transparent;" width="100"> 
	Max (<a href="https://www.linkedin.com/in/maximilian-brunner-847a89a6/">Maximilian Brunner</a>) worked both on hardware and theory. Firstly, he implemented the first version of the state estimator and the low level controller. Afterwards, he extended the LMPC theory to handle repetitive tasks. Please refer to 
	<a href="https://ieeexplore.ieee.org/abstract/document/8264027/">this paper</a> for further details.
</td>
<td style="width: 50px; border: 1px solid transparent" valign="top"> <iframe width="250" src="https://www.youtube.com/embed/4kHDv9senpE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> </td>
</tr>
</tbody>
</table>


<table style="border: 1px solid transparent;">
<tbody>
<tr>
<td style="text-align:justify; width: 550px; border: 1px solid transparent">
	<img align="left" src="/images/students/martin.png" style="border: 10px solid transparent;" width="100"> 
	Martin (<a href="https://www.linkedin.com/in/martin-d-hoffschmidt-91b5a130/">Martin D'Hoffschmidt</a>) explored the possibility of incorporating Deep Neural Network (DNN) in the LMPC framework. First, he developed (in C) a library for training and then evaluating DNN. Afterward, he implemented the LMPC where the vehicle model was a DNN. Finally, he designed a "curiosity cost" which would encourage the LMPC to explore new regions of the state space. All his work has been tested in simulation with the high fidelity software CarSim.
</td>
</tr>
</tbody>
</table>


<table style="border: 1px solid transparent;">
<tbody>
<tr>
<td style="text-align:justify; width: 500px; border: 1px solid transparent">
	<img align="left" src="/images/students/michael.png" style="border: 10px solid transparent;" width="100"> 
	Michael (<a href="https://www.linkedin.com/in/michaelgarstka/">Michael Garstka</a>) worked on Adaptive LMPC. The key idea is to build a controller which at the same time computes the control action and adapts the vehicle model used in the forecasting process. Michael successfully demonstrated on the experimental set-up that his adaptive strategy is able to improve the performance of the controller.
</td>
<td style="text-align:justify; width: 50px; border: 1px solid transparent" valign="top"> <iframe width="250" src="https://www.youtube.com/embed/Z1q9PjCnIdY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> </td>
</tr>
</tbody>
</table>


<table style="border: 1px solid transparent;">
<tbody>
<tr>
<td style="text-align:justify; width: 550px; border: 1px solid transparent">
	<img align="left" src="/images/students/felix.png" style="border: 10px solid transparent;" width="100"> 
	Felix (<a href="https://www.linkedin.com/in/felix-nobis-2ab79a113/">Felix Nobis</a>) worked on obstacle avoidance. He designed and implemented a new strategy for learning when obstacles can appear or disappear on the track. Indeed, when an obstacle is placed on the race track the set of safe point shrinks. The problem is challenging as,  when the obstacle can appear everywhere on the track, the recorded data do not represent safe regions. Felix successfully tested his algorithm on the BARC simulator.
</td>
</tr>
</tbody>
</table>

<table style="border: 1px solid transparent;">
<tbody>
<tr>
<td style="text-align:justify; width: 500px; border: 1px solid transparent">
	<img align="left" src="/images/students/francesco.png" style="border: 10px solid transparent;" width="100"> 
	Francesco (<a href="https://www.linkedin.com/in/francesco-ricciuti-1a9839149/">Francesco Ricciuti</a>) continued the work on obstacle avoidance. He focused on speeding up the LMPC solver time and adapting the safe set definition when moving obstacles present on the track. Finally, he tested the controller on the BARC platform.
</td>
<td style="text-align:justify; width: 50px; border: 1px solid transparent" valign="top"> <iframe width="250" src="https://www.youtube.com/embed/_ESVg0gt9bk" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> </td>
</tr>
</tbody>
</table>


<table style="border: 1px solid transparent;">
<tbody>
<tr>
<td style="text-align:justify; width: 500px; border: 1px solid transparent">
	<img align="left" src="/images/students/shuqi.jpg" style="border: 10px solid transparent;" width="100"> 
	Shuqi (<a href="https://www.linkedin.com/in/shuqi-xu-58879296/">Shuqi Xu</a>) worked on  identifying and testing modeling strategies for autonomous racing. He developed several strategies based on physics law and\or machined learning. Furthermore, he developed a multi-frequency controller which is able to run in real-time (shown in the video). Finally, he co-developed the latest version of the state estimator used in the BARC platform.
</td>
<td style="text-align:justify; width: 50px; border: 1px solid transparent" valign="top"> <iframe width="250" src="https://www.youtube.com/embed/O61Pb5fMPkw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> </td>
</tr>
</tbody>
</table>

<table style="border: 1px solid transparent;">
<tbody>
<tr>
<td style="text-align:justify; width: 400px; border: 1px solid transparent">
	<img align="left" src="/images/students/lukas.jpg" style="border: 10px solid transparent;" width="100"> 
	Lukas (<a href="https://www.linkedin.com/in/lukas-brunke-98898095/">Lukas Brunke</a>) worked on competitive multi-agent autonomous car racing using LMPC. He developed strategies for state exploration, safe set selection and improved the obstacle avoidance behavior. He demonstrated on the BARC simulator shown that the autonomous vehicle were able to perform multiple overtaking maneuvers.
</td>
<td style="text-align:justify; width: 50; border: 1px solid transparent" valign="top"> <img align="left" src="/images/students/lukas_multi_vehicle.gif" style="border: 10px solid transparent;" width="600px">  </td>
</tr>
</tbody>
</table>
