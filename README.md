# DinoSimulator
An automation of the popular offline game on Chrome that is able to avoid any obstacles approaching. Using ```pyautogui``` and ```keyboard``` to automate the movements and whereabouts of the dino.
# Known Issues
1. The obstacle region has some difficulties in regards to a universal coordinate system, hence it the region coordinates depend on the local machine of the user and needs to be updated accordingly.
2. As this is a static code that relies solely on the pixels of the upcoming obstacle, the code or automation suffers with back-to-back obstacles that have less gap between them will cause the automation to fail or deteriorate in quality.
3. Lack of dynamic programming that hinders the quality of the automation and thus is not very consistent
4. The max score reached on my local machine with this code is ```2349```, feel free to try it out after adjusting the obstacle region according to your local machine!

