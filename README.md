# Neopets-Data
Information about neopets.

IDs needed to fetch images of pets from pets.neopets.com. Each file contains the IDs for every color of that pet, as well as a boolean indicating whether an unconverted version of that color exists. To get a pet's image, you can plug it in like : http://pets.neopets.com/cp/<PET_ID>/<EXPRESSION>/<IMAGE STYLE>.png. The value of the "disco" key in aisha.json is {"female":"74x2klsd","male":"mbncmc4m","UCexist":true}, meaning a female disco aisha can be accessed at http://pets.neopets.com/cp/74x2klsd/1/4.png and a male at http://pets.neopets.com/cp/mbncmc4m/1/4.png, and that unconverted artwork of disco aisha exists.
