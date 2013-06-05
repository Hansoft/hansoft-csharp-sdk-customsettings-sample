hansoft-csharp-sdk-customsettings-sample
====================

About this program
------------------
This sample code demonstrate how to use custom controls in the Hansoft client from the Hansoft .NET/Managed/C# SDK. It is bundled with the Hansoft SDK that can be downloaded from the [Hansoft website](http://www.hansoft.com/support/downloads/). 
To be able to compile this program you need the Hansoft SDK DLLs that are included in that download. A Visual Studio solution is included for 
building on Windows. The file CustomSettings.ir contains definitions of the dialogs that are added to Hansoft.

The program connects to a Hansoft server. To be able to do this you need a Hansoft license with the SDK module. If you need help with this, contact
Hansoft support at <support@hansoft.com>. The program creates a scheduled task in every project and updates the task's date to the current date.

Terms and conditions
--------------------
The program is licensed under the MIT License as stated in [LICENSE.md](LICENSE.md).

Usage
-----
	Start the program from your IDE or in a shell. It will loop until a key is pressed and outputs debug text to stdout. Look for new menu items in the More menu.., in the global admin right hand pane and new tabs in the User config dialogs.
