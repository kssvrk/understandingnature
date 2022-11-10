# On Black Body Radiation
## Reference

 - History : https://arxiv.org/pdf/2208.06470.pdf
 - Ideal Gas Law : https://www.tec-science.com/thermodynamics/thermodynamic-processes-in-closed-systems/ideal-gas-law/
 - Kinetic theory of gasses : https://www.tec-science.com/thermodynamics/kinetic-theory-of-gases/pressure-and-temperature/
 - Stefan Boltzmann law : https://www.tec-science.com/thermodynamics/temperature/thermodynamic-derivation-of-the-stefan-boltzmann-law/
 - Derivation of Plancks law : https://edisciplinas.usp.br/pluginfile.php/48089/course/section/16461/qsp_chapter10-plank.pdf

## Rayleigh jeans law

A black body is an idealized opaque, non-reflective body. It absorbs all different wavelengths and emits energy in a wide spectrum of wavelengths. The energies absorbed do not have any relation to the emitted energies, except that the absorbed energies change the temperature of black body. This happens due to the nature that the black body is built. When the body absorbs energy, the particles ( atoms / electrons / what ever ) , are sent into an higher energy state and there by the temperature increases.

The emitted energies of black body essentially depend on the internal temperature of the black body. Temperature can be a yard stick to measure which emissions will be most prominent or the energy distribution. But what is the mechanism through which this distribution of energy occurs across frequencies for any given temperature T.

Experimentally it was known that as the temperature increases , the wavlengths that have the maximum energy in the emission decrease. So on either ends of the wavelengths the intensities keep rising till they reach a peak at somewhere in the middle.

![Blackbody radiation](https://www.periodni.com/gallery/blackbody_radiation.png)

To understand this , we have to come to terms with a theory which could explain why this is happening. This was a very active problem and lies at the juncture of dividing classical and quantum physics. This was attempted by Rayleigh and Jeans through classical physics and Max planck solving the problem using the ideas from Quantum physics.

But before all this some of the main fundamental ideas behind the assumption that a black body radiates energy lies inside kinetic theory of gasses and then assuming Light as photon gas exerting some pressue.

## Black Body description and Initial efforts


### Kirchoff 

There is a reason why we call black bodys as kirchoff's black bodies, it's because it was Gustav Kirchhoff  who derived the relation that the ratio of emissivity to absorptivity for any body for a specific wavelength remains same when talking in terms of black body radiations. [Ref-1 : Kirchoff](#reference)

### Josef Stefan

In 1864, Irish physicist John Tyndall did measurements of the infrared emission by the platinum filament, and the corresponding
colour of filament.In Tyndall’s measurements, Stefan noticed that by increasing the temperature of platinum filament from 798K to 1473K
(1.845 times), radiation was increased by 11.7 times (approximate to ( $1.845^{4}$ ). So he empirically stated that the energy emitted by a black-body per unit area per second is proportional to the
fourth power of the absolute temperature. [Ref-1 : Stefan](#reference)

$$ E \propto T^{4} $$

### Kinetic theory of gasses

[Ref-2 : Kinetic theory derivations](#reference)

Assume that we have a cube filled with gas particles. The gas particles  are uniformly moving in all directions. If we need to calculate the pressure exerted by these gas particles let say on the wall on the +X side ( assuming cube is centered around 3 - axes) , we need to know the force exerted by these particles. Assuming that all the collisions in the gas are elastic at any particular interval we need to count the number of particles hitting one end of this cube. Let us assume that the mass of the gass particles is $m$ grams each. 

The way that we calculate the force will be to calculate the change of classlical momentum of particles for a change in time. Now the particles that will reach the right wall in this time interval are the particles whose velocity will allow them to do so. So if we take a time interval $\triangle t$ , the particles that can reach the wall with velocity $v_{x}$ would be those who are in distance of $v_{x} \triangle t$ with the wall. Also on an average there would be equal number of particles going towards the wall and away from the wall with same average velocity. So we need to divide the total estimate by half to choose the right moving particles

 If we assume that the total number of particles in the cube is N and the length of cube is L , the number of particles with in  $v_{x} \triangle t$ would be  

$$N_{left+right}=\frac{v_{x} \triangle t N}{L}$$

and the right moving particles would be 

$$N_{right}=\frac{v_{x} \triangle t N}{2L}$$

Now $N_{right}$ number of particles will hit the right wall and change their velocity from $v_{x}$ to $- v_{x}$ , so the total net change in momentum on the right wall hitting particles $\triangle p$ is

$$ \triangle p = m 2 v_{x} N_{right} $$
 Substituting for $ N_{right} $ we get
$$\frac {\triangle p}{\triangle t}  = \frac {m v_{x}^{2} N}{L}  $$

The rate of change of momentum is nothing but the force and force per unit area is pressure. So we can indicate pressure on the right wall as

$$ P = \frac {F}{A}=  \frac {\triangle p}{\triangle t A} = \frac {m v_{x}^{2} N}{L^{3}} $$

as Area of the right wall is $L^{2}$ for a cube. Now substituting V ( volume ) in place of $L^{3}$ , we get

$$ P = \frac {m v_{x}^{2} N}{V} $$

Now the $v_{x}$ term here has to be taken with a pinch of salt here because it is a statistical average of all the particles velocity moving in the +X direction. And also , there will be other particles moving in other directions as well and +X is not in any way special. Let us take the average velocity vector $v$ , it can be indicated as 

$$ v = v_{x} \hat{i} + v_{y} \hat{j} + v_{z} \hat{k} $$

Now because this is ideal situation and there are no external forces influencing the gas to be assymetric in any of  the directions, at equilibrium the following can be assumed

$$ v_{x} = v_{y} = v_{z} $$

$$ | \bar {v} |^{2} = 3v_{x}^2$$

$$ P = \frac {1}{3} \frac {m \bar {v}^{2} N}{V} $$

now in energy terms , as the average kinetic energy will be

$$ W_{ke} = \frac {1}{2} m\bar {v}^{2} $$ 

the pressure can be denoted in KE terms as ,

$$ P = \frac {2}{3} \frac { W_{ke}N}{V} $$



###  Ludwig Boltzmann

The underdog and the most important in connecting energy of a gas to the black body radition is Ludwig boltzman. He was a student of Josef stefan. He used the idea of radiation pressure to calculate thermodynamic energy of light system. To understand this in detail let us first understand a little bit about the kinetic theory of gasses.







