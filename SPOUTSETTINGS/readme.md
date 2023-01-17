SPOUTSETTINGS

SpoutSettings is a utility program to change the operation mode for Spout applications.

When first run, if a Spout installation is detected you should select the option to remove it.
If then you do not receive a message that the un-installation has been successful,
close the program and use Windows Control Panel to un-install Spout.

Options

o Buffer

Use OpenGL pixel buffers to speed up data transfer between system memory. This is used for pixel images and CPU backup mode. Buffering is faster but might result in latency. Test for your application. 

o Number of buffers

Number of buffers allocated from 2 to 4. More buffers can improve performance but sufficient memory must be available. Reduce the number or disable buffering for any problems.

o Auto share

Detect graphics compatibility and use either CPU or GPU for texture sharing. Leave this option checked on normally. But if you suspect that CPU sharing is occurring, check it off to find out. In that case, sharing will simply fail and the application will not send or receive. Then you should investigate graphics compatibility to achieve optimum performance.

o Maximum Senders

Sets the maximum number of senders that can operate at the same time. The minimum number is 10 and default is 64. 
Memory allocated is 256 * number of senders in bytes. If setting to more than the default, keep to the minimum you require.
Applies for Spout applications built with the 2.005 SDK or later. Earlier applications are be limited to 10 senders.
Spout applications must be re-started after change

o NVIDIA global processor

For laptop computers with dual graphics and NVIDIA Optimus power saving technology. 
The mode of operation can be changed to enable the high performance NVIDIA graphics globally for all applications.
This over-rides the NVIDIA control panel settings and can be useful where there is difficulty in adjusting them.
This will not have any effect if the computer does not have Optimus graphics or is not NVIDIA.

o Windows graphics settings

Windows graphics performance settings for applicationb are available from Windows 10 version 1803 (build 17134) and apply for Laptops with multiple grahhics that allow the options of power saving or performance. "High Performance" is recommended for Spout applications.

o Help

Use the help button for each item for more information.

o Diagnostics

Shows details of the graphics system and compatibility for OpenGL/DirectX texture sharing.

o Registry

All selected options are saved in the registry under "Computer\HKEY_CURRENT_USER\Software\Leading Edge\Spout".

