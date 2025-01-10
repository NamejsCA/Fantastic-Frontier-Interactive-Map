# Fantastic-Frontier-Interactive-Map
Roblox Coordinates to Interactive Map

Step 1:
Game Example: Fantastic Frontier (Roblox)
With the Coordinate Finder Script you will have to setup the path that it needs to go for example mine will go through all the folders in Spawners to find a model called BirdSpot then stores the coordiantes in a txt.

Step 2:
I had a problem where the coordinates went 90* and flipped.
Opening Coordinate Fixer.html and choosing the file you got from Coordinate Finder (Mine was BirdSpot_Coordinates.txt) and placing it there will rotate it to North so its accurate.
If this doesnt work for you try asking chatgpt for a better rotation.

Step 3:
Editing The Map.html

You will probably want to change the image link (I used Imgur Direct link).
        const imageUrl = 'https://i.imgur.com/1LiUfk5.png'; (Example)
        
The image will probably appear somewhat random spot, so try finding the position x y with
Image Slider.html then change to correct
        const xOffset = -1671; (Example)
        const yOffset = -2183;

Step 4:
Replace the coordinates with your own (Step 2), change the Main category's name to whatever you want, but you will also need to change the code at the bottom.
Maybe you can do this step with chatgpt.
