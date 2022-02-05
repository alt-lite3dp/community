## Problem:
I acquired my kit from Mouser Electronic but it solidify everything at the middle even though I set the exposure time to 3 seconds only. This make the printer simply unusable.

## Root cause:
After investigation, the root cause is the beam angle of the ultraviolet LED is too narrow. That makes the center session of print surface receive high intensity of ultraviolet light that able to penetrate the mask.

## Solution:
My final solution is simply add 15 mm of extra separation for the light beam to diffuse.Some M3 Male Female Hex Brass Spacer would do the job easily. (And I have many of these)
Since the original base part no-longer fit after the modification, I modify the file to fit the modified printer so that it does not leak out ultraviolet light.

## Preferred tools:
1. FDM 3D printer
2. Black colored fliament
3. M3 screw tap

## Bill of material:
1. 6 pieces of ![15 mm M3 Male Female Hex Brass Spacer] (https://hk.element14.com/ettinger/05-13-153/spacer-m3x15-ni/dp/1466869?gclid=Cj0KCQiA3fiPBhCCARIsAFQ8QzUBVi5ktcUXnQlwDdsfskdFQfebgMBmz5QJDubC1DPWpBHUhVl7b4saAmrEEALw_wcB&mckv=sb4PsLRXk_dc|pcrid|432655398157|pkw||pmt||slid||product|1466869|pgrid|106281172011|ptaid|pla-899072975402|&CMP=KNC-GOO-SHOPPING-1466869)
2. 1 print out of "50mmHeight_Base_r2.stl".

## Usage:
1. Add the extra height to the printer by  15 mm M3 Male Female Hex Brass Spacer
2. If "50mmHeight_Base_r2.stl" is not printed out by black material, paint it in black color. This would avoid many problems caused by internal reflection of UV light.
3. Use M3 screw trap to 
4.  Install "50mmHeight_Base_r2.stl" as-is the original one.

