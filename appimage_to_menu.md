Open terminal and run as administrator:

1. cd /usr/share/applications
2. touch APPNAME.desktop
3. gedit APPNAME.desktop

Copy & Paste to file:

[Desktop Entry]   
Name=APPNAME   
Exec={LOCATION_OF_APPIMAGE}    example: Exec=/home/tmollov/app_images/myapp.App.Image  
Comment=DESCRIPTION_OF_APP  
Icon={LOCATION_OF_APP_ICON}    example: Icon=/home/tmollov/app_images/myapp.png  
Type=Application  
Terminal=false  
Encoding=UTF-8  
Categories={CATEGORY_OF_APP}   example: Categories=Graphics
