# Modkit_extractor for FiveM
Same as the sirenId finder just a simple python made to extract modkit IDs from the carcols.meta files. Built by ai but edited by me from the original sirenId extractor.

Place inside your main resource folder and right click inside the directory and open in terminal. 

Once terminal is open type ```python modkitId_extractor.py``` and hit enter. 

The python script will run in terminal or powershell and set results in 2 .txt files.

  One will be a simplified .txt containing all the modkit IDs in the carcol.meta files in your server. 
  The other will be any duplicates found if there is any. You may see vehicle1 and vehicle2 that will have the same modkit ID but that will be ok espicially if they are in the same folder. 

If you have one folder of vehicle files in your resources change line 9:
  ```self.base_directories = ["emergency"]``` to the folder name you need to search. Mine is labeled [emergency] so that is what I used.

Likewise if you have multiple folders in your resources you would like to check use line :
``` directories_to_search = [ #if you have multiple vehilce folders put them here as they are typed in your resource folder.
        "[emergency]",
        "[Vehicles]",
    ]```
  And change or add as needed for the folders you have.

If you see anything that can be approved on submit a PR. 
