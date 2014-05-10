---
layout: default
title: Watch
weight: 6
---


<!--

Place the ID:s of the videos here below (in between the "capture"-tags

-->
{% capture videos %}

yUWtk81q7Eo
tKE98TUAV4w
H7HuHMH-1bs
YJc_vKJEZ58
0DLAZf9y43Q
Jz8jvwo5zYU
a33_8fWiX6Y
I25frMHXLD4
Mjz6F8cfAbk
G44e0dufFx4
d6_1EjMCvPM
vT4tliB847c
ETxc3oqjvhA
rmiA3ocFaT0
CBUVSdRh3Ls
ksQBR1dxkl0

{% endcapture %}

<!--

Do not change anything after this. 

-->


{% assign videoArray = \"{{ videos }}\" | split: " " %}

{% for vid in videoArray %}
<div class="videoWrapper">
<iframe class="youtube-player" type="text/html" width="640" height="385" src="http://www.youtube.com/embed/{{vid}}" allowfullscreen frameborder="0">
</iframe>
</div>
{% endfor %}




<!--
{% for pah in myArray %}
<div class="videoWrapper">
</div>
<iframe class="youtube-player" type="text/html" width="640" height="385" src="http://www.youtube.com/embed/{{pah}}" allowfullscreen frameborder="0">
</iframe>
{% endfor %}




 <iframe width="425" height="350" src="//www.youtube.com/embed/{{pah}}?wmode=transparent" frameborder="0">
</iframe>





<iframe width="425" height="350" src="//www.youtube.com/embed/Jz8jvwo5zYU" frameborder="0" allowfullscreen></iframe>

<iframe width="425" height="350" src="http://www.youtube.com/embed/H7HuHMH-1bs?wmode=transparent" frameborder="0">
</iframe>


<iframe width="425" height="350" src="http://www.youtube.com/embed/YJc_vKJEZ58?wmode=transparent" frameborder="0">
</iframe>

<iframe width="425" height="350" src="http://www.youtube.com/embed/0DLAZf9y43Q?wmode=transparent" frameborder="0">
</iframe>

<iframe width="425" height="350" src="http://www.youtube.com/embed/a33_8fWiX6Y?wmode=transparent" frameborder="0">
</iframe>

<iframe width="425" height="350" src="http://www.youtube.com/embed/I25frMHXLD4?wmode=transparent" frameborder="0">
</iframe>

<iframe width="425" height="350" src="http://www.youtube.com/embed/Mjz6F8cfAbk?wmode=transparent" frameborder="0">
</iframe>

<iframe width="425" height="350" src="http://www.youtube.com/embed/G44e0dufFx4?wmode=transparent" frameborder="0">
</iframe>

<iframe width="425" height="350" src="http://www.youtube.com/embed/d6_1EjMCvPM?wmode=transparent" frameborder="0">
</iframe>

<iframe width="425" height="350" src="http://www.youtube.com/embed/vT4tliB847c?wmode=transparent" frameborder="0">
</iframe>

<iframe width="425" height="350" src="http://www.youtube.com/embed/ETxc3oqjvhA?wmode=transparent" frameborder="0">
</iframe>

<iframe width="425" height="350" src="http://www.youtube.com/embed/rmiA3ocFaT0?wmode=transparent" frameborder="0">
</iframe>

<iframe width="425" height="350" src="http://www.youtube.com/embed/CBUVSdRh3Ls?wmode=transparent" frameborder="0">
</iframe>

<iframe width="425" height="350" src="http://www.youtube.com/embed/ksQBR1dxkl0?wmode=transparent" frameborder="0">
</iframe>

-->
