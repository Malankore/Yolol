# ISAN Deltas Script
Created by Mutleyx & Agonarch  
  
**To use this script you will need the following:**  
1x Text Display  
1x Adv. Yolol Chip  
1x Memory Chip (Memory Module for ISAN)  
  
**On your Text Panel:**  
Rename the PanelValue to Deltas  
  
**On your Adv. Yolol Chip:**  
Enter the code included in Deltas.yolol  
  
**On your ISAN YOLOL chip:**
Change Line 10 to:  
:at=g b=v-:a b*=b br=(b-lb)/4 lb=b u/=:a u=11 :CL=1 gotovv
  
Change Line 12 to:  
:at=a d=v-:a d*=d dr=(d-ld)/4 ld=d u/=:a u=9 :CL=1 gotovv
  
Change Line 15 to:  
i+=ar b+=br c+=cr d+=dr :CL=0
