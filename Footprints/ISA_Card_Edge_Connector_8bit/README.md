# ISA_Card_Edge_Connector_8bit
A Kicad footprint describing the 8-bit ISA card edge connector.

## Revision 1:
- Added F.Mask and B.Mask areas over card edge fingers, so they do not need to be added manually on a board design.
- Added some distance measurements to the "Eco2.User" layer, as well as a suggested grid spacing, to make it easier to set the edge connector width.

![Rev1 Image](../ISA_Card_Edge_Connector_8bit/Images/ISA_Card_Edge_Connector_8bit_Rev1.PNG)

## Revision 0:
- First release of the footprint.
- Footprint origin is aligned to the bottom centre of Pad A01 (Pad B01) of the corresponding 8bit ISA card edge connector.
- Board edge guides are on the "Eco1.User" layer. Take care as they are strange decimal fractions.
- Board edge guide duplicated on the "F.Fab" layer adjacent to the card edge connector (can't remember why I did this...)
- See corresponding ISA card edge reference drawing for exact board edge locations.
- Corresponding Keystone 9202 hole location reference shown as a cross in the upper right hand of the symbol on the "Eco1.User" layer.

![Rev0 Image](../ISA_Card_Edge_Connector_8bit/Images/ISA_Card_Edge_Connector_8bit_Rev0.PNG)
