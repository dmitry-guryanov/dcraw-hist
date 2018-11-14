# About

This is a modification of Dave Coffin's dcraw, which prints histogram of raw data. The output is 5 columns. The first one is value and next four columns are number of Red Green Blue and second Green pixels with that value in a RAW file.

Please, don't use it for any sort of important tasks, because I've made it just for fun and to learn, how camera works. It works with Canon's and Nikon's files, others may not work correctly.

Compile it with
> make

Run without any options:
> ./dcraw-hist <raw file>

Sample output:

```
     VALUE      R      G      B      G

         1      0      0      0      0
         2      0      0      0      0
         3      0      0      0      0
         4      0      0      0      0
....
      4269    501    559    212    553
      4270    671    415    217    416
      4271    691    600    157    591
      4272    538    638    221    555
      4273    697    362    215    435
      4274    522    572    149    581
      4275    678    432    199    455
      4276    532    600    224    517
      4277    673    588    163    595

```
