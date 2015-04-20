
With multijunction cell we defined a solar cell composed of more than one single pn-junction, usually between 2 and 4.

Any pn-junction is stacked on top of the other and works as a normal, single junction cell.

Of course, several problem arise when we stack different junction on each other.

Specifically we are going to address how to let the energy penetrate between the first layers of a multijunction cell down to the last layer, and how to manage the current flow.

### Light Penetration

Light of specific wavelength does not interact with material that are not multiple of that wavelength, this property is exploited to let light penetrate the first layer of a multijunction cell down to the last layers.

Absorb the light in the most efficient way is only a matter of choose what wavelength absorb first, if we absorb first the light of wavelenght 2*n the junction of wavelenght n won't absorb anything.

The junctions that absorb the smaller wavelength are stacked on top of the junctions with bigger wavelength.

### Current Flow

As any other component the pn-junction need to obey to the Kirchhoff laws, this means that the current that flow into a junction must be the same that flow out of the junction.

To address this problem two main design emerged, the monolithic multijunction and the stacked multijunction.

#### Monolithic

In a monolithic multijunction the different layer are stacked directly one on top of the other, and the current flow between the different cell in serie.

If a junction produce the wrong current it will act as load, heating the multijunction cell itself, heading to a loose of efficiency, and consuming power directly.

For this reason the single junctions must be carefully tuned to produce the right ammount of current with the expected inlumination, the junction are tuned modifing slightly the dope ammount.

#### Stacked

In a stacked multijunction cell the different layers are completely isolated from each other.

The problem of different current in different cell is avoided by design, but, as trade-off, such cell required transparent contacts that are still not easy to produce.

The rest of the technical exploration will so focus on the monolithic multijunction cell.

## Technical exploration of a multijunction monolithic solar cell.

A single layer of every monolithic solar cell consist of:

1. Windows
2. Emitter
3. Base
4. Back Surface Field (BSF)

Also a tunnel junction is used to connect the different layers.

## Component:

As in a normal junction the light is converted into electricity in the pn-junction between the emitter (2) and the base (3) and we are not focus again on such point.

### Windows and Back Surface Field

Either component are used to avoid losses by recombination.

The windows is used to reduce the surface recombination velocity.

BSF: Used to reduce the scattering of carriers towards the tunnel junction.

# How to compose the different layer:

## Focus on the Monolithic type.

Necessity of the tunnel junction.


Definition to take care of:

Tunnel Junction: pn-junction of extremely high doped material, the bandgap between the two region is extremely low, almost no power loss.

Surface Recombination Velocity: A measure of the rate of recombination between electrons and holes at the surface of a semiconductor, equal to the component of the electron or hole current density normal to the surface divided by the excess electron or hole volume charge density close to the surface. [2]

Reference:
[1]: http://www.superstrate.net/pv/limit/tandem.html
[2]: http://encyclopedia2.thefreedictionary.com/surface+recombination+velocity

Other:
http://www.sciencedirect.com/science/article/pii/S2215098615000245
http://science.nasa.gov/science-news/science-at-nasa/2002/solarcells/
http://pvcdrom.pveducation.org/DESIGN/SURF_MIN.HTM
http://academic.evergreen.edu/curricular/matterandmotion/chem_phys/solar_cells.pdf
