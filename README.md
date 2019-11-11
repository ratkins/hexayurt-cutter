# Hexayurt Cutter
The [Hexayurt](https://www.appropedia.org/Hexayurt_playa) is a shelter made from standard-sized sheets of 8' by 4' building material, with no waste. Versions made out of [foil-laminated polyisocyanurate insulation board](https://en.wikipedia.org/wiki/Polyisocyanurate) are popular at [Burning Man](https://burningman.org).

Mitring the edges of the panels allows the yurt to fit together better, improving insulation, dust- and light-proofing. Doing so with hand tools is very tricky, until now.

3D printing this cutter and fitting a [standard 18mm snap-off blade](https://www.amazon.com/s?k=18mm+snap+off+blade&crid=1X0J38O0XKV1W&sprefix=18mm+snap%2Caps%2C228&ref=nb_sb_ss_i_3_9) into the appropriate slot allows you to simply push the cutter over the edge of the board and cut the perfect angle.

## How to make
Download the STL file for the measurement system you're using and slice it as appropriate for your printer. Print!

## How to use
There are two sets of slots. One set will cut a 15° angle, the other 30°. Within each set there are slots for different thicknesses of board. Slide a snap-off blade into the appropriate slot and push it along the edge of the board to make a perfect cut.

For a "standard" 12' Hexayurt, you want the wall board 4' edges to all be at 30°, with the 8' edges left square. The hypotenuse of each roof triangle should be cut to 15° and the bottom edge to 30°. **NOTE: this is per the folding hexayurt [instructions on Appropedia](https://www.appropedia.org/Hexayurt_playa#The_Folding_Hexayurt), but I have not tested this first hand. If you have, could you please validate my instructions or send any corrections**.

## Contributing
The source file format is .shape, for the macOS procedural modeling prorgram [ShapeScript](https://apps.apple.com/us/app/shapescript/id1441135869?mt=12). It's kind of like OpenSCAD (very) Lite. It's just a text file and should be self-explanatory. You can download ShapeScript yourself for free on macOS and try out any modifications. I'll re-export the STLs and upload them here upon any meaningful change.

Suggestions and PRs are welcomed, especially from people who've printed one and tried it on various materials.
