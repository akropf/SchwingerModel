# Schrödinger, Klein-Gordon and Dirac equation
## Schrödinger Equation
Before Schrödinger published his famous equation in 1925, it was already established that something peculiar was happening on small scales. 
While Maxwell, who lived in the 19th century, was treating light as an electromagnetic wave, and successfully so, Einstein found an explanation for the [photoelectric effect](https://en.wikipedia.org/wiki/Photoelectric_effect), 
by treating light as a stream of individual elementary particles, called *photons*.<br> 
For the explanation of the photoelectric effect, he could make use of the same relationship between energy and frequency that was 
proposed by Planck a few years ago:<br> <img src="https://render.githubusercontent.com/render/math?math=E%3Dh%5Cnu"><br>
where the energy *E* is linked to the wave frequency <img src="https://render.githubusercontent.com/render/math?math=%5Cnu">. Here, *h* is the [Planck constant](https://en.wikipedia.org/wiki/Planck_constant).<br>
The wave-particle duality of light led to many groundbreaking ideas. 
First, the physicist Louis de Broglie speculated that not only light exhibited a wave-particle duality, 
but matter too. In his dissertation, he proposed another relation between wavelength and momentum: <br><img src="https://render.githubusercontent.com/render/math?math=%5Clambda%3D%5Cfrac%7Bh%7D%7Bp%7D">
<br>
This means, that both the mechanical properties energy *E* and momentum *p* were translatable into wave properties, which was the first major part on the way to the 
Schrödinger equation.<br>
The second part concerned another mystery that was heavily discussed at the beginning of the 20th century, approximately ten years before de Broglie wrote his dissertation: 
The [Spectra](https://en.wikipedia.org/wiki/Emission_spectrum) of Chemical Elements. <br>
If you pass the sun's light through a prism, you see all colors continuously emerging as a rainbow. However, if you fill a tube with hydrogen gas and pass its 
light through the prism, you can see only four distinct lines with all other 'colors' in-between missing. If you would repeat this with different elements, 
you would come to the conclusion that it depends on the element which and how many lines you see, so which colors of light are emitted and absorbed. 
So, basically, spectra are the fingerprints of elements. <br> But why is that the case? At that time, it was already known that the atom had a certain 
structure with a core and electrons moving around it. However, no one was quite sure how this structure produced certain wavelengths of light, 
dependent on the element. In the beginning, electrons were treated as small entities orbiting around the core, as planets do around the sun.
The many tries to match some mechanical motion of the electron to the spectra however failed.<br> It was Niels Bohr who set the ball rolling again when he proposed 
that the motion of the electron had nothing to do with the frequency of radiation. He, moreover, claimed that the electrons can be found in fixed orbits. 
If the electron jumps from one orbit to another, light is emitted or absorbed, and the frequency of the light is then defined by Plancks relation.<br>
While this sufficed in explaining properties of the spectra, Bohr did not know why his model worked. Why were those orbits stable and had fixed energies? 
And why should electrons only emit energy when they jump around between those orbits?<br>
Ten years later, de Broglie used his matter-wave framework to shed some light on the mystery. He could explain isolated, stable orbits by using only wave physics. The stable orbits, he found, correspond to periodic waves.<br>
So when Schrödinger wrote down his equation, he combined the following key aspects into a wave equation:
* Particle-Wave duality, including Matter Waves,
* <img src="https://render.githubusercontent.com/render/math?math=%5Clambda%3D%5Cfrac%7Bh%7D%7Bp%7D">,
* <img src="https://render.githubusercontent.com/render/math?math=E%3Dh%5Cnu">,
* Stable orbits correspond to periodic waves and
* <img src="https://render.githubusercontent.com/render/math?math=E_%7Bkin%7D%3D%5Cfrac%7Bp%5E2%7D%7B2m%7D"> from classical physics.<br>
The wave-function for one-dimension, describing <img src="https://render.githubusercontent.com/render/math?math=%5CPsi(x)"> at a fixed point in time is:<br>
<br>
<p align="center">
  <img src="https://github.com/akropf/Images/blob/main/StationaryWave.png" width="250" height="60">
<p><br>
Now, if you use the new expression for <img src="https://render.githubusercontent.com/render/math?math=%5Clambda%0A">, we can write:<br>
<p align="center">
  <img src="https://github.com/akropf/Images/blob/main/preSchrödingerEq.png" width="250" height="60">
<p><br>
Finally, we now that the total Energy is the sum of kinetic energy <img src="https://render.githubusercontent.com/render/math?math=E_%7Bkin%7D%0A"> and the potential Energy V, which also means that  <img src="https://render.githubusercontent.com/render/math?math=E_%7Bkin%7D%3DE_%7Bt%7D-V">.
Finally, this brings us to the last equation, which is the famous Schrödinger equation:<br>
<p align="center">
  <img src="https://github.com/akropf/Images/blob/main/SchrödingerEqfinal.png" width="310" height="65">
<p><br>
 Now, let's go into more depth. In classical physics, certain mechanical quantities are measured, for example, position *x(t)* or momentum *p(t)*. In Quantum Mechanics, those quantities are translated into so-called operators, which are nothing else than certain multiplication- or differentiation rules 'acting' on the wave-function.   In Quantum Mechanics, those quantities are translated into so-called operators, which are nothing else than certain multiplication- or differentiation rules 'acting' on the wave-function.   Schrödinger expressed the physical quantities position, momentum, and energy as such differential operators for his formulation, which are:
  <p align="center">
  <img src="https://github.com/akropf/Images/blob/main/Translation.png">
<p><br>
If we consider this, we can write the stationary (time-independent) one-dimensional Schrödinger equation as<br>
    <p align="center">
  <img src="https://github.com/akropf/Images/blob/main/OpSchroedinger.png"width="480" height="75">
<p><br>
  
which makes it more clear that the Schrödinger equation is nothing else than a formulation of the conservation of energy. This, however, leaves out one important concept already known at the time: Einstein's notion of general relativity.<br>
The quick history of the Schrödinger equation makes clear that the effort of many is required before a groundbreaking piece of the puzzle is found.  
This summary is based on [Schrödinger and the Genesis of Wave Mechanics](https://www.mpiwg-berlin.mpg.de/sites/default/files/Preprints/P437.pdf), which goes into great depth about the history behind the Schrödinger equation. Quantum Theory basics and Klein-Gordon equation derivations are from the paper [The Weak Force: from Fermi to Feynman](https://arxiv.org/abs/0911.0058), which summarizes the developent in particle physics, especially through nuclear beta decay, in the twentieth century.

