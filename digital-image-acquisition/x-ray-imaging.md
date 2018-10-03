## Characteristics
- Electromagnetic waves with wavelengths below the visible spectrum (frequency above)
- Has wave characteristics but travels as clusters of energy or photons with a given wavelength
- Do not need a carrier
- Travel at the speed of light

The wavelength λ and frequency f are related by: 

<a href="https://www.codecogs.com/eqnedit.php?latex=c=\lambda&space;f" target="_blank"><img src="https://latex.codecogs.com/gif.latex?c=\lambda&space;f" title="c=\lambda f" /></a>

where the constant c is the speed of light. The energy of a photon measured in eV is the energy that a single electron acquires when moving through a potential of 1 V. The energy of a photon is characterized by its wavelength and is given by:

<a href="https://www.codecogs.com/eqnedit.php?latex=E&space;=&space;hf&space;=&space;\frac{hc}{\lambda}&space;=&space;\frac{1.24&space;\;&space;keV\;&space;nm}{\lambda}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?E&space;=&space;hf&space;=&space;\frac{hc}{\lambda}&space;=&space;\frac{1.24&space;\;&space;keV\;&space;nm}{\lambda}" title="E = hf = \frac{hc}{\lambda} = \frac{1.24 \; keV\; nm}{\lambda}" /></a>

The wavelength of an electromagnetic wave is inversly proportional to its energy. If ordered by increasing energy (or decreasing wavelength), electromagnetic waves can be:

- radio waves (used for MRI)
- microwaves
- infra-red
- visible light
- ultraviolet light
- X-rays or gamma (created in nucleus decays) rays

The energy of the X-ray photons is enough to release electrons from an atom - by a process called photoelectric effect. 

**Exposure**-amount of charge per volume of air, measured in Roentgen (R) characterizes the X-rays. 
- measures the energy of the radiation source
- does not describe how much radiation is absorbed by the body under the radiation

**Dose**-absorption per unit mass, measured in radiation absorbed dose (rad) or gray (Gy) with 1 Gy=100 rad

**f-factor**-ratio between the dose and the exposure, varies with the X-ray energy
- much higher for hard tissues at low exposure (bones) compared to soft tissue and water
- thus, bone at low doses absorbs a significantly higher amount of radiation than soft tissue

## X-ray Generation
- electrons in an atom organized in shells around the nucleus
- the innermost shell contains electrons with the lowest (negative) energy, meaning that they are the most tightly bound
- energy is needed to move an electron from an inner shell to an outer shell - this is the difference between energy levels of the two shells 
- for the electron to be released from a shell, an energy amounting to the difference between its current energy level and the energy level of a free electron (which is usually set to 0 eV by convention). 

X-rays are the result of the excess energy from electrons in the material of a cathode ray tube (CRT) when the cathode is heated up. (The material is usually tungsten). 
Energy from heating causes the electrons to be released from the cathode and accelerated towards the anode. 
In the anode, electrons lose their kinetic energy by:
- excitation - causes electrons of the anode material to move from an outer shell to an inner shell, happens directly
- ionization - causes electrons of the anode material to move from an outer shell to an inner shell by exciting the electrons of another atom
- radiation - excess energy released as X-rays (depends on the energy difference between the outer and inner shell), monochrome/characteristic radiation

However, most generated X-ray radiation is polychrome. 
- an incident electron slows down (by a coulomb intreaction) when passing the nucleus of an atom and its path is deflected
- this lowers the frequency and, thereby the energy of the electron. The energy difference between the incident electron and deflected electron is emitted as a photon
- this process is called bremsstrahlung and emmited photons are called bremsstrahlung X-ray photons
- the amount of emitted photons depends on how close the electron passes the nucleus
- approximately 80% of the population of X-rays within the X-ray beam consists of X-rays generated in this way

## X-ray Spectrum

- As a result of characteristic and bremsstrahlung radiation generation a spectrum of X-ray energy is produced within the X-ray beam
- The spectrum of the bremsstrahlung of a cathode ray tube should be roughly of a triangular shape
- Because the sorrounding glass of the tube filters some of the low energy radiation, the actual curve is zero at low energy, increases to a maximum at some intermediate energy level and decreases to zero at the maximum energy
- The complete spectrum is a combination of monochrome and polychrome radiation
- Spikes indicate some characteristic radiation energy levels

![spectrum](https://github.com/elberethfanulios/medical-image-analysis/blob/master/digital-image-acquisition/spectrum.png) <!-- .element height="25%" width="25%" -->

X-ray tubes are characterized by the total amount of emitted energy as X-rays and the quality of radiation. A high quality tube has a higher amount of high energy radiation and of monochrome radiation. 
High quality radiation imposes a lower dose on the patient and produces better images. 

