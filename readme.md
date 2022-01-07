# How to get started

Fork this repo to your Github. I recommend public mode for proof of work/project presentation in future interviews.

# Interfaces for Your Engine -> MicroLiquid Vehicle

## Dimensions
- Rocket Tube OD: 2in
- Rocket Tube Thickness: 0.049in
- Standard Skin Fastener: [M2x0.4 Countersunk Torx](https://www.mcmaster.com/92703A146/), 8mm; 8X or 12X
- Retaining Ring: [Internal Retaining Ring for 1-7/8" ID, Black-Phosphate 1060-1090 Spring Steel](https://www.mcmaster.com/99142A580/).
- Retaining Ring Groove: (undersized) Diameter 1.922" x Width 0.068"

## Other values
- Nitrogen initial pressure: ~1000psi
- Flow control orifice (you choose): [Threaded Flow Control Orifice with Brass Body Plug with Hex Socket, 1/8 NPT Male](https://www.mcmaster.com/2712T51/) (might switch to UNF thread based on burst disk design)
- Target Liftoff TWR: 5
- Estimated takeoff weight: 8.5 lb
- Estimated dry weight: 5 lb

# Parts to manufacture
The top of your injector must interface with the bottom of the fuel tank and act as its bulkhead, with the standard O-ring groove. See MLKT/upstream-salmon-rocket/cad/rocket/Rocket.SLDASM for how this fits together. Cut a throughfeed for 1/4 inch LOX tube and a burst disk and flow control orofice hole stack as seen in the reference assembly. Provided in this repo is your

You can either use my liquid-tube or cut your own to your desired length. Fin attachement scheme TBD. It could be a fin can that transfers across body tubes, or each tube could glue on their own fins.