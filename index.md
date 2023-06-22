---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
image: /assets/images/tr-p2p.jpg
image2: /assets/images/synapse.jpg
image3: /assets/images/libmod.jpg
---
<h1>Selected Audio Projects 2019 - 2022</h1> {: .centre}

<!-- <h2>Selected audio projects I've worked on between 2019 - 2022 </h2> -->

<h2>Wave Terrain Eurorack Module</h2> {: .centre}

<!-- <br> -->

<div class="responsive-youtube">
<iframe width="560" height="315" src="https://www.youtube.com/embed/_I_Bj-A8xkg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

<br>

<!-- <h3>Wave Terrain Eurorack Module</h3> {: .centre} -->

Wave terrain synthesis is a technique that has displayed potential in academic literature, but has failed to cross over into popular use—one reason being the lack of a dedicated hardware interface. 

This project implements a Eurorack-compatible modular approach to the technique. In addition to canonical audio-rate wave terrain synthesis, it also enables the user to draw the trajectory with incoming CVs, and allows for low-frequency control voltage output.

*Completed as part of a Master of Engineering (ME) in Electronics and Computer Systems at Victoria University of Wellington Te Herenga Waka.* 

* [*Full abstract and thesis*](https://openaccess.wgtn.ac.nz/articles/thesis/Wave_Terrain_Hardware_for_Modular_Synthesis/22123283)  
* [*Schematics and code*](https://github.com/samcar17/Wave-Terrain-Synthesizer)

<!-- * [Full abstract and thesis]()
* [Schematics and code](https://github.com/samcar17/Wave-Terrain-Synthesizer) -->

<br>

<h2>TR-P2P: A Networked Sequencer</h2> {: .centre}

![TR-P2P at Te Wā Heke Festival in 2019]({{page.image | relative_url}})

<br>

A browser-based MIDI sequencer that can be edited and played communally, similar to a Google Doc. The server side uses Node.js, with p5.js for the client. 

This project explored the potential for networks to deemphasise the performer by prioritising communal performance—blurring the line between performer and audience member.

It was [demonstrated at Te Wā Heke Festival](https://www.youtube.com/embed/Gswd3yIgAZI) in 2019, where it was used to control a combination of synths and acoustic drums played by robots. 

*Completed as part of a summer scholarship at Victoria University of Wellington Te Herenga Waka.* 

* [*Code and reference documentation*](https://github.com/samcar17/TR-P2P)

<br>

<h2>Synapse</h2> {: .centre}

![The Synapse prototype]({{page.image2 | relative_url}})

<br>

“Synapse” was a MIDI-based effects pedal (the version in the image was built as an initial prototype).

It resulted from an experimental framework for designing instruments, where I interviewed people involved in a free improv community and aimed to capture values common to them. The project aimed for reciprocity — the community's use of the device giving purpose to the design, and the design working to amplify the purposes of the community.

It used various configurations of envelope followers, pitch-trackers and LFOs running into a perceptron object, based on the Nonlinear Circuits "Neuron", with the resulting control signal output as CV and MIDI. This was intended to facilitate connections across devices/instruments prevalent in the community, allowing them to react to each other in a manner that might extend the actions of the improvisors controlling them.

*Completed as part of an Honours project at Te Kōkī New Zealand School of Music.* 

<br>

<h2>Eurorack Modules</h2> {: .centre}

<!-- <br> -->

![The modules in Johnsonville library system]({{page.image3 | relative_url}})

<br>

A collection of Eurorack modules that I built as a way of learning PCB design. They include: 

* +/-12 V Eurorack power supply with +5 V rail
* Three channel mixer and analogue neuron*
* VCA and Fuzz*
* Breadboard to Eurorack converter module (designed for compatibility with the Moog Werkstatt)
* Teensy to Eurorack converter (development board)

<div class="right">
<sup>*Variations on Nonlinear Circuits designs.</sup> 
</div>

Various modules are currently available for use in the Johnsonville Library (Te Whanganui-a-Tara/Wellington, Aotearoa/NZ), forming the beginnings of a publicly-accessible modular synthesizer (seen in the above picture). 


*Teensy to Eurorack converter was designed as part of the preliminary work for a Master of Engineering (ME) in Electronics and Computer Systems at Victoria University of Wellington Te Herenga Waka.* 

*More information is included in the thesis, and the schematic used can be found on [GitHub](https://github.com/samcar17/Wave-Terrain-Synthesizer).*

