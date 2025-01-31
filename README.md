<b> About the App: </b>  
*Din Quick Launch Toolbar* App is a simple App with auto-hide feature for Windows 11/10 to manage Shortcuts. This App is available on Microsoft Store. See following YouTube Video for a quick demonstration of the App.   
For any inquiries on this App, please email us at dinvision.bc@gmail.com

[![IMAGE ALT TEXT](http://img.youtube.com/vi/548o5cCr1VA/0.jpg)](https://www.youtube.com/watch?v=548o5cCr1VA "Quick Launch Toolbar Demo")

<b>Updates in new verisons  ![image](https://github.com/user-attachments/assets/9ca49cb0-9956-47aa-a1fb-9bfc80e21a91)
</b>  
Jan 31, 2025:   
Version 1.0.57.0: Added function ![image](https://github.com/user-attachments/assets/3180731b-d9ea-4689-b9e7-d58f06006d7d)
to create ICO icons from Image files, added options in INI file to resize Control Buttons ![image](https://github.com/user-attachments/assets/48ed36f0-42fb-48c3-b682-5d6f990eba77)
.  
Jan 27, 2025:  
Version 1.0.55.0: Added support for grouping shortcuts in the Toolbar by creating sub-folders.  
Version 1.0.54.0: Display icons without shortcut arrow, added options in INI file to show Toolbar Border, change Shortcut Text Color.    
  
<b>Group Shortcuts  ![image](https://github.com/user-attachments/assets/82d5596f-9b4b-404a-94a0-8b43a956166b)
</b>  
Create sub-folders to display shortcuts in separate groups as shown in example below. The 3-digit prefix is for sorting purpose.  
  
![image](https://github.com/user-attachments/assets/3569ca71-4973-4d9f-87c5-aa44d54ff68b)






![image](https://github.com/user-attachments/assets/4372c362-850b-4ce6-817b-756a24aa754b)






<b>Sorting and Naming the Shortcuts:</B>  
For easy sorting, name the Shortcuts with 3 digit numeric prefix as example below.    
"010 Paint"  
"020 Notepad"  
"030 Excel"  
Then, if you need to insert new shortcuts in-between, use the in-between numeric prefix such as:  
"015 Outlook"  
The 3-digit numeric prefix is automatically hidden in the Shortcut ToolTip.  

<b>Customization:</B>  
The Toolbar can be customized by modifying the values in the INI file as shown in the Demo video. 

<b>Troubleshooting:</B>  
If you mess up the INI file settings, and do not have backup, you can just close the App, delete the INI file and restart the App, it will automatically re-create the INI file with default settings.

<B>Taskbar Display Setting:</B>  
For older versions, if you prefer not to display the app in the Taskbar, set 'AlwaysShowOnTaskbar' to 'No' in the INI file. Restart the App. Then the App will be displayed in the Taskbar only when you minimize it.  
![image](https://github.com/user-attachments/assets/32530b33-bbfe-4917-9355-ef02efb3f6e6)



<b>How to change Toolbar Color:</B>  
To change the color of the Toolbar, change the Color name for the "ToolbarColor" parameter, you can choose color name from the following list  
[Color Names List](https://learn.microsoft.com/en-us/dotnet/media/art-color-table.png?view=windowsdesktop-8.0)  
For example, change the color as below in the "ini" file. (in version 1.0.52.0 and newer)  
ToolbarColor=LightBlue  
ToolbarBorder=Yes  
ToolbarBorderColor=Green  
Save the "ini" file, close and re-open the Toolbar to apply changes.  

![image](https://github.com/user-attachments/assets/4f5ab5e1-d552-4e9d-b784-4104081970e6)

<b>How to customize Icons Display:</B>  
See this YouTube Video [How to customize Icons Display](https://www.youtube.com/watch?v=RTC05oaLqeM) to see demonstration of the configuration such as following.

| Toolbar Display                                                                                             | ini settings                                                                                                                                                                                      |
|---------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|![image](https://github.com/user-attachments/assets/ff0b5b9e-7aa2-4bb1-b960-37d6176d6042)  | <sub>ButtonSizeWidth=80<br>ButtonSizeHeight=75<br>IconSizeWidth=32<br>IconSizeHeight=32<br>ShowButtonText=Yes<br>ToolbarColor=DarkSlateGray<br>ButtonTextImageRelation=ImageAboveText<br>ButtonImageAlign=TopCenter<br>ButtonTextAlign=MiddleCenter<br>ToolbarBorder=Yes<br>ToolbarBorderColor=DarkGray<br>ButtonTextColor=White</sub> |


| Toolbar Display                                                                                             | ini settings                                                                                                                                                                                      |
|---------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![image](https://github.com/user-attachments/assets/d89f2772-5864-4745-81b4-087772cfab7e) | <sub>ButtonSizeWidth=80<br>ButtonSizeHeight=75<br>IconSizeWidth=32<br>IconSizeHeight=32<br>ShowButtonText=Yes<br>ToolbarColor=DarkOrange<br>ButtonTextImageRelation=ImageAboveText<br>ButtonImageAlign=TopCenter<br>ButtonTextAlign=MiddleCenter</sub> |





| Toolbar Display                                                                                             | ini settings                                                                                                                                                                                      |
|---------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![image](https://github.com/user-attachments/assets/c1b05bf8-4f87-4910-9371-276e3593cc46)| <sub>ButtonSizeWidth=150<br>ButtonSizeHeight=36<br>IconSizeWidth=24<br>IconSizeHeight=24<br>ButtonBorderSize=1<br>ShowButtonText=Yes<br>ToolbarColor=LightCoral<br>ButtonTextImageRelation=ImageBeforeText<br>ButtonImageAlign=MiddleLeft<br>ButtonTextAlign=MiddleLeft</sub> |

<B> End </B>



