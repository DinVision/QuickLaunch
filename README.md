<p>
Hello to users from around the world!😊<br>
<img src="https://flagcdn.com/28x21/in.png" width="28" height="21" alt="India" title="India">
<img src="https://flagcdn.com/28x21/jp.png" width="28" height="21" alt="Japan" title="Japan">
<img src="https://flagcdn.com/28x21/de.png" width="28" height="21" alt="Germany" title="Germany">
<img src="https://flagcdn.com/28x21/vn.png" width="28" height="21" alt="Vietnam" title="Vietnam">
<img src="https://flagcdn.com/28x21/us.png" width="28" height="21" alt="United States" title="United States">
<img src="https://flagcdn.com/28x21/gb.png" width="28" height="21" alt="United Kingdom" title="United Kingdom">
<img src="https://flagcdn.com/28x21/za.png" width="28" height="21" alt="South Africa" title="South Africa">
<img src="https://flagcdn.com/28x21/cn.png" width="28" height="21" alt="China" title="China">
<img src="https://flagcdn.com/28x21/ar.png" width="28" height="21" alt="India" title="Argentina">
<img src="https://flagcdn.com/28x21/my.png" width="28" height="21" alt="Malaysia" title="Malaysia">
<!--img src="https://flagcdn.com/28x21/ca.png" width="28" height="21" alt="Canada" title="Canada"-->
<!--img src="https://flagcdn.com/28x21/sa.png" width="28" height="21" alt="Saudi Arabia" title="Saudi Arabia"-->
<b>...</b>
</p>


<b> About the App: </b>  
*Din Quick Launch Toolbar* App is designed to manage Shortcuts for Windows 11/10 with auto-hide feature. This App is available on [Microsoft Store](https://apps.microsoft.com/detail/9n7nxtc0kbks). <img width="14" height="13" alt="image" src="https://github.com/user-attachments/assets/e89693ef-b4c4-4c82-b292-09f020deb171" />
Please do not install from any other sources. See following YouTube Video for a quick demonstration of the App.   
For any inquiries on this App, please email me at dinvision.bc@gmail.com <img width="32" height="16" title="Canada" alt="CanadaFlag_32x16" src="https://github.com/user-attachments/assets/bfe4f8f7-8c61-4549-a91c-ed43d1b278ce" />



[![IMAGE ALT TEXT](http://img.youtube.com/vi/548o5cCr1VA/0.jpg)](https://www.youtube.com/watch?v=548o5cCr1VA "Quick Launch Toolbar Demo")

<b>Auto-Hide:  </b>  
To enable Auto-Hide, position the toolbar so that it touches the side or top edge of the screen. The toolbar will then automatically hide when you move the mouse away from it and reappears when you hover the mouse over the thin strip on that edge. 

<b>Add and Group Shortcuts:  </b>  
The shortcuts for the Toolbar are in the "Shortcuts" Folder that can be opened as shown below. Create sub-folders to display shortcuts in separate groups as shown in example below. The 3-digit prefix is for sorting purpose. The toolbar can be resized and moved as per preference.  
  
![image](https://github.com/user-attachments/assets/3e600486-8af4-47ee-9ef5-24b759153d74)

<img width="475" height="311" alt="image" src="https://github.com/user-attachments/assets/414e91a6-5b00-431e-95b3-e71ab90a46d1" /><br>

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

<B>Background Image:  </B>  
To set a background image, enter the image file path in the "BackgroundImagePath" setting of the INI file, as shown in example below. Use small image files (under 100 KB) to prevent slow loading. Close and reopen the app to apply the changes.  

![image](https://github.com/user-attachments/assets/1874df0e-2e52-4b3f-8399-85d81adeea6f)

<b>How to change Toolbar Color:</B>  
To change the color of the Toolbar, change the Color name for the "ToolbarColor" parameter, you can choose color name from the following list  
[Color Names List](https://learn.microsoft.com/en-us/dotnet/media/art-color-table.png?view=windowsdesktop-8.0)  
For example, change the color as below in the "ini" file. (in version 1.0.52.0 and newer)  
ToolbarColor=LightBlue  
ToolbarBorder=Yes  
ToolbarBorderColor=Green  
Save the "ini" file, close and re-open the Toolbar to apply changes.  

![image](https://github.com/user-attachments/assets/d1c69e39-62f4-4635-8d41-3b515a457f8d)

<b>How to customize Icons Display:</B>  
See this YouTube Video [How to customize Icons Display](https://www.youtube.com/watch?v=RTC05oaLqeM) to see demonstration of the configuration such as following. Download the INI files from [INI Files](https://github.com/DinVision/QuickLaunch/tree/Main/INI_Files) Folder  


| Toolbar Display                                                                                             | INI settings                                                                                                                                                                                      |
|---------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|![image](https://github.com/user-attachments/assets/86d62ec4-2b66-40bf-bd5d-ce46446b00ad)  | <sub>ButtonSizeWidth=130<br>ButtonSizeHeight=36<br>IconSizeWidth=24<br>IconSizeHeight=24<br>ButtonBorderSize=1<br>ShowButtonText=Yes<br>ToolbarColor=Pink<br>ButtonTextImageRelation=ImageBeforeText<br>ButtonImageAlign=TopLeft<br>ButtonTextAlign=MiddleLeft<br>ToolbarBorderColor=RosyBrown<br>ButtonBorderColor=RosyBrown<br>SpaceBeforeButtonText=Yes</sub> |

<b>Dark Mode:</B>
Following color combination is also appropriate for Dark Mode preference
| Toolbar Display                                                                                             | INI settings                                                                                                                                                                                      |
|---------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|![image](https://github.com/user-attachments/assets/83a755ba-b222-42b8-83c6-61a45e4b0caa)  | <sub>ButtonSizeWidth=80<br>ButtonSizeHeight=75<br>IconSizeWidth=32<br>IconSizeHeight=32<br>ShowButtonText=Yes<br>ToolbarColor=DarkSlateGray<br>ButtonTextImageRelation=ImageAboveText<br>ButtonImageAlign=TopCenter<br>ButtonTextAlign=MiddleCenter<br>ToolbarBorderColor=DarkGray<br>ButtonTextColor=White<br>FolderTextColor=White</sub> |

<b>Create Icons:  </b>  
Use Create Icon button to select Image files (jpeg, png, bmp, gif) and convert to ICO file that you can use as Icons for your shortcuts. See this short YouTube Video [Create Icons from Image](https://www.youtube.com/watch?v=xGHXstfHCos) to see demonstration of this feature.  
  
![image](https://github.com/user-attachments/assets/e68b01ac-e314-4863-a7d0-6adf73562725)

<B>Run as Administrator:  </B>  
To run any app as an administrator, hold the Shift key on the keyboard while clicking the app icon. 

<b>Group name Font Size and Spacing (version 1.0.64.0+)</b><br>
The font size and spacing for the Folder Group names can be changed as shown below. You can manually add them for older INI Files. <br>

<img width="697" height="281" alt="image" src="https://github.com/user-attachments/assets/a7c795af-f5c2-47f4-9170-2ece09cb1155" /><br>

<b>Always on Top (version 1.0.64.0+)</b><br>
The App will always stay on top of other open Apps, if you wish to disable this behaviour, change "AlwaysOnTop=No" in the INI File. You can manually add that line them for older INI Files. * see "Known Issues" section. <br>

<B>Website Shortcuts:</B>  
To add shortcuts to specific websites, make copy of the shortcut of the Browser such as Edge. Open Properties, add the Website address at the end of the Target value. Change Icon as per your preference.   

![image](https://github.com/user-attachments/assets/716e5954-8b74-4841-b688-321b54042c1a)


<B>Windows Settings Shortcut (ms-settings):</B>  
To add shortcut for Windows Settings:  
Create Shortcut to: "C:\Windows\explorer.exe ms-settings:"  
Then select Icon from "%SystemRoot%\System32\shell32.dll"  
Close and re-open the App, then it will display in the app. See following screenshot.  

![image](https://github.com/user-attachments/assets/13cb0af7-b847-47f0-bf8a-aa8b61653f2a)

<B>Taskbar Display Setting:</B>  
If you prefer to always display the App in the Taskbar, set 'AlwaysShowOnTaskbar' to 'Yes' in the INI file. Restart the App. Then the App will be displayed in the Taskbar. If you set it to "No", then the App will be displayed in the Taskbar only when you minimize it.   <br><br>
![image](https://github.com/user-attachments/assets/32530b33-bbfe-4917-9355-ef02efb3f6e6)

<b>Known Issues:</b><br>
Nov 10th, 2025 - Toolbar not staying on top. There is a known issue where the Din Quick Launch toolbar stops staying on top after opening certain Windows apps such as "Paint" or "Photos". Once one of these apps is opened, all other windows can overlap the toolbar - even apps that normally stay behind it. This behavior started recently and appears to be related to a change in how those Windows apps manage window layering (Z-order).<br><br>
The current workaround is to minimize the overlapping apps and then hover your mouse over the toolbar to bring it back on top. You can also change "AlwaysShowOnTaskBar=Yes" in the ini file if this is a frequent issue for your use. This behavior is under investigation, but it appears to be caused by changes within the Windows apps themselves, making it difficult to fully control from the Quick Launch toolbar side.


<b>Thank You for Your Ratings !🙏:</b><br>
This app currently has a 4.2★ rating in the [US Region](https://apps.microsoft.com/detail/9n7nxtc0kbks?hl=en-US&gl=US). If you are already using this app, please take a moment to rate it. It takes only 10 seconds. Simply click on "Rate" in the App Settings as shown below.   <br><br>
<img src="https://github.com/user-attachments/assets/3c05bea9-c5a1-4ebe-954b-2e0b3e3482a4" alt="App Ratings" width="600"> 

<B> End </B>



