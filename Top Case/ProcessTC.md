
# Top Case Machining

<img width="764" height="612" alt="Top Case On Device" src="https://github.com/user-attachments/assets/f4ecc25f-ac51-402c-9fdc-08ee4b53855b" />


This guide covers the manufacturing process, fixture setup, material considerations, and tooling details required to machine the top watch case out of aluminum.

## Fixture Holes

The top case of the T-Minus watch case is a very thin piece (7mm thin), so holding it in a standard industrial sized CNC machine can prove to be challenging. To this end a modification of the CAD was made to allow 2 M3 Bolts to be passed through and tightened to a workholding piece machined out of Poliurethane with a fitting to the internal part of the case.

| Fixture | Adapted Work Piece | 
| ----- | ----- | 
|  |  | 
| *[<img width="942" height="671" alt="Device Top Case" src="https://github.com/user-attachments/assets/890593b2-85ca-43cc-8ce8-7217f8530b3c" />](https://github.com/OffSetEyeBrow/T-Minus-Case/blob/main/STEPs/Top%20Case.STEP)* | *<img width="1017" height="756" alt="Top Case Holes" src="https://github.com/user-attachments/assets/83b8c995-d578-4bda-86cc-bdd34f39d436" />* | 

## Material

**Aluminum 5083** was chosen for the watch enclosure due to its relatively high availability, low price and great corrosion resistance:

* Generally considered "Naval Grade", which just means it's not too expensive and it has great corrosion resistance, so great choice to be in constant contact to skin oils. Only drawback I've noticed with use is its malleability, so it nicks and gets marked easily, anodization should help in this regard, as the outer layer gets higher hardness, so better resistance to wear and tear. 

* Main drawback of aluminum as case material: worsens signal strength for Bluetooth and WIFI antenna, so when updating the time and downloading weather, its best to keep it close to the internet modem.

### Stock Dimensions: 

* For the top case a 10mm plate was chosen and cut to 70 x 48 mm to allow some room of error when squaring the work piece. in theory you could get a thinner plate, but it would need to be well squared and have decent surface finish as to be used directly in the machining steps

## Tooling & Machining Parameters

Because of the small dimensions of the case, most of the tools used are on the smaller size, going down to a 2mm end mill, and only up to a 20mm face mill for facing.

### Tool Table

| Tool ID | Tool Description | Diameter (mm) | Flutes | Primary Operation | Tool Image | 
| ----- | ----- | ----- | ----- | ----- | ----- | 
| **T01** | Face Mill | 20mm | 4 Flutes | Stock Facing & Squaring |<img width="549" height="139" alt="D20 Head" src="https://github.com/user-attachments/assets/e7a89e5f-f9a1-4b49-8074-cf3d03e80b15" />| 
| **T02** | End Mill | 8mm | 2 Flutes | Roughing & Pocketing |<img width="550" height="139" alt="D8 Top" src="https://github.com/user-attachments/assets/d01a6a11-7283-4754-b33b-2e022ef7c000" />| 
| **T03** | End Mill | 6mm | 2 Flutes | Roughing & Pocketing | | 
| **T04** | End Mill | 4mm | 2 Flutes | Roughing & Finishing |<img width="439" height="109" alt="D4 Top" src="https://github.com/user-attachments/assets/42ab9791-aebc-4629-a71b-d6fccb1cf677" />| 
| **T05** | End Mill | 3mm | 2 Flutes | Finishing & Pocketing | | 
| **T06** | End Mill | 2mm | 2 Flutes | Finishing & Slot Milling |<img width="549" height="138" alt="D2 Top" src="https://github.com/user-attachments/assets/df342f2c-3658-411a-809b-88cddb1312c6" />| 
| **T07** | Chamfer Mill (90°) | 4mm | 2 flutes | Chamfer Milling, Edge Deburring & Spot Drilling|<img width="548" height="139" alt="D4 Chan" src="https://github.com/user-attachments/assets/2f039dbc-afc5-490c-8c0e-51537a08ec6a" />| 
| **T08** | Twist Drill | 3.4mm | 2 Flutes | Fixture Holes Drilling | | 
| **T08** | Twist Drill | 2.5mm | 2 Flutes | Screw Holes Drilling | 
| **T10** | Twist Drill | 1.7mm | 2 Flutes | Thread Holes Drilling | 
