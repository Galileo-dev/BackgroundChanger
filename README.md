# Dynamic Wallpaper.
Changes the background depending on the time of day.

## Installation.
1. Downlaod The [latest Release](https://github.com/Galileo-dev/Dynamic-Wallpaper/releases).
2. Extract The .zip file.
3. Go to windows search and open Task Scheduler.
4. At the top left select ```Action > Import``` Task now find the DynamicWallpaper.xml which is located in the tasks folder inside the extracted directory .
6. Go to actions, select the first one and hit edit.
7. For the program/script hit browse and locate the dynamic-wallpaper.exe file.
8. For Start in use the Program/script file directory but remove the \dynamic-wallpaper.exe at the end
9. Then hit ok until exited.

## How to Change images
First you need to get some images. I would suggest you check out this website (https://dynamicwallpaper.club/gallery)

Images are stored in the ``` stored_images ``` folder. The image names refelect at what time the program will change the wallpaper.
So if an images name is ```14.jpeg``` the wallpaper will change to that image at ```14:00``` or 2pm and so on.

## Future Plans.
- Create an installer
- Use sun position to determine wallpaper
- Create a UI

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Disclaimer
The images located in the ``` stored_images ``` folder belong rightfully to Apple Inc.
if requested these images may be removed and if so please follow the instructions above to use your own images.
