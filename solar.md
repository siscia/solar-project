
Nowadays the most efficienc type of solar cell are the multijucntion cell.

Such photovoltaic cell are composed of more than one single pn-junction, usually between two and four different junction are used.

Spatially the single pn-jucntion that compose a multijunction cell are stacked one on top of each other in order to capture as much as possible of the light frequencies.

However several problems arise when we stack different junction on each other.

The two biggest constrain to the design of a multijunction cell are how to let the light penetrate down to the very last junction and how to handle the current generate by the different junctions.

### Light Penetration

In order to obtain the higest efficiency out of a multijucntion cell it is necessary that every single junction will be irradiate by enough light in order to provide energy.

However, if we stack different cell on top of each other, our intution will suggest that only the first cell will be inradiate, while the next cell will be on the shadow of the top one.

Fortunately, in contrats with our intuition, light of specific wavelength does not interact with material that are not multiple of that wavelength, this property is exploited to let light penetrate the first layer of a multijunction cell down to the last layers.

Exploiting this property of light to absorb the light in the most efficient way means to choose what wavelength absorb first, if we absorb first the light of wavelength 2*n the junction of wavelength n won't be able to absorb anything.

The junctions that absorb the smaller wavelength are so stacked on top of the junctions with bigger wavelength.

### Current Flow

Different pn-junction will provide different current, however, as any eletrical component, even the pn-junction need to obey the Kirchhoff law of current.

To obey to the Kirchhoff current law means that the current which flow into a pn-junction must be equal to the current that flow out from that same jucntion.

In order to manage the different current that are produced by the different junction two main design emerge, the monolithic multijucntion and the stacked multijunction.

#### Monolithic

In a monolithic multijunction the different layers are stacked directly one on top of the other, and the current flow between the different cell in series.

If a junction produce the wrong current, in order to obey to the Kirchhoff law, it will act as load, heating the multijunction cell itself, heading to a loose of efficiency, and consuming power directly.

For this reason the single junctions must be carefully tuned to produce the right amount of current, the junctions are tuned modifying slightly the dope amount.

#### Stacked

Opposed to the monolithisc cell the stacked cell are composed of several different layers, but each layer is completely isolated from the others.

This design avoid completely the issues about the possible difference of current production in each cell, however, as trade off, the stacked cell required transparent contacts that are still not ready.

Because of the lack of transparent contacts the most widely developed and used multijucntion cell are the monolithic one, so the rest of the article will explore the implementation of such multijunction cells.

## Technical exploration of a multijunction monolithic solar cell.

After a lot of interation in the design of multijucntion cells the modern multijucntion cell is composed of different, but extremely, similar layers.

Every single layer of the monolithic solar cell consist of:

1. Windows
2. Emitter
3. Base
4. Back Surface Field (BSF)

A tunnel junction is used to connect the different layers.

The layers are different because the different material that are used to compose the 4 components, every combination of materials is most appropriate to absorb a particular wavelength.

## Components:

As in a normal junction the light is converted into electricity in the pn-junction between the emitter (2) and the base (3) and we are not focus again on such point.

### Windows and Back Surface Field

Either component are used to avoid losses by recombination.

The windows is used to reduce the surface recombination velocity.

While the BSF is used to reduce the scattering of carriers towards the tunnel junction.

### Tunnel Junction

A tunnel junction is a very high doped pn-junction, it serve two main purpose:

#### Junctions Isolation

The tunnel junction isolate the p-region from the top cell from the n-region of the bottom cell.

Without such isolation we will have an inverse junction between the different layers and the photo-voltage will drop significantly.

#### Tunnel Effect

Thanks to the high dopage the bandgap between the two region of the tunnel junction is extremelly low, this let the electrons pass, practically undisturbed between the different layers thanks to the tunnel effect.

Using the tunnel effect we achieve a contact between the different layer without practical power loss.


Surface Recombination Velocity: A measure of the rate of recombination between electrons and holes at the surface of a semiconductor, equal to the component of the electron or hole current density normal to the surface divided by the excess electron or hole volume charge density close to the surface. [2]

Reference:
[1]: http://www.superstrate.net/pv/limit/tandem.html
[2]: http://encyclopedia2.thefreedictionary.com/surface+recombination+velocity

Other:
http://www.sciencedirect.com/science/article/pii/S2215098615000245
http://science.nasa.gov/science-news/science-at-nasa/2002/solarcells/
http://pvcdrom.pveducation.org/DESIGN/SURF_MIN.HTM
http://academic.evergreen.edu/curricular/matterandmotion/chem_phys/solar_cells.pdf
