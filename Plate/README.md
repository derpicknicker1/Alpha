# Instructions

SVG and Illustrator file for top and bottom plate. If importing into a CAD program, convert it to DXF first or verify the dimensions are correct when you import it. 

Countersinking mounting holes may be done manually with a drill press.

3mm acrylic needs a cutout for stab wire.

## Generate a Plate

Make the layout [here](http://www.keyboard-layout-editor.com/#/)

Then you have something like the following (raw data):
```
[{a:7},"Q","W","E","R","T","Z","U","I","O","P"],
["A","S","D","F","G","H","J","K","L",{c:"#c9b81e"},"Ent"],
[{x:0.5,c:"#cccccc"},"Y","X","C","V",{c:"#00aacc",w:2},"",{c:"#cccccc"},"B","N","M"]
```
You can use this for your alpha.


Copy this and go to [this page](http://builder.swillkb.com/)

* Paste it there.
* Set `Switch Type` to MX (t_3)
* Turn `Edge Padding` on and set all to 1.5mm
* Turn on `Plate Corners` and set it to 3.5mm
* Click `Draw My Cad!!!`
* Download DXF file 
