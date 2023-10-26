# Parametric-compound-cycloid-reducer
An easily editable reducer designed in Onshape.

![image](https://github.com/OrnithopterX/Parametric-compound-cycloid-reducer/assets/109166435/2b450d9b-061f-4ed6-8846-5b364425f419)


# Printing
  If you just want to print the default reducer, the .STL files can be found on Printables and Thingiverse.
  
 > Printables: https://www.printables.com/model/499046-parametric-compound-cycloid-reducer
 > 
 > Thingiverse: https://www.thingiverse.com/thing:6063196
 > 
 > The CAD can be found and viewed here: https://cad.onshape.com/documents/c2a2e521f493f2e65ef4a7b8/w/77562cc514e7b5cb2fbcdb98/e/b7dbfba2af92f823ef527d3f

  notes:
> For best results your printer should be able to pass a basic calibration test.
> 
> The design is not backdrivable.

  For reducing backlash:
> It is not uncommon to see <1 degree of backlash at the output shaft, when setup properly!
> 
> I've uploaded three diffrent cycloids, each 0.1mm larger than the last. If backlash is unsatisfactory simply print a larger verison.
>  
> If more than +0.2mm is needed, edit the "thicken" profile for each cycloid (labeled "7tooth" and "8tooth" by default). Then right click on the "Assembly for reducer" and export the file.
  
 
  
# Tips for Editing
If the default reducer/reduction does not fit your needs, the OnShape document is available here:
>https://cad.onshape.com/documents/c2a2e521f493f2e65ef4a7b8/w/77562cc514e7b5cb2fbcdb98/e/b7dbfba2af92f823ef527d3f
>To make changes to the design, simply copy the onshape document and edit your new file. You will need an onshape account!

Tips for editing the Cycloids:
  For those wishing to make changes to the reduction ratio, generally it is only necessary to change the cycloids located in the base, output shaft and the compound cycloid assembly.

All cycloids should have the same eccentricity to function properly. 

Diameter. The diameter of each cycloid should be carefully selected for best results. To make things easier a diameter constant can be used. The diameter constant of the cycloid is determined by dividing the diameter by the number of teeth. This should remain consistent for all cycloids in the reducer, except for the base and output shaft.

Diameter of cycloid assembly:
  [diameter = number of teeth * diameter constant]

Diameter of base and output shaft:
[diameter = (number of teeth * diameter constant) - eccentricity].

More to come...
