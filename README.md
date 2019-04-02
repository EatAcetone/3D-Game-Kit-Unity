# 3D-Game-Kit-Unity
Here are some fixes for bugs in 3D Game kit for Unity March 2018


## *CHANGES*

     
+ Basic Errors
  - Assets/PostProcessing/Editor/PropertyDrawers/MinDrawer.cs(6,34): error CS0104: 'MinAttribute' is an ambiguous reference between 'UnityEngine.PostProcessing.MinAttribute' and 'UnityEngine.MinAttribute'
  
  - Replace code (Should keep changes after saved and uploaded) if this error shows up go to the MINDRAWER . md file I created in this respository file and copy the code and paste it inplace of what is on your file in the 3D game kit code VV
  
  - To get to the MINDRAWER . css file just double click on the error in the console panel on your project and it should open visual studio or whatever program you use. *if this does not work go to **Assets > Post Processing > Property Drawers > MinDraw.cs**
  
  - **AFTER YOU SAVE THE CHANGES** A box in unity will ask if you want to keep changes/update etc > Click YES (I've made a backup) and then let it update. The errors will go away.
              
              
### MUST DO ON EACH MACHINE

+ Fix this error
  - **Error:** Assets/3DGamekit/Scripts/Game/Utility/QualitySettingPostprocessProfileSwitch.cs(19,37): error CS0012: The type 'Enum' is defined in an assembly that is not referenced. You must add a reference to assembly 'netstandard, Version=2.0.0.0, Culture=neutral, PublicKeyToken=cc7b13ffcd2ddd51'.
  
  - Fixed by going to **Window > Package Manager > Post-processing > UPDATE-TO**
  - Once updated the error should go away. This may be needed everytime you open this project on a new machine.
        *THIS IS IMPORTANT TO DO SO PLEASE DO THIS.*
