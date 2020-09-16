# Warning
I do *not* take responsibility for what may happen to your system. This is at your own risk.

# Windows10Debloater
Script/Utility/Application to debloat Windows 10


# How to run Windows10Debloater
-	Close all other applications.
-	Run launch.bat as admin.

## Warning
If you do not run this script as administrator, it can cause unnecessary breaks in the system.

# This script will remove the bloatware from Windows 10 when using Remove-AppXPackage/Remove-AppXProvisionedPackage, and then delete specific registry keys that are were not removed beforehand. For best results, this script should be ran before a user profile is configured, otherwise you will likely see that apps that should have been removed will remain, and if they are removed you will find broken tiles on the start menu.

These registry keys are:

EclipseManager,
ActiproSoftwareLLC,
Microsoft.PPIProjection,
Microsoft.XboxGameCallableUI

You can choose to either 'Debloat' or 'Revert'. Depending on your choice, either one will run specific code to either debloat your Windows 10 machine.

The Debloat switch choice runs the following functions:

Debloat,
Remove-Keys,
Protect-Privacy,
Stop-EdgePDF (If chosen)

The Revert switch choice runs the following functions:

Revert-Changes,
Enable-EdgePDF

The Revert option reinstalls the bloatware and changes your registry keys back to default. 

# The scheduled tasks that are disabled are:

XblGameSaveTaskLogon,
XblGameSaveTask,
Consolidator,
UsbCeip,
DmClient

These scheduled tasks that are disabled have absolutely no impact on the function of the OS.

# Bloatware that is removed:

3DBuilder,
ActiproSoftware,
Alarms,
Appconnector,
Asphalt8,
Autodesk SketchBook,
Bing Finance,
Bing Food And Drink,
Bing Health And Fitness,
Bing News,
Bing Sports,
Bing Travel,
Bing Weather,
BioEnrollment,
Camera,
CandyCrush,
CandyCrushSoda,
Caesars Slots Free Casino,
ContactSupport,
CyberLink MediaSuite Essentials,
DrawboardPDF,
Duolingo,
EclipseManager,
Facebook,
FarmVille 2 Country Escape,
Flipboard,
Fresh Paint,
Get started,
iHeartRadio,
King apps,
Maps,
March of Empires,
Messaging,
Microsoft Office Hub,
Microsoft Solitaire Collection,
Microsoft Sticky Notes,
Minecraft,
Netflix,
Network Speed Test,
NYT Crossword,
Office Sway,
OneNote,
OneConnect,
Pandora,
People,
Phone,
Phototastic Collage,
PicsArt-PhotoStudio,
PowerBI,
Royal Revolt 2,
Shazam,
Skype for Desktop,
SoundRecorder,
TuneInRadio,
Twitter,
Windows communications apps,
Windows Feedback,
Windows Feedback Hub,
Windows Reading List,
XboxApp,
Xbox Game CallableUI,
Xbox Identity Provider,
Zune Music,
Zune Video.

# Credits

Thank you to a60wattfish, abulgatz, xsisbest, Damian, Vikingat-RAGE, and Reddit user /u/GavinEke for some of the suggestions and fixes that I have placed into my scripts. You all have done a fantastic job!