Kouta Hania - NatsuDragneel808

(This tutorial is ui/screen scaling 400% bug fix in LibreSprite 1.0)

The Issue:
As someone who casually deals with attempting to touch all the features in whatever app I open, I believe that this feature should be removed. There are 4 options in preferences --> general --> screen scaling (default=200%) & ui scaling (default=100%). The 4 options are 100%, 200%, 300%, and %400% in the drop down. I ended up setting both to 400% which made the app completely unusable since it was scaled so close I could only see the top of the menu for File/Edit/Sprite and La out of Layers. I think 200% should be the maximum to prevent anyone else from messing it up like I did. Why? Because I spent hours upon hours pulling my hair out trying to fix the issue. There's no support (forums/tutorials/YouTube videos/git/googlesolutions/etc) for this issue and reinstalling the libresprite files or restarting the pc doesn't fix it. However, after calming myself and thinking I managed to fix the issue and return the app to normal. I'm opening a project on my GitHub for you to follow a fix if you run into this issue.

Reproduce:
![Capture](https://github.com/NatsuDragneel808/desktop-tutorial/assets/76171803/dd228431-e02b-4f64-8e15-ba1101e5502c)
![Capture2](https://github.com/NatsuDragneel808/desktop-tutorial/assets/76171803/f03f4926-9ffd-4810-aa8f-c2ac68ac7d64)
![Capture3](https://github.com/NatsuDragneel808/desktop-tutorial/assets/76171803/b469a576-1bc4-47b8-87ad-eef93b318f32)
![Capture5](https://github.com/NatsuDragneel808/desktop-tutorial/assets/76171803/e1db9993-3264-420a-8795-6b292a1b26f1)


"Pictures and Instructional Text"

Fix:
![Capture5](https://github.com/NatsuDragneel808/desktop-tutorial/assets/76171803/e4381ce4-3e8e-490b-8801-cec693050de7)
Step 1: Navigate using the arrow keys to edit. Afterward, the drop-down menu appears make sure you're on the top selection. Mine was *undo history*. From there press your arrow key up (Although you can't see it, you'll be hovering above preferences) Press enter and you should now be in preferences. 
![Capture6](https://github.com/NatsuDragneel808/desktop-tutorial/assets/76171803/10d30a02-4618-4e0b-a239-ec89f9b6c9a2)
Step 2: Click on the configuration file.
![Capture7](https://github.com/NatsuDragneel808/desktop-tutorial/assets/76171803/c3a2dd76-1fcd-4c61-bf84-3c2011b49c6d)
Step 3: You've been redirected to the folder that contains all your primary documents for libresprite. And no, not the portable download. All the files are saved locally on your PC for libresprite. IMPORTANT: Make sure you close libre sprite after opening the configuration files!!! Otherwise, this won't work. Right-click on libresprite.ini and delete the file.
![Capture8](https://github.com/NatsuDragneel808/desktop-tutorial/assets/76171803/374a8ce3-a6af-4243-be2e-62b81ea07df0)
Step 4: Re-open libresprite.
![Capture9](https://github.com/NatsuDragneel808/desktop-tutorial/assets/76171803/d0f6160c-8cfe-4f79-83b0-2ea93316b66a)


Step 5: Enjoy TwT

Links:
Bug Report - https://github.com/LibreSprite/LibreSprite/issues/445
Libresprite - https://libresprite.github.io/#!/
