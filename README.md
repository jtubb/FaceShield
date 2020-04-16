# FaceShield

Rapid prototype face shield for front line medical workers. The goal was to develop a face shield that could be made quickly with materials not traditionally being consumed by other Covid-19 response efforts, easy to sanitize/replace parts, and keeping the price point under $5 per unit. When you're done you'll have a mold that can make ~25 visors in 15 minutes, timing the pours correctly you can cast them continuously. The mold can be reused thousands of times.

This project is released under the Creative Commons Zero Universal license. You may do whatever you like with these designs, my advice is work closely with the medical workers you will provide these too to make sure they are being used appropriately.

For a quick video overview see: https://youtu.be/5g29kG8YU5k

# Tools

80W+ Laser Cutter with minimum 20"x20" bed, or printer+jigsaw.

Table saw, or circular saw, or jigsaw, or handsaw.

Mixing pot - Cheap stainless steel pot

Mixing utensil - I used a cheap silicon spatula


# Software


DeepNest.IO - https://github.com/Jack000/Deepnest


# Materials


2 - 2'x4' 1/4" MDF Sheets from Home Depot - $6.50 ea

1 - Wood Glue - $5

1 - Spray on polyurethane - $7

1 - Silicon Caulking - $5

1 - Silicon Spray - $7

1 - EasyFlo 60 76 LB Kit - $461.00 (https://www.polytek.com/products/easyflo-60-liquid-plastic)

1 - PlatSil 70-71 16 LB Kit - $286.00 (https://www.polytek.com/products/platsil-71-11-silicone-rubber)

7 - 75ft 1/4" PVC self adhesive foam - $7 ea

800 - A4 PVC Sheets - $35 200pc (I used Fellowes Crystals Clear PVC Binding Covers, 8mil Letter, 200 Pack (5204303))

1000 - Elastic Straps (I am using rubber bands, other alternatives include hair bands, leggings cut to bands, string, shoelaces, etc)


Total cost ~$1000 + ~$80 Shipping of the material from polytex.


The large cast takes ~2oz of resin. With 10 gallons of EasyFlow you'll get ~640 masks. 
Price per unit $1080/640 = $1.69


Once the mold is made each additional batch of 640 visors is only material costs. EasyFlo 60 + A4 PVC Sheet + Elastic Straps + PVC foam = ~$730


Price per unit Batch 2 $1810/1240 = $1.45

Price per unit Batch 3 $2540/1860 = $1.36

Price per unit Batch 4 $3270/2480 = $1.32


You can also gain more efficiency by using the blank to create more than one mold.




# Directions


If your laser bed is 20" square you can skip to Step 2 and just use the "20InchBedOptimizedLayout.dxf"

Step 1. Import the various sizes of Faceshield DXF into DeepNest. The only setting I changed was to increase Part Rotations to 16 and clearance to 4mm. Set a bounding box appropriate for your laser bed.

![Import](https://github.com/jtubb/FaceShield/blob/master/images/DeepNestImport.png)

![Settings](https://github.com/jtubb/FaceShield/blob/master/images/DeepNestSettings.png)

Step 2. Pull the optimized part layout into your laser cutting software of choice, I use LightBurn. Begin the cut. For MDF my speed+feed for an 80W laser is 7mm/s at 40%power.

Step 2a. If you do not have access to a laser cutter, you can also print the DXF as a template, glue it to the MDF, and cut it out with a jigsaw.

Step 3. Sand any sharp edges and make sure the visor channel is cleared of all debris.

Step 4. Glue all blanks that were just cut out to the second 2'x4' sheet of MDF using standard wood glue, you should be able to fit at least 25 blanks. Wipe up any excess glue. Make sure to keep the pieces centered on the sheet of MDF.

Step 5. Trim 1" of material from each edge of the 2'x4' with the blanks glued to it. Make sure there is at least a 1/4" between any blank and the edge after cutting.

Step 6. Using some 1" square scrap pieces of wood, use wood glue to fix the 1" MDF strips from Step 5 to create a lip around the 2'x4' MDF sheet.

Step 7. Once the glue has dried apply silicon caulk to the lip where it meets the 2'x4' MDF sheet. This will prevent any leaks and provide extra holding for the lip.

Step 8. Once the silicon has dried ensure the mold is clean of any debris, and then coat the mold with polyurethane spray. Makes sure to spray from all angles.

Step 9. Once the first coat of polyurethane has dried apply a second coat.

Step 10. Once the second coat of polyurethane has dried apply a coat of spray silicon. Make sure to spray from all angles. Wipe up any puddling.

Step 11. Make sure the mold is leveled and on a flat surface. I recommend putting a plastic sheet under it in case there are any leaks.

Step 12. Mix the PlatSil 70-71 per the manufacture instructions. The material is fairly sticky and mixing was done best in a stainless steel container with a rubber spatula. Once cured any excess can be easily peeled off the mixing tools.

Step 13. Pour the mold material into the center of the mold blank. Use the spatula evenly spread the mold material to the edges of the mold blank. If you have a palm sander or another tool that shakes quite a bit run it along the edges of the mold or the surface the mold is on to vibrate any trapped air bubbles out. Monitor the level of the mold blank for the first 20 minutes to make sure it is level and won't overflow.

Step 14. Let sit approximately 24 hours. I demolded after 14 hours and the let it continue to cure for the other 10 hours. If you plan to make more molds be careful to not damage the blanks when removing, repeat steps 10 through 14 for each mold. The blank should hold up well enough to make 4 or 5 molds.

Step 15. Clean the mold of any debris and ensure it is level.

Step 16. Prepare the EasyFlo 60 per manufacture instructions. It only has a 2 minute work time. I delt with this by having a pint container of part A and a separate container of part B on my workspace. I added 3oz of part A and part B to my mix pot, stir for 15 seconds until the mix went clear, then pour into the mold. That was enough to fill ~3 visors. I repeated this until all molds were filled. I was pouring in a cold basement so I used a heat gun on low to help cure the material, a hair dryer would work just a well.

Step 17. Demold per the manufacture instructions. It took approximately 15 minutes for the pieces to be cured enough to remove, be gentle as they will still be a little soft.

Step 18. Let demolded pieces harden per manufacture instructions. Approximately 2 hours.

Step 19. Sand the top side of the cast visors if necessary.

Step 20. Apply approx 8" of 1/4" foam to the inside brim of the visor.

Step 21. Insert PVC shield material into the visor channel.

Step 22. Attach elastic bands to the ear pieces and begin fitting the visor.



# Shield Material

I used a length of nichrome wire run between 2 hinged boards to make a simple plastic bender. Anything that can heat the A4 PVC material to ~140-150 degF can be used. See the Plastic Folder directory for a simple arduino temperature controller and designs for the folder.

From the landscape (hotdog) orientation, I created a 1/4" fold on the left and right side of the A4 PVC sheet. This will provide rigid edges for the mask. If using a small visor make a 1/2" fold on each side. Then on the top edge make a 90deg bend.

Alternatively if you don't want to bend the PVC you can apply staples along the top edge of the sheet.




# Use and Sanitization

Don the face shield per CDC recommendation (https://www.cdc.gov/vhf/ebola/hcp/ppe-training/n95respirator_gown/donning_13.html).


If made with a urethane resin the visor can be sanitized in an autoclave, the foam strip will need to be removed for this.


If sanitizing with O2 the entire assembly can be placed in the sanitization chamber.


Elastic bands should be replaced every use.
