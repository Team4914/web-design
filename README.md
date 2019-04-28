# General Information
Hosted @ https://team4914.github.io/web-design/VPCI-Robotics-Website-master/basic/

Found @ https://schoolweb.tdsb.on.ca/victoriapark/Students/Co-Curricular

## Instructions on how to update various pages
To *EDIT* Gallery:
**_Please note - all GALLERY photos are .JPG_**
1. Go to https://github.com/Team4914/web-design/tree/master/VPCI-Robotics-Website-master/Website_Dependencies/Website_Images/Team_Photos
2. Upload and overwrite an existing .JPG image
3. Go to https://github.com/Team4914/web-design/blob/master/VPCI-Robotics-Website-master/Website_Dependencies/Image_Gallery/Image_Gallery.html
4. Edit the alt next to the image id equivalent to the overwritten file to match the current season.
e.g.

img src="../Website_Images/Team_Photos/Robotics_8.JPG" onclick="onClick(this)" class="w3-hover-opacity" alt="Team 4914 @ Southwest International"

If the photo is from DCMP, an example alt would be

img src="../Website_Images/Team_Photos/Robotics_8.JPG" onclick="onClick(this)" class="w3-hover-opacity" alt="Team 4914 @ DCMP"

To *EDIT* Sponsers:

**_Please note - all GALLERY photos are .PNG_**
1. Go to https://github.com/Team4914/web-design/tree/master/VPCI-Robotics-Website-master/Website_Dependencies/Website_Images/Team_Photos
2. Upload and overwrite an existing .PNG image. Give the new file an appropriate name

To *ADD* Sponsers:

**_Each ROW can hold a maximum of 4 sponsers_**
1. Go to https://github.com/Team4914/web-design/tree/master/VPCI-Robotics-Website-master/Website_Dependencies/Website_Images/Logos
2. Upload a .PNG image and rename with an appropriate name. Then go to https://github.com/Team4914/web-design/blob/master/VPCI-Robotics-Website-master/Website_Dependencies/Image_Gallery/Sponsor_Images.html
3. If applicable, declare a new row using 

**_div class="w3-row-padding w3-center w3-section"_**

**_/div_**

4. Add in an image using

**_div class="w3-col m3_**"

  **_img src="../Website_Images/Logos/REPLACE_WITH_PNG_NAME.PNG" onclick="onClick(this)" class="w3-hover-opacity" alt=""_**
  
**_/div_**


