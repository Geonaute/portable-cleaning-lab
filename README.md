Portable Cleaning Lab (PCL) Scripting and Utilities For A Completely Portable Malware Removal Experience




Version History (Windows)
--------------------------

v0.9.4

-GLOBAL: Updated definitions for all compatible portable malware scanners

-GLOBAL: Added "HDDScan 3.3" and "RAMMap 1.50" to diagnostics modules and added to EXPERT scripting menu



v0.9.3

-GLOBAL: Updated definitions for all compatible portable malware scanners

-GLOBAL: Updated module framework template to v3.2. Added support for new Windows 10 version numbers

-GLOBAL: Updated core files in "RMPrepUSB" module to 2.1.730A. Also updated Easy2Boot core files to 1.76, located under %RMPrepRoot%\E2B

-GLOBAL: Added "x64dbg" module to Forensics menu under Tools. Both x86 and x64 versions are included, and the scripting will choose the correct one upon launch

-GLOBAL: Updated "Process Hacker" core files to v2.37.214 under Diagnostics Menu

-CLI: Added "snowman.ini" to cleanup script. This file is created by x64dbg in the PCL root, and is automatically cleaned during startup and exit

-CLI: Antivir and Vipre update modules have been flagged as no longer working due to recently discovered server side changes. These and other scripts will be fixed soon



v0.9.2

-GLOBAL: Updated definitions for all compatible portable malware scanners

-GLOBAL: Updated "Teamviewer" module to v11.0.51091 Beta. Fixed issue with EXE not terminating after pressing "X" Close button

-GLOBAL: Fixed another Teamviewer startup nag from appearing

-GLOBAL: Added "360 Total Security" to Malware Scanners menu. It currently is marked as not working properly

-CLI: Added "Spybot: Anti-Beacon" to Maintenance, under Expert menu, for disabling telemetry data

-CLI: Removed "Microsoft Fixit" from Utilities menu under Expert, until stable

-CLI: Added "GWX Control Panel" to Utilities under Expert for controlling Win10 nags on Win7/8/8.1 machines

-CLI: Added a "Disable GWX" script under Manual Malware Removal for further supressing Win10 nags on Win7/8/8.1 machines



v0.9.1

-GLOBAL: Updated definitions for all compatible portable malware scanners

-GLOBAL: Added "NTPWEdit" and "Password Renew" to Recovery, under Expert menu

-CLI: Added "PowerGREP", "Q-Dir" and "Super Finder" to Utilities, under Expert menu

-CLI: Moved "Fake Flash Test" from Utilities to Diagnostics, under Expert menu

-CLI: Moved "Fiddler", "Filezilla", "Teamviewer", and "Wireshark" from Utilities to Networking, under Expert menu

-CLI: Fixed repack and copy settings in update script for "Malware Destroyer" cleaning module

-CLI: Updated "Teamviewer" module to v11.0.50714 Beta. No longer using PortableApps version. Now using original version with scripting to control nags

-CLI: Added "modulepath" to hidden keywords. This is currently in testing 



v0.9.0

-Now in RC4 development stage

-GLOBAL: Updated definitions for all compatible portable malware scanners

-GLOBAL: Updated module framework template to v3.0 BETA. All modules will be migrated to the new v3.0 platform as updates roll out

-GLOBAL: Updated "config/pcl.ini" to support module path override. This can be used to change the working path for modules in PE Mode and other situations

-GLOBAL: Updated core scripts to support new module settings



v0.8.9

-GLOBAL: Updated definitions for all compatible portable malware scanners

-GLOBAL: Updated module framework template to v2.9. Added support for multiple services to be enabled during malware scan, if needed

-GLOBAL: Updated PE Mode detection

-GLOBAL: Updated "Teamviewer" module to v10.0.47484P

-CLI: Added "WIM Converter" module to Utilities, under Expert Menu

-GLOBAL: Updated main script compatibility for new PCL: PE Edition ISO, currently in testing

-Added the following baddies to "rmListPF.txt" file:
   -BBItSaveoro
   -BitaSaVer
   -BitSauver
   -Fancy Response
   -Keep Awake
   -LighterModulator
   -NewTab Connect Homepage
   -Ponyhoof
   -RiightOfFerApp
   -SalePlus
   -SalePlusu
   -Steam Trader Helper
   -TAkeTheCoUUpoon
   -TAkeThheoCoupon
   -TakoeTheCouuPon



v0.8.8

-GLOBAL: Updated definitions for all compatible portable malware scanners

-GLOBAL: Updated module framework template to v2.8. Added support for apps that use split x86 and x64 versions. Added ability to select x86 version if x64 and both exist. Other small fixes

-GLOBAL: Added "CryptoPrevent" and "Windows Worm Doors Cleaner (WWDC)" to Maintenance modules. These are selectable through Expert menu

-GLOBAL: Added "Process Hacker" to Diagnostic modules, also selectable through Expert menu

-GLOBAL: Fixed "Dr Web CureIt" module under Expert Menu Scanners. Now using the GUI instead of CLI due to licensing issues

-GLOBAL: Updated "Malwarebytes Antimalware" core files to v2.1.8.1057

-GLOBAL: Updated "Comodo Cleaning Essentials" core files to v2.4.225190.192

-GLOBAL: Fixed the 64bit version of SuperAntiSpyware module for both launch and update scripts

-GLOBAL: Updated "Process Explorer" core files in diagnostics module to v16.05

-GLOBAL: Updated "Process Monitor" core files in diagnostics module to v3.20 

-GLOBAL: Updated "Speccy" core files in diagnostics module to v1.28.709

-GLOBAL: Updated "System Explorer" core files in diagnostics module to v7.0.0.5356. Fixed startup nag from popping up also

-GLOBAL: Updated "Unknown Device Identifier" core files in diagnostics module to v9.0

-GLOBAL: Updated "CCleaner" core files in maintenance module to v5.10.5373

-GLOBAL: Updated "Recuva" core files in recovery module to v1.52.1086

-CLI: Added "Defraggler" to maintenance modules and Expert Menu

-CLI: Added "MiniTool Partition Wizard Free 9.1" module to Utilities under Expert Menu

-CLI: Added "Driver Signature Enforcement Overrider" to Utilities under Expert Menu



v0.8.7

-GLOBAL: Updated definitions for all compatible portable malware scanners

-GLOBAL: Fixed crashing on corrupt remote config parsing. Added a routine that verifies the "pcl.ini" config file and skips check if corrupt

-GLOBAL: Changed behavior of Update Status ONLY if version matches. Now the MsgBox appears ONLY when invoking from Expert menu, not on launch

-GLOBAL: SuperAntiSpyware module will give a 32-bit error if on 64-bit system. Just click OK for now, it will work fine. This will be fixed in a future update

-GLOBAL: Updated "Trend Micro" module to use an external text file (defnum.txt) to hold current update number to download

-GLOBAL: Fixed 32-bit error while running 64-bit with "Comodo Cleaning Essentials" module. It now downloads both 32 and 64 bit versions and uses the appropriate one for scanning

-CLI: Fixed an issue with "Copy Dumps Back to Source Media" option for folders with spaces under Forensics Main menu

-Added the following baddies to "rmListPF.txt" file:
   -7777aa49-c6b1-48e5-975b-fdbd9f9b4ac9
   -02989483-f434-410e-8075-09639f688b4d
   -BetTTerPariceeCheoc
   -Citable
   -ClickMovie1-Downloaderv10
   -deal2deAliTT
   -disco games
   -Favicon Changer
   -new game
   -Pay-By-Ads
   -PeRinceCoupoN
   -PrinceCoupOn
   -PrinCeCouupon
   -SAAlesChaeckeR
   -SalesChEckeer
   -SAlesChecker
   -savErabox
   -saveroNaett
   -The Key for YouTube
   -TheVEEHD Plugin V10

-Added the following baddies to "rmListADLL.txt" file:
   -ClickMovie1-Downloaderv10



v0.8.6

-Now in RC0 development stage

-GLOBAL: Updated definitions for all compatible portable malware scanners

-GLOBAL: Updated CCleaner to v5.05.5176. Both x86 and x64 versions were updated in PCL module

-GLOBAL: Updated module template to v2.7. Added a "defCheckFileTemp" for updating definitions. Added a routine to download directly to a custom destination. Fixed a few typos and cleaned up some code

-GLOBAL: Changed Avast module update script to now be automatic, without having to load the Avast awMBR GUI. The VPS definition file is now directly downloaded with wget to the same destination as the GUI would normally use

-GLOBAL: Updated Avast core scanner to v1.0.1.2290 in main module

-GLOBAL: Added "updateMode" to the [updates] section of "/data/config/pcl.ini" file. This will allow the PCL to use different modes for individualized updating (full, modules, scripts, tools, etc)

-GLOBAL: Updated "System Explorer" module to v6.4.2.5342. Tweaked some settings to load more quickly without displaying initial nag screens

-GLOBAL: Updated "Malwarebytes Antimalware" core files to v2.1.6.1022 in main module

-GLOBAL: Updated "SuperAntiSpyware" core files to v6.0.1194 in main module. The main EXE is no longer patched to hide nag window due to false positives from AV scanners (oh the irony!). If an update nag appears while scanning, simply ignore and close as normal when finished. If you select update from the nag, it will just give an error

-CLI: Enabled "Automatic Update Checking" when launching the PCL. It can be changed in the "/data/config/pcl.ini" file. This was solely done because I am assuming most people that use this tool do not see the update option! Maybe I am wrong?

-CLI: Changed the behavior of "Automatic Update Checking" option on launch to skip interaction if user version matches server version

-CLI: Changed the default output for update status check from displaying inside terminal window to a msgbox instead

-Added the following baddies to "rmList.txt" file:
   -CinemaPlus-3.2cV16.05
   -Crossbrowse
   -Driver Tool
   -Ebon
   -Ebon Maintenance Service
   -Edu App
   -FlashBeat
   -gmsd_us_581
   -gmsd_us_585
   -Goobzo
   -GUPlayer
   -Infonaut_1.10.0.13
   -LolyKey
   -MixVideoPlayer
   -mystarttb
   -nlikcompbpfinbbonponkbjdbineclph
   -Optimizer Pro 3.91
   -ORBTR
   -SafeGuard
   -SysFilesx
   -WGANomTYuuq

-Added the following baddies to "rmPUP.txt" file:
   -YTDownloader

-Added the following baddies to "rmListPF.txt" file:
   -app_setup
   -BubbleSound
   -CompuClever
   -Coupoon
   -Crossbrowse
   -DriverRestore
   -Edu App
   -Fragile Fixer
   -Infonaut_1.10.0.14
   -ospd_us_1071
   -PC Privacy Dock
   -PCP
   -Portable WeatherApp
   -Priceless
   -Pro PC Cleaner
   -Service Mgr PositiveFinds
   -Sn2zknte1ndjhzgj
   -Tuneup computer
   -Unzbkyzfhndrhnwj
   -WajaIEnhancer
   -WindeskWinsearch

-Added the following baddies to "uninstallPF.txt" file:
   -BubbleSound
   -CompuClever
   -Coupoon
   -DriverRestore
   -Fragile Fixer
   -user extensions
   -Itibiti Soft Phone
   -PCP
   -PC Clean Maestro
   -PC TuneUp Maestro
   -ospd_us_1071 (OneSoftPerDay)
   -Super Optimizer
   -WebBar

-Added the following baddies to "svcList.txt" file:
   -1DEA2C4A-8529-46b5-ACC0-C3873ED068E6
   -22134214
   -CoupoonService
   -csrcc
   -eLdxGPJOXCS
   -Orbiter
   -SafeGuard Update Service
   -SGUpdater (SafeGuard)
   -shopperz Updater
   -SMUpdPlus (Search Module Plus Update)
   -Update Edu App
   -Update Fragile Fixer
   -UpdateCheck
   -Update Mgr PositiveFinds
   -Util Edu App
   -WajaIEnhancer Service
   -wbsvc
   -WeWatcherProxy

-Added the following baddies to "svcListPUP.txt" file:
   -APNMCP (Ask Update Service)
   -vToolbarUpdater18.3.0

-Added the following baddies to "processList.txt" file:
   -apnmcp.exe
   -EduApp.PurBrowse64.exe
   -HealthcareHelp.exe (SysFiles)
   -insvc.exe
   -MixVideoPlayerUpdaterService.exe
   -netengine.exe
   -SafeGuard.exe
   -SafeGuardApp.exe
   -SafeGuardSrv.exe
   -ShopAtHome_BAC_Service.exe
   -smu.exe (Goobzo)
   -updateEduApp.exe
   -upgmsd_us_581.exe
   -utilEduApp.exe
   -WeWatcherProxy.exe (SysFiles)
   -WeWatcherLSP64.exe (SysFiles)
   -WeWatcherLSP64.exe (SysFiles)



v0.8.5

-GLOBAL: Updated definitions for all compatible portable malware scanners

-GLOBAL: Updated Vipre update script to v2.3. This fixes an issue with downloading the new EXE from VIPRE's server, as they changed the static link redirection

-GLOBAL: Fixed issue with Spybot giving a log error when updating

-GLOBAL: Added default boot /3GB scripts and INI files for XP, Vista, 7, 8+. This is for enabling 4GB+ memory on 32 bit versions. The files are located under %pclRoot%/data/scripts/misc/

-GLOBAL: Updated Trend Micro update starting number to 661, which is currently the newest trigger for definitions update link. This number will auto increment to the newest automatically when running update script

-GUI: The current GUI (Graphic User Interface) is still in early ALPHA stage and will be on hold until more time can be devoted to it. The project is currently written in C#, but I will probably re-write from scratch or re-code in C++

-CLI: The current CLI (Command Line Interface) is very stable and this will be the last BETA release. Most to all major bugs should be non-existent, excluding specific issues for individual cleaning modules that may break and require updates from time to time. Further development will continue as a Release Candidate (RC0)

-CLI: Changed the layout and some of the colors on main UI selection menu

-CLI: Added an "[X] Exit" command on main UI selection menu, in the lower right-hand corner of the terminal window

-CLI: Added "Networking Tools and Scripts" to Main Expert UI Menu

-CLI: Changed default menu option for "Clean Current Temp Folders" from "9" to "T" as the menu item key

-CLI: Added "network" to main scripts path

-CLI: Updated "set-global" core script with new path variables for network scripts

-CLI: Added "Disable and Enable Default Wireless Connection" and "Show Default Wireless Connection Info" to main network script

-CLI: Added msgbox for trying to access any module that is currently experiencing issues

-MODULE: Dr Web and Kaspersky modules do not fetch the current definition update. This will be fixed in a future update

-MODULE: Norman Malware Cleaner update link is no longer valid and the software may have been discontinued in favor of Suite tools

-Added the following baddies to "processLists.txt" file:
   -nseven.exe
   -sprz.exe

-Added the following baddies to "rmList.txt" file:
   -CoupScannero
   -download Manager
   -FianeDealSooft
   -FlexibleShhopppeer
   -Priceless
   -PuriceLesse
   -Shopperz
   -SOftCouap
   -topbuayer



v0.8.4

-GLOBAL: Updated definitions for all compatible portable malware scanners

-GLOBAL: Updated starting number to 573, which is currently the newest definitions update, for triggering update link in Trend Micro module

-GLOBAL: Changed wget user agent to use Firefox/Linux as default for scanners that have direct downloads. This is solely for bypassing T-Mobile tethering limits while testing, which I currently have ;)

-GLOBAL: Added "rmFile.txt", "rmFileOEM.txt", and "rmFilePUP.txt" to "scripts/lists" directory for baddie removal of individual files

-CLI: Added a network check before executing "PCL Update" option from Main Expert Menu

-Added the following baddies to "svcList.txt" file:
   -Freemake Improver

-Added the following baddies to "rmListPD.txt" file:
   -E1864A66-75E3-486a-BD95-D1B7D99A84A7 (CryptoWall 3.0)

-Added the following baddies to "rmListPF.txt" file:
   -DOwNSAeve
   -Freemake
   -PC Tools
   -Red AdBlocker
   -ReguulArDDealsi
   -SpeedyPC Pro
   -SpeedyPC Software
   -The AdBlocker

-Added the following baddies to "rmListADL.txt" file:
   -APworks
   -Ention
   -FreemakeVideoConverter
   -Threat Expert

-Added the following baddies to "rmListADLL.txt" file:
   -FreemakeVideoConverter

-Added the following baddies to "rmListDocuments.txt" file:
   -Freemake

-Added the following baddies to "processLists.txt" file:
   -AdapterTroubleshooter.exe

-Added the following baddies to "rmFile.txt" file:
   -HELP_DECRYPT.HTML (CryptoWall 3.0)
   -HELP_DECRYPT.URL (CryptoWall 3.0)
   -HELP_DECRYPT.PNG (CryptoWall 3.0)
   -HELP_DECRYPT.TXT (CryptoWall 3.0)




v0.8.3

-GLOBAL: Updated definitions for all compatible portable malware scanners

-GLOBAL: Updated Module Framework template to v2.6. Adds support for finding locally installed scanners and apps. Also includes other features

-GLOBAL: Added "Lenovo Superfish Removal Tool" to other cleaning modules

-GLOBAL: Updated "Norton Removal Tool" to v22.0.0.20 under AV removal

-GLOBAL: Fixed "Comodo Cleaning Essentials" scripting to hide the EULA on launch. It's a reg entry... sorry Comodo ;)

-CLI: Disabled "Dr Web CureIt" until issues are resolved

-CLI: Added "View Windows Event Logs" to Manual Malware Removal -> Other Scripts Menu

-CLI: Fixed Rootkit/Other Scanners menu items not launching

-CLI: Fixed typo in Maintenance title

-CLI: Added "Lenovo Superfish Removal Tool" to Rootkit/Other Scanners menu

-Added the following baddies to "rmListADR.txt" file:
   -AnyProtectEx
   -Fingertapps
   -freegames4357
   -GoldenGate
   -PCDr
   -ShopAtHome
   -SoftwareUpdater
   -Taplika
   -USTechSupport

-Added the following baddies to "rmListADL.txt" file:
   -avaxvavya
   -BrowserHelper
   -Chromatic Browser
   -CleanerPro
   -com/NewPlayer.*
   -Deal Vault
   -DesktopTemperature
   -Gameo
   -Geckofx
   -gmsd_us_74
   -Installer
   -PC_Drivers_Headquarters
   -SoftThinks
   -Taplika
   -TBHostSupport
   -TelevisionFanatic
   -Vosteran
   -ZombieNews

-Added the following baddies to "rmListADLL.txt" file:
   -{D2020D47-707D-4E26-B4D9-739C4F4C2E9A}
   -BringMeSports_1c
   -Company
   -InternetHelper3
   -ShopAtHome
   -WebEx

-Added the following baddies to "rmListPD.txt" file:
   -Allmyapps
   -Extreme Blocker
   -gCXhpgaR
   -makulitsidwe
   -NoMore Ads
   -UltraCoupon
   -Unchecky
   -WaowCeoupoon
   -ZombieNews

-Added the following baddies to "rmListPF.txt" file:
   -08F60977-C840-42C6-A2D3-06E8FE3787F5
   -1 Media Player
   -8306ec99-c559-4a07-ba87-bff22a98676d
   -BringMeSports_1c
   -BuzzSocialPointsIE_DNS
   -BuzzSocialPoints_DNS
   -BuzzSocialPoints_DNS_IE
   -Claro LTD
   -CouPSccaNner
   -Cyti Web
   -Deal Vault
   -DigiCoupoNa
   -DiigISaver
   -DisCeOUntExteeNsi
   -doctorpclab.com
   -DomaIQ Uninstaller
   -ffff4938-29f5-4731-a383-f5e92891d5fe
   -Finance41 Extension
   -Fliptoast
   -Free Slots
   -FunDEAls
   -Ge-Force
   -GUM8FB4.tmp
   -hdvidcodec.com
   -leess2pay
   -mediainformationaccess
   -PopularScreensavers
   -RoboSavver
   -SaaveReProo
   -saffeReweebb
   -sarconsogulpe
   -SaveLottS
   -shhopndRop
   -StormWatch
   -SweetPacks
   -System Registration
   -Tabman Tabs Manager
   -TampaGeneration
   -TelevisionFanatic
   -Tuguu SL
   -Unfriend Checker
   -uniisalees
   -uniSalies
   -uTorrentControl_v6
   -WaowCeoupoon

-Added the following baddies to "rmListDocuments.txt" file:
   -My Smilebox Creations
   -ProPCCleaner

-Added the following baddies to "uninstallPF.txt" file:
   -Cyti Web

-Added the following baddies to "uninstallPUP.txt" file:
   -Liveistream

-Added the following baddies to "processList.txt" file:
   -CouPSccaNner.exe
   -p5MedInt.exe
   -p5PSSavr.scr
   -p5svc.exe
   -SaaveReProo.exe
   -shhopndRop.exe
   -sarconsogulpe.exe
   -Tabman Tabs Manager.exe
   -uniSalies.exe

-Added the following baddies to "svcList.txt" file:
   -dd693f9b (TampaGeneration)
   -BringMeSports_1cService
   -BrsHelper
   -TelevisionFanaticService



v0.8.2

-GLOBAL: Updated definitions for all compatible portable malware scanners

-GLOBAL: Updated Module Framework template to v2.5. Adds support for "root.blob", "Windows Compatibility Mode", and more

-GLOBAL: Added "rmRoot.txt" and "rmRootFile.txt" to scripts to be used in baddie loops for removing baddies from root (C:\) drive

-GLOBAL: Fixed "Panda Antivirus" scanner for launch and auto mode scripts in module

-GLOBAL: Updated CCleaner to v5.1.0.5075. Both x86 and x64 versions were updated in PCL module

-GLOBAL: Fixed update URL issue with VBA32 module. Now using RAR version because of 0-byte issues with ZIP version on server

-GLOBAL: Added "ESET NOD32 Antivirus" to cleaning modules

-GLOBAL: Fixed "hopefully" the update repack issue with Comodo module

-GLOBAL: Updated "Malwarebytes" core files to 2.04.1028 in module. Archived version 1.x in "malwarebytes-classic" module

-GUI: Updated Expert Scanners tab. Launch and Update buttons now work for all scanners

-GUI: Added "Clean Cookies" to Auto Mode misc option checkboxes

-GUI: Enabled "Panda Antivirus" under scanner options in Auto Mode

-GUI: Added "ESET NOD32 Antivirus" to Auto Mode and silent scanners default

-CLI: Added "Clean Cookies" and set default response to YES for "Clean Temp Files" menu item

-CLI: Fixed issue on Manual Malware menu if accidentally selecting 0 or any number less than 1 from loading next menu

-CLI: Added "ESET NOD32 Antivirus" to Auto Mode and Manual Malware Removal menu

-Added the following baddies to "rmListADLL.txt" file:
   -{044A102D-C0F1-CBC5-54A0-5DC4BADB35FB} ProiShopPer
   -{F59B3A26-DD10-BEFB-8235-76F77F13BD9D} LuckYCoupoN
   -{F9146CD7-4350-6BF8-71E4-417EB4582BED} DeaL4me
   -Protect

-Added the following baddies to "rmListPD.txt" file:
   -DiscOunTLLoccatoor
   -fdbimgihibdbpcglmdlegilhmdcimbck
   -leess2pAye
   -LuckYCoupoN
   -ProiShopPer
   -realdeal
   -savEitkkeep
   -savinshop
   -teopdeal
   -topbuyer
   -WinSpeed

-Added the following baddies to "rmListPF.txt" file:
   -ProiShopPer

-Added the following baddies to "svcList.txt" file:
   -2f086fd2 (ProcessMaker)
   -globalUpdate
   -globalUpdatem



v0.8.1

-GLOBAL: Updated definitions for all compatible portable malware scanners

-GLOBAL: Updated Module Framework template to v2.4. This update adds a more refined method for detecting when a scanner has finished updating itself, and a few other tweaks

-GLOBAL: Added "F-PROT Antivirus" and "Zillya Antivirus" to modules, using 2.4 framework

-GLOBAL: Updated registry settings for "Dr Web CureIt" module

-GLOBAL: Added support for "users.blob" to module framework. This is for any folders or files that need to be in the Users root path while scanner is actively running

-GLOBAL: Updated module scripting for "Comodo Cleaning Essentials" to use the newer v2.4 framework

-GLOBAL: Fixed (temporarily) the ampersand issue with Spybot module when repacking

-GUI: Added "F-PROT Antivirus" and "Zillya Antivirus" to scanner options in Auto Mode

-GUI: Cleaned up some text on multiple messagebox items

-CLI: Removed "Update Mode" from Manual Malware Removal menu until Multi-Update is functional

-CLI: Added "F-PROT Antivirus" and "Zillya Antivirus" to Manual Malware Removal menu and Auto Mode



v0.8.0

-GLOBAL: Updated definitions for all compatible portable malware scanners

-GLOBAL: Updated Module Framework template to v2.3. This update cleans up some code and adds several features

-GLOBAL: Added "Dr. Web CureIt" to modules using 2.3 framework. Using CLI version for now, if issues arise from demo key then the gui version will be used in a future release

-GLOBAL: Updated HTML Parsing to handle default scanner and definition files in v2.x Module Framework template

-GLOBAL: Updated "Avira Antivir", "McAfee Virus Scan" and "Vipre Rescue Scanner" modules to v2.x Module Framework

-GLOBAL: Updated "Teamviewer" module to v10.0.36897

-GLOBAL: Added "Comodo Cleaning Essentials" to v2.3 Module Framework

-GLOBAL: Updated FileZilla core to 3.10.0.1 in utility modules

-GLOBAL: Added "Wireshark" to utility modules

-GLOBAL: Updated "Comodo" update script to wait longer while updates are finalizing through GUI before termination and repack

-GLOBAL: Updated "Kaspersky Virus Scanner" module update script. It can now download the full setup, extract files, pull RAR password from EXE, then extract and repack module with updated files

-GUI: Added "Dr. Web CureIt" to scanner options in Auto Mode

-GUI: Enabled "Antivir Scanner" under scanner options in Auto Mode

-GUI: Fixed and Enabled the "Baddie Directory Removal Loop" in Auto Mode

-GUI: Fixed the "Browser Kill Loop" not running when checked in Auto Mode

-GUI: Removed "Avast" from Auto Mode default silent options

-GUI: Added "Clean Temp Files" to Auto Mode Misc Options

-GUI: Added "Comodo", "Kaspersky" and "Vipre" to silent checkbox options as default

-GUI: Cleaned up some resources and brought the total size of EXE down quite a bit

-CLI: Added "Dr. Web CureIt" to Manual Malware Removal menu

-CLI: Fixed a size issue on launch if the window is actively being dragged while opening

-Added the following baddies to "rmList.txt" file:
   -grillaprice
   -PlayPickle

-Added the following baddies to "processList.txt" file:
   -AM_Delta.exe
   -grillaprice.exe
   -playpickle.exe

-Added the following baddies to "svcList.txt" file:
   -csrcc



v0.7.9

-GLOBAL: Updated definitions for all compatible portable malware scanners

-GLOBAL: Added support for "Program Files" and "Common Files" blobs, "pf.blob" and "cf.blob" respectively to module template scripting

-GLOBAL: Updated Module Framework to v2.2. This fixes a "missing directory" issue where if a folder that is expected for repack is missing (ie. %LocalAppData%\Norman Malware Cleaner\) the blob would be packed with all files from %cd% (ie. *\pcl-win\)

-GLOBAL: Fixed a line that was supposed to be commented in update.cmd scripts for all 2.x modules. This seemed to cause no issues, but is now commented to be safe

-GLOBAL: Fixed "Norman Malware Cleaner" module, suffering from "missing directory" issue on repack

-GLOBAL: Updated all rar.exe versions in modules to RAR 5.1

-GLOBAL: Fixed update script in Avast scanning module. This fixes an issue where the repack would start before new updates were complete

-GUI: Updated checkbox options to only load "silent Only" scanners as default for Auto Clean button on launch

-GUI: Added "Select All", "Select None", and "Select Silent" to scanners and loops checkbox lists

-GUI: Added vertical scrollbar to Auto scanning options

-GUI: Added "Kaspersky Virus Scanner", "Trand Micro SysClean" and "VBA32 Antivirus" to Auto scanner options

-CLI: Removed "AVG Antivirus" and MS Security Essentials" from Malware Scanners menu until working properly

-CLI: Added "Trend Micro SysClean" and "VBA32 Antivirus" to Manual Malware Scanners Menu and Auto Mode

-CLI: Added "Kaspersky Virus Scanner" to Malware Scanners Menu

-Added the following baddies to "rmList.txt" file:
   -3c049c0d-a23f-45d1-a58d-d5ab53ae4352
   -6b67962d-1524-4564-98ac-387f94912ac4
   -bbqleads
   -BrowseForTheCause
   -Browsers+Apps+1.1
   -Bull Softwares
   -Cinema Video Pro 1.6V10.11
   -CloudGuard
   -Desktop Dock
   -LyricsParty-soft
   -OverTheEdge
   -Reg Pro Cleaner
   -Smart-ActiveX
   -The-Go-Photo-it-v11
   -ver1LyricsParty

-Added the following baddies to "rmListADLL.txt" file:
   -Dioptair
   -PennyBee
   -serv

-Added the following baddies to "rmListADL.txt" file:
   -Astromenda
   -StormWatch
   -Weather_Protector_LLC

-Added the following baddies to "uninstallPF.txt" file:
   -Desktop Dock

-Added the following baddies to "svcList.txt" file:
   -70F4EEDB-1367-4b4f-8247-3133551A741
   -gupdate
   -shopperz Updater



v0.7.8

-*** QUICKFIX RELEASE ***

-GLOBAL: The "OllyDBG' forensics module has been updated to a barebones clean version after receiving false positives from some antivirus. OllyDBG is a Windows debugging tool, therefore some of its plugins can be considered malicious if in the wrong hands. The new module has been uploaded to VirusTotal and the scan is now clean. Just to be clear, the OllyDBG app is not malicious in itself and is an indispensable tool in malware research ;)

-GLOBAL: Updated definitions for all compatible portable malware scanners

-GLOBAL: Updated Panda Antivirus module to use new v2.1 Framework

-GUI: Added 2 new slide out options in Auto Mode for selecting which scanners and loop scripts to run before clicking the big launch button

-GUI: Added themes and color options to main toolbar for a small amount of customizing the overall look



v0.7.7

-Added the initial version of the GUI. This can be launched by running "portable-cleaning-lab.exe" in main folder. You can still launch the command line (CLI) version by using the .cmd file, and launch the CLI with the GUI as well

-Auto Mode now working in GUI, most other parts are still under development and may not work properly, or at all

-Updated module framework to v2.1. Now globally recognizes all common setup extracted paths. Also extracts INNO, MSI, NSIS, RAR, and ZIP files, and supports standalone and PCL modes

-Updated Avast, BitDefender, ClamWin, Emsisoft, Malwarebytes, Malware Destroyer, McAfee Stinger, Norman Malware Cleaner, RemoveIt Pro, Sophos, Spybot, and SuperAntiSpyware modules to use new v2.1 Framework

-Added many tweaks and updates to the auto, launch, and update scripts for v2.1 module template

-Updated definitions for all compatible portable malware scanners

-Added "net stop" commands to services kill loop. This helps in terminating stubborn baddie services before removing

-Fixed a typo on Main Expert Menu for the Maintenance text

-Updated all "loop scripts" to check for "initGUI" and global variable references, and if not found, common variables are set inside each script

-Added support for "misc.blob" for v2.x modules. This is used for any files needed to be extracted while running, that don't fit into any other category

-Fixed Clamwin module not launching and updating without manually loading script

-Updated rar.exe binary to v5.0.1 in main bin folder and in all modules

-Fixed Spybot not getting the last definition update status when launched

-Fixed an issue globally in the v2.x Module Framework, with processes not being killed before and after scanning

-Fixed services and tasks Auto Mode loops not exiting when finished

-Added "gui" to hidden keywords on Expert Menu on CLI. This will launch the GUI from the Command Line version

-Fixed an issue in PCL scripting with "Run As Administrator" right-click option not working for Windows 8 and higher

-Fixed "Panda Antivirus" module from double launching when running update script

-Removed 64 bit support from SuperAntiSpyware until definitions update issue can be resolved. All windows versions will default to using the 32 bit scanner
   
-Added the following baddies to "svcList.txt" file:
   -CltMngSvc (searchProtect)
   -SftService
   -SupraSavingsService64
   -Util snipsmart
   
-Added the following baddies to "processList.txt" file:
   -sopkjrkm
   
-Added the following good guys to "whitelistADLL.txt" file:
   -EmieBrowserModeList


v0.7.6

-Updated definitions for all compatible portable malware scanners

-Added initial support to a few selected scripts for interacting with the new GUI, still under development

-Updated v2.0 module framework code to run modules in "Standalone Mode" when invoked by the PCL GUI, and when manually extracted and scripts ran individually

-Updated the "set-global" script to dump its environment, if needed for GUI or other tasks

-Added one time loops for "Baddie Services Removal" and "Baddie Tasks Removal" to Auto Mode

-Updated taskkill routine to use text files with exe names to terminate, for v2.0 module scripting

-Fixed Malwarebytes module scripting issue with not extracting the "AllUsers" blob properly

-Added "OllyDBG", "XVI32" and "EXEInfoPE" to Forensics Mode modules and added to Forensics Tools Menu

-Moved "YARA Malware Analyzer" to Forensics Tools Menu

-Re-organized Manual Malware Menu items

-Updated "SuperAntiSpyware" module to use x86 mode until x64 definition update issues are resolved

-Added "Baddie Services Removal" and "Baddie Tasks Removal" options to Expert Manual Malware Menu

-Changed the services text export to show "sc query" results instead of "net start", for more detailed results

-Removed "Dump Malware Items In Registry" and "Get Handles" from Expert Menu. These options are available in Forensics Mode
   
-Added the following baddies to "svcList.txt" file:
   -GorillaPrice
   -IePlugin Services
   -pcCMService
   -pcServiceHost

-Added the following baddies to "rmListPD.txt" file:
   -7save
   -AllSaver
   -b3e7ffbdb916a8dd
   -BitSaver
   -Block The Ads
   -bogdfacjbpjmoheodkbknmihbdmcpgkf
   -boost_interprocess
   -ekiekdklpnjnoinmlepahnkdbhcffaaf
   -ExstraCoupon
   -FindBestDeal
   -Fun2Save
   -IePluginServices
   -shoppii
   -SmartOnes
   -Tarma Installer
   -Wincert
   -Yellow AdBlocker

-Added the following baddies to "rmListADR.txt" file:
   -DriverCure
   -IminentToolbar
   -Leader Technologies
   -OpenSoftwareUpdater
   -ShopAtHome
   -Systweak
   
-Added the following baddies to "rmListADL.txt" file:
   -ArcadeYum
   -encyclopediabritannicagamesbar
   -freegames197
   -iplay_en
   -SpeedAnalysis
   -speedtest127
   -speedtest199
   
-Added the following baddies to "rmListADLL.txt" file:
   -alot
   -ConduitEngine
   -Productivity_2.2
   -Radio_TV_1.1
   -RecipeHub_2j
   -RecipeHub_2jEI
   -Toolbar4
   
-Added the following baddies to "rmPUP.txt" file:
   -AskToolbar
   
-Added the following good guys to "whitelistADL.txt" file:
   -EmieSiteList
   -EmieUserList



v0.7.5

-Updated definitions for all compatible portable malware scanners

-Added support for "Easy Mode". This should be able to accommodate the average user that wants a little more control than Auto Mode offers, but doesn't want to dive into Expert Mode quite yet

-Added "McAfee Stinger" to Auto Mode

-Added "YARA" to Forensics modules and menu for help analyzing malware

-Fixed "Update Module" option from executing the repack command after update, if the network is offline

-Updated all "Auto Mode Aware" modules auto scripts

-Updated "Malwarebytes" module to use v2.0 framework. All v2.0 modules are "global variable aware", can share resources, and can run in all modes

-Updated "Mcafee Stinger" module to now support both 32 and 64 bit modes for updates and scanner

-Moved "updateFailLimit" from modules.ini to pcl.ini under [modules] section

-Removed the modules.ini file from "data\config\". It has been deprecated by pcl.ini and individual module INI files

-Updated "McAfee Stinger" module to no longer use the portableapps.com package. It now uses only the default stinger EXE and OPT files. This shaves a few MB from the original size and maintains the same functionality

-Added "data\config\modules\" directory. This contains individual INI files for each module, in favor of one INI file for all modules. The INI file name matches the PCL Module name and path so any settings here will override global defaults

-Removed "Launch Scanner To Check Definitions" after downloading new binary for "RemoveIT Pro" module. This is no longer needed because the new definitions are packaged with the setup bundle

-Updated SuperAntiSpyware core files in module to v6.0.1164, for both x86 and x64 scanners

-Added more info before processing module under Expert Scanners Menu

-Fixed update issues with 64-bit version of SuperAntiSpyware module

-Added a huge list of baddies to "processList.txt" file
   
-Added the following baddies to "uninstallADL.txt" file:
   -ArcadeFrontier
   -GreatArcadeHits



v0.7.4

-Updated definitions for all compatible portable malware scanners

-Added "Forensics Mode" as a new UI option, selectable from Main UI Menu. This mode is also an Expert level menu, and currently shares resources with the Main Expert menu

-Removed "Forensics Mode" from Expert Sub-Menu and re-linked all scripting through global variables

-Fixed a typo in Malwarebytes module for on-screen display text

-Removed "Toggle Counter" from Forensics Main Menu. This is only needed for Expert Mode Baddie Removal options

-Added "Purge All Scheduled Tasks" and "Purge Custom" to Expert Manual Malware Removal Menu

-Moved "Change Default Dump Path" and "Dump EXE Names From A Target Folder" from Expert Manual Malware Removal Menu to Forensics Menu

-Added a safety check for the current PCL Temp Path. If no path is set, then the path is not removed

-Added "Show Running Services", "Show Active Network Connections", and "Show Scheduled Tasks" to Main Forensics Menu

-Fixed "Logoff" option from Reboot Menu on Expert Main Menu

-Added "defaultTextViewer" to [options] under "data\config\pcl.ini". The 2 valid options are "notepad" and "npp"

-Removed auto clicking update process for Avast Module when using Expert Mode

-Added support to Forensics Menu for checking current machine and outputting whitelists, blacklists, and greylists to text

-Fixed Spybot Scanning Module. The user no longer has to click "launch.cmd" or "update.cmd" to start, as this is now automatic like the rest of the modules

-Added "svcList.txt", "svcListOEM", and "svcListPUP.txt" to "data/scripts/lists/" for removing Baddies from Services

-Added "taskList.txt", "taskListOEM", and "taskListPUP.txt" to "data/scripts/lists/" for removing Baddies from Scheduled Tasks
   
-Added the following baddies to "uninstallPF.txt" file:
   -1clickmoviedownloader.com
   -EZDownloader
   -iExplorer
   -VipBoxSportsApp.com
   
-Added the following baddies to "rmList.txt" file:
   -Linkey
   -MediaPlayerV1
   -SNT
   -soave.net
   -soave. net
   -SW-Booster
   -TrustMediaViewerV1
   -UtilityChest_49
   -VideoPlayerV3
   -YoutubeAdblocker
   
-Added the following baddies to "rmListPD.txt" file:
   -50CCOUPonis
   -AllCCheapPuricce
   -BestSaveeFuorYouu
   -DigiSaveur
   -ec9b73db23fd37e4
   -ItsMyApp
   -MiniimuMPiriccee
   -MinimumPrIce
   -MyApps
   -NewSaver
   -systemk
   
-Added the following baddies to "rmListADLL.txt" file:
   -entrusted11
   -WhiteSmoke_New
   
-Added the following baddies to "rmListADL.txt" file:
   -Fast Browser
   -File Scout
   -Flvto Youtube Downloader
   -FlvtoYoutubeDownloader
   -genienext
   -InstallX Search Protect for Yahoo
   -Macroplant_LLC
   -Open Download Manager
   -PutLockerDownloader
   -Solid State Networks
   -ValueApps
   -WebBar

-Added the following baddie shortcut links to "rmListDesktop.txt" file:
   -Advanced System Protector
   -Clean Registry for Free!
   -EZDownloader
   -iExplorer
   -MovieDownloader
   -MyPC Backup
   -NewPlayer
   -OpenDownloaderManager
   -OpenSoftwareUpdater
   -RegClean Pro
   -VipBoxSportsApp

-Added the following baddies to "uninstallMSI.txt" file:
   -Delta ChromeToolbar {177586E7-E42E-4F38-83D1-D15B4AF5B714}
   -SavetheChildren App {A9A33A1C-3A0F-4EBC-BA5E-0C405ADB7FF4}
   -ScorpionSaver {9B65F9A3-9D24-452A-B6EF-1457D65E4259}


-Added the following baddies to "uninstallPUPMsi.txt"file:
   -Avira SearchFree Toolbar {41564952-412D-5637-00A7-A758B70C0A00}


v0.7.3

-Updated definitions for all compatible portable malware scanners

-Further cleaned up redundant code, and modularized scripts to work more seamlessly together using global variables

-Split all main sub-menu scripts into separate scripts that act as "Linux-Like" functions, and can be triggered globally by easy to remember variables

-Updated "exitStatus" global function to help properly navigate when a script reaches EOF. Currently supports "back", "close", "return", and "exit" statuses

-Moved Auto Mode script into "data\scripts\ui\auto\main.cmd". This does not affect the end-user, and does not display any visual differences

-Split the Main Expert Menu into separate scripts, now located under "data\scripts\ui\expert". This allows for menus to be easily added, modified, or removed and keep global variables in use

-Updated "unpack-upx" script for global use to unpack UPX compressed files

-Added "ui" to scripts. This directory contains a folder for each UI Mode (auto, easy, expert). This also allows for other modes to be added without too much code overhead

-Added "updateFailLimit" to "config/modules.ini". You can use this to manually set the limit of failed update attempts before asking to continue

-Updated module scripting to better handle checking for updates and retrying updates if they fail, or the user can choose to continue without updates

-Added "checkNetworkStatus" checks to all main sub-menus. This keeps the network status correct and eliminates errors or false detections during menu transitions

-Organized all variables in "set-global" into categories for each type

-Updated modules to clean up after themselves once unloaded

-Removed deprecated scripts from main scripts directory



v0.7.2

-Compacted and cleaned up a lot of orphaned and redundant code throughout the entire PCL structure

-Updated definitions for all compatible portable malware scanners

-Fixed a few typos in Help Menu

-Fixed registry dump script not writing to the proper location when running in Auto Mode

-Updated code for all module handling into a more uniform and organized format. All modes (auto, easy, expert) can use the same modules without having to write extra code

-Added "safeModeCheck" to pcl.ini for enabling and disabling (this is primarily a testing option and should remain ON during normal use)

-Added "check-pe-mode" to scripts. This is also set in the global script, and can be disabled from pcl.ini config file

-Fixed "Restart Explorer Shell" option under Reboot Menu

-Fixed a variable issue with psexec getting loaded for launching system related tasks

-Cleaned up scripting and bin directories

-Updated "RemoveIt Pro" update script. It now downloads the new EXE from server and extracts INNO installer to update scanner, definitions, and module

-Added "Download Module" to menu items under "Malware/Virus Scanners" scanning options menu, after selecting an option

-Updated "Core Temp" module core files to v1.0 RC6

-Updated "Process Explorer" module core files to v16.04

-Updated "Process Monitor" module core files to v3.1

-Fixed "checkUAC" script not asking the user to reboot after disabling UAC

-Moved "md5toggle" in "config/pcl.ini" from [options] to [updates] since this is only triggered as part of the update process



v0.7.1

-Fixed PCL update script globally. This version has fixed all known issues and can properly download and extract updates going forward. If you are on v0.7.0, the update process will download the zip and extract it, but it will not remove old files and the script will stop after extraction and the command window must be closed manually

-Updated definitions for all compatible portable malware scanners

-Added "get-local-config" to scripts. This reads INI values and overwrites global defaults, if value is present. This is processed on initial launch, and when the "init" and "reset" commands are issued

-Updated the main PCL script and split each UI mode option to a different script located in scripts folder. This allows for better portability and more fine tuned global access to all PCL items

-Added "init" and "reset" to Expert Main Menu. These are not hidden keywords, but rather two special menu items that can be typed to restart the main PCL script in 2 different ways. The "init" option reloads global variables, and the "reset" option retains them while clearing the PCL cache

-Fixed Sophos scanning module "Double Launch" issue in Auto Mode

-Updated some of the "Web Browser Manager" options under Main Expert Menu

-Fixed "checkUAC" script not executing for disabling User Access Control. The last version did not process the pipe "|" correctly after activating the set-global script

-Added GUI wait dialogs during operations that take a significant amount of time. These may also display additional help text, when available

-Fixed Option 7 under Manual Malware Common Directories Menu. The missing option was "My Documents" directory

-Fixed a few issues with pulling dumped data back to source media under Forensics Menu

-Added paths for AppData\Local, LocalLow, and Roaming for SYSTEM account to Common Directories on Manual Malware Menu

-Fixed a bug in Auto Mode that was causing the "detectme" files to get deleted before the module was unpacked. This caused the "auto" flag to not trigger when launching module, defaulting to "Expert" scan options for some

-Fixed another bug in Auto Mode causing the update script not to trigger in modules before scanning, if network connection is online

-Added "fixprinter" command to hidden keywords. This will run a script to stop spooler, clear spool directory, and restart print spooler

-Updated the default help text when selecting the Help Option from Main Expert Menu

-Updated "System Explorer" module to v6.0.1.5281 under diagnostics

-Added "Fiddler v2.4.9.6" custom portable version to modules and Utilities Menu

-Updated "McAfee Stinger" scanner and definitions to v12.1.0.1216

-Updated "Removeit Pro" module core and definitions to v2014.21.11

-Removed the "Coupounsuninstall.exe" reference from uninstallPF.txt because this is a false uninstaller

-Added "Easy2Boot v1.6.0" to "RMPrepUSB" module for assisting in PE (Preinstall Environment) related tasks

-Added a messagebox if network is offline and an update is triggered from Expert Menu

-Added "rmListRoot.txt" to "data\scripts\lists\". This will aid in cleaning baddies from root drive (ie. C:\)
   
-Added the following baddies to "uninstallPF.txt" file:
   -Framed Display

-Added the following baddies to "uninstallMSI.txt" file:
   -Driver Support {597FB4A5-DD86-4316-A410-7E8074CC2CCE}
   
-Added the following baddies to "rmList.txt" file:
   -Coupons
   -Coupouns
   -GetMeDeals
   -greatsaving
   -InboxAce_1g
   -InboxAce_1gEI
   -MapsGalaxy_39
   -RadioPI_4e
   -RadioPI_4eEI
   -RecipeHub_2j
   -RecipeHub_2jEI
   -VideoScavenger_1e
   -VideoScavenger_1eEI
   
-Added the following baddies to "rmPUP.txt" file:
   -Video Downloader
   -YouTube Accelerator

-Added the following baddies to "processList.txt" file:
   -ALOTSettings.exe
   -alotwidgets.exe
   -apnmcp.exe
   -APNSetup.exe
   -Browsers+_App#s#-bg.exe
   -Browsers+_App#s#-codedownloader.exe
   -brs.exe
   -ConsumerInputCrashHandler.exe
   -ConsumerInputUpdate.exe
   -ConsumerInputUpdateBroker.exe
   -ConsumerInputUpdateOnDemand.exe
   -FU.exe
   -g7TheBestDealsx.exe
   -GoogleInputCrashHandler.exe
   -GoogleInputUpdate.exe
   -GoogleInputUpdateBroker.exe
   -GoogleInputUpdateOnDemand.exe
   -HAMYBOX.exe
   -ServiceLocator.exe
   -SuperOptimizer.exe
   -SupOptGuard.exe
   -SupOptLauncher.exe
   -SupOptReminder.exe
   -SupOptSchedule.exe
   -SupOptSmartScan.exe
   -SupOptStart.exe
   -Toolbar.exe
   -updateFramedDisplay.exe
   -UpdateManager.exe
   -x2TheBestDealsMu175.exe



v0.7.0

-Now in BETA development stage

-Added support for the PCL to update itself. Currently only available as an option on Expert Main Menu. It is limited to checking version number from server, generating md5 list, and downloading a new full zip release, if server version is newer

-Added support for INI files for all configuration. These config files will override any default global environment setting. Currently only support for main pcl.ini file for getting version info, md5 creation, and updates

-Cleaned up variables across all scripts by using set-global script and using a more modularized environment

-Updated definitions for all compatible portable malware scanners

-Removed support for "data/pcl.ver" for determining local PCL version info, in favor of using INI config files

-Added "Detekt" spyware tool to modules and Rootkit and Other Scanners Menu

-Fixed "Recuva" 32-bit module not loading due to a typo in the launch script

-Added support for MD5 creation usage during update. This setting is located in "data/config/pcl.ini" and can be toggled "0" or "1" for disabled and enabled

-Added "clear-update-cache" to scripts to handle cleaning any temp files used during the update process

-Added support for unpacking and repacking UPX compressed files

-Renamed "check-file-status" to "check-rw-permissions" in scripts folder

-Added "EKey Finder" to modules and Recovery Menu

-Added "Bulk Rename Utility", "Filezilla", and "Win32 Disk Imager" to modules and Utilities Menu

-Fixed "My Pictures" directory not backing up properly under Backup Menu

-Added "Backup All Items" to Backup Menu. You will be able to select the destination for each directory

-Added "EasyBCD Boot Manager" to modules, and to the Expert Maintenance menu

-Added "scannerdefault" and "scannermulti" to hidden keywords. These will toggle a new option to update multiple scanning modules without user interaction. Multi mode will not be processed until tested further

-Changed 64-bit PF and CF directories in "Open Common Directories" menu from opening if OS is 32-bit. Also colors the menu items red for 64-bit paths

-Added "Web Browser Manager" to Main Expert Menu. This is used for configuring, installing, uninstalling, cleaning, and fixing detected browsers

-Added "Check For PCL Updates" menu option to Main Expert Menu

-Fixed "dump-all-locations" baddie registry dump script in Auto Mode not using the global "%dumpPath%" variable

-Removed "Access Status" from top toolbar

-Added "Fake Flash Test", "Linux Reader", and "RMPrepUSB" to modules and Utilities Menu

-Added "Launch Windows Task Manager" to Manual Malware Menu

-Added "Respawn Explorer Shell as SYSTEM" to Reboot Menu

-Removed pause after scan and scan/update operations have completed. This applies to all scanner modules in Expert Mode

-Changed some options around on Main Expert and descendant menu items

-Added bannerText to Main UI Mode Launch Menu

-Added "snip" to hidden keywords. This launches the Windows Snipping Tool. Not compatible with XP

-Updated "bitdefender" module update script. It now waits 3 secs after message is displayed if no updates are available

-Fixed "Toggle Counter" not syncing between "normal" and "forensics" mode menus properly under Manual Malware Menu

-Added "build-update-list" to scripts. This will gather details on current PCL files for use when checking for updates

-Added "Display Current To Do List" as a menu option on Help Menu

-Added the path "/data/config/" to store all PCL configuration files

-Renamed "data/config.ini" to "/data/config/pcl.ini" to accomodate the new configuration changes

-Moved "/data/todo.txt", and "/data/known-issues.txt" to "/data/text/" to cleanup main data directory

-Changed colors of "Forensic Mode" and "Normal Mode" menu items to make them more noticeable under Manual Malware Menu

-Added "sync-environment" to scripts. This will keep the global variables synced across multiple instances of the PCL, invoked as USER, SYSTEM, or any other mode

-Moved "View/Edit Hosts File" from main Expert Menu to Manual Malware Removal Menu

-Removed "View Current Temp Folders" from Main Expert Menu

-Added default Temp Folder locations to "Open Common Directories" menu option under Manual Malware Menu



v0.6.9

-Updated definitions for all compatible portable malware scanners

-Added "MS Config", "Direct-X Diag", and "Services.msc" to Manual Malware Menu (thanks jriedel)

-Added "Transfer Data Dumps to Source Media" to Forensics Mode Menu (thanks jriedel)

-Added "set-global" to scripts. This will hold all variables and commands for the entire PCL to use globally

-Added "defragme" to hidden keywords. This option will start a defragmentation on the current source drive using the Windows Defrag tool

-Fixed an issue with keywords returning to main menu after executing. Now only entering "menu" as a keyword will return to main menu. All other keywords return to expert mode menu

-Modified behavior of "wincontig" defrag module to select %SystemDrive% as default scan with GUI interface

-Modified update script in "avast" module to now handle the update process unattended

-Added scripting to get source drive letter as "root" directory. This will also soon be changeable to switch base target drives for scanning and other tasks

-Updated CCleaner to v4.19.4867. Both x86 and x64 versions were updated in PCL module

-Fixed EULA nag from appearing when running "Autoruns", "ProcessMonitor", and "ProcessExplorer" modules

-Added "getsystem" to hidden keywords. This will respawn the PCL as SYSTEM. This mode is currently *BROKEN* and does not use the correct %temp% path, so all modules will not work, and also some menu items. A warning will be displayed with brief instructions before launching

-Added "check-file-status" to scripts. This will check if current media is writable or read-only

-Fixed double quotes issue when returning default "pclModuleTemp" variable

-Added "Access" to top banner text. This will display the file access mode "rw" if writable, and "ro" for read-only media (CD-ROM)

-Added framework scripting for updates. The PCL will be able to update itself and download modules, scripts, and other files

-Added an option to run the PCL as USER or SYSTEM. This option is currently disabled because of issues, and will run in "user" mode by default

-Fixed "browserLoop", "regLoop", and "tkLoop" scripts to not run infinitely in Auto Mode

-Fixed color changing when an invalid entry is made at the main menu

-Added "getset" and "showset" to hidden keywords. This will show all current active environment variables in a command window, or text file respectively

-Changed Auto Mode uninstall and removal scripts to skip OEM software and remove PUPS by default

-Added the following baddie shortcut links to "rmListDesktop.txt" file:
   -Eusing Free Registry Cleaner
   -Eusing Free Registry Defrag
   -Eusing Free System Cleaner
   -Free Music
   -PepperZip
   -Super Optimizer
   -Torch
   
-Added the following baddies to "uninstallPF.txt" file:
   -alot
   -Browser Features
   -ContinueToSave
   -Coupons.com CouponBar
   -PepperZip
   -Setup Support for Consumer Input
   -SiteRanker
   -Super Optimizer
   
-Added the following baddies to "rmList.txt" file:
   -35556262-902E-49AE-8622-66E14F1F041C
   -Avanquest
   -Browsers+_App#s#
   -CouponArific
   -Eusing Free Registry Cleaner
   -Eusing Free Registry Defrag
   -GeniusBox
   -HOTALBUMMyBOX
   -IEToolbar
   -iWonEI
   -ospd_us_201
   -PCTRunner
   -puredefmusic
   -System_Alerts_LLC
   -ver8NewPlayer
   
-Added the following baddies to "rmListADR.txt" file:
   -acccore
   -Aszo
   -Compete
   -Ixdo
   -Move Networks
   -NCdownloader
   -SimilarSites
   -Systweak
   
-Added the following baddies to "rmListPD.txt" file:
   -BetterSoft
   -continueaTooSave
   -Prism Deploy
   -saveitkeepo
   -ShopperPro
   -TxtMakeR
   
-Added the following baddies to "rmListADL.txt" file:
   -DesktopTemperature
   
-Added the following baddies to "rmListADLL.txt" file:
   -FunWebProducts
   -Move Networks
   -MyWebSearch
   
-Added the following baddies to "rmPUP.txt" file:
   -Games.com Toolbar
   -Setup NetZero
   
-Added the following baddies to "rmListDocuments.txt" file:
   -Optimizer Pro
   -Super Optimizer

v0.6.8

-Updated definitions for all compatible portable malware scanners

-Added options to spawn command prompts as Administrator and System to Manual Malware Removal Menu

-Fixed "check-network-status" script not reporting correct status for Windows 8.1 and lower. It now checks for correct replies based on OS. Should work on XP, Vista, 7, 8, 8.1, and 10

-Fixed network status not refreshing in navigation bar when changing menus

-Updated "wallpaper-thief" script to use the current %USERNAME% variable as the path, after main dump folder

-Fixed "wallpaper-thief" script to exit if the copied wallpaper already exists in destination. This fixes an infinite loop issue on some machines that continue copying the same wallpapers over and over

-Fixed setting correct registry entries, while running, for Malware Destroyer, Malwarebytes, and Spybot. Also fixed registry removal when finished

-Added "rmListCF.txt" to /scripts/lists/. This will be used to populate baddies for "%PF%\Common Files" directories

-Added the following baddie shortcut links to "rmListDesktop.txt" file:
   -Activeris AntiMalware
   
-Added the following baddies to "rmList.txt" file:
   -1H1Q
   -EonjoyyCoouuppoNN
   -FastMediaConverter
   -Itibiti Soft Phone
   -JoONiCCoupono
   -Maxiget
   -PCHealthBoost
   -Rr Savings
   -Speedial
   -SymSilent
   -VebaSearch
   -VideoDownloadConverter
   
-Added the following baddies to "rmListCF.txt" file:
   -DealAlly
   -Hoist Search
   -Reimage
   -Soluto
   
-Added the following baddies to "rmListPF.txt" file:
   -Astrology_4aEI
   -di9TheBestDeals
   -DriverRestore
   -mefeediatest
   -ospd_us_210
   -puredefmusic
   -Search Extensions
   -TidyNetwork

-Added the following baddies to "rmListPD.txt" file:
   -BlueStacks
   -eSellerate
   -FirefoxToolbar
   -install_clap
   -jiBrhhIgtr
   -OnlineLowDeals
   -Soluto
   -surfkeepit
   -Vaudix

-Added the following baddies to "rmListADR.txt" file:
   -SoftGrid Client

-Added the following baddies to "rmListADL.txt" file:
   -Obrona Block Ads
   -ospd_us_210
   -Pay-By-Ads
   -Pokki
   -SoftThinks
   -TidyNetwork
   -UpdateAdmin

-Added the following baddies to "rmPUP.txt" file:
   -Beware
   -PC-Doctor for Windows

-Added the following baddies to "rmPUPDocuments.txt" file:
   -McAfee Vaults



v0.6.7

-Updated definitions for all compatible portable malware scanners

-Added "McAfee Virus Scan" to cleaning modules and Malware Scanners menu. Also added the module to run in Auto Mode 

-Changed the order of a few items under Manual Removal -> Other Scripts and Tweaks

-Added "getwallpaper" to list of hidden keywords. This will run the "wallpaper-thief" script and dump system wallpapers to easily copy to another source. This is way off base for the PCL, but as a tech, I felt it was needed ;)

-Added "%ProgramData%\pcl\" to cleanup list when exiting. This folder is used for registry dumps and other temp files when PCL is in use



v0.6.6

-Updated definitions for all compatible portable malware scanners

-Updated "checkNetwork" script to determine the status based on Windows version to handle the different outputs properly when offline and online

-Added separate registry entries to control "Take Ownership" context menu, based on Windows version. The "Remove Take Ownership" option still works for all Windows versions

-Fixed "False Flag" issue with "checkUAC" script. It now properly checks to verify and disable UAC prompts for Windows 8, Windows 8.1, and Windows 10

-Added "subinacl.exe" to "data/bin/"

-Added "reset-acl-perms" to scripts. This will reset the registry permissions and Windows system folder permissions to default for administrator. This option is selectable on Manual Malware menu

-Added "purge-notification-cache" to scripts. This removes all the leftover and unused icons in the notification area. This option is also selectable on Manual Malware menu, and has been added to Auto Mode



v0.6.5

-Updated definitions for all compatible portable malware scanners

-Added full support for Windows 10 Technical Preview and future builds. Tested all modules with Scan, Update, and Repack options

-Updated some routines to use virtual writable paths for the PCL module temp building process. This affected the "Update and Repack" option under Malware Scanners. All scripting should now be compatible with Windows 10 and earlier versions

-Added Windows 10 to the "checkOS" script

-Fixed text error on menu for "Windows Registry Recovery". It was mislabled as "Windows Registry Repair"

-Removed "uimode" from hidden keywords because it has been deprecated

-Fixed issue with registry values getting applied correctly in "checkUAC" script

-Added "dumpPath" to global list of variables

-Added the option to change the default "dumpPath" variable under Expert menu

-Added backup, restore, and clean scripts for "Run" and "RunOnce" registry paths. Also added menu options under Expert -> Manual Malware Removal

-Added the following baddies to "uninstallPF.txt" file:
   -Klip Pal
   -SlimDrivers
   -SparkTrust PC Cleaner Plus
   -ver3TheBestDeals
   -Web Protect

-Added the following baddies to "rmListADLL.txt" file:
   -GutscheinCodes
   -LyricsParty-16
   -Protect
   -Torntv V9.0

-Added the following baddies to "rmListPD.txt" file:
   -DSearchLink
   -SparkTrust

-Added the following baddies to "rmListADL.txt" file:
   -emaze
   -OurrarUdl
   -Rocket
   -SoftGrid Client
   -Software Updater
   -Software_Updater
   -SoftwareUpdater
   -SpeedFixTool

-Added the following baddie shortcut links to "rmListDesktop.txt" file:
   -Clean Registry for Free!
   -FREE Games
   -NewPlayer
   -Open It!
   -Optimize Your PC
   -PC Tech Hotline

-Added the following baddies to "processList.txt" file:
   -a5TheBestDealsA83.exe
   -b6o.exe
   -KlipPalUninstall.exe
   -MyOSProtect.exe
   -o1LX179.exe
   -updateKlipPal.exe



v0.6.4

-Updated definitions for all compatible portable malware scanners

-Added defragmentation of main hard drive to Auto Mode using WinContig (thanks Chad!). It will run silently and unattended after scanners are complete

-Updated SuperAntiSpyware core files in module to v6.0.1146. Also fully supports portable mode with the new UI, for both x86 and x64 scanners

-Removed "McAfee Stinger" from Auto Mode because it is not fully automatic. This will be re-added when scripting is updated

-Changed default action for extracting PCL modules to overwrite all files extracted to temp folder

-Added "rmListDocuments.txt" and "rmPUPDocuments.txt" to "/data/scripts/lists/" for removing junkware from Documents folder

-Updated CCleaner to v4.16.4844. Both x86 and x64 versions were updated in PCL module

-Added baddie folder removal to accompany the .lnk and .url removals for Start Menu in rmLoop script

-Moved %PROCESSOR_ARCHITECTURE% variable check back to its original location. I have verified to myself that if 64bit processor and 32bit OS, this variable is still correct when used



v0.6.3

-Updated definitions for all compatible portable malware scanners

-Added "uninstallAV.txt" and "uninstallAVMSI.txt" to "data/scripts/lists/" to hold a list of Antivirus that can be optionally uninstalled

-Disabled "Panda Antivirus" scanning module to until scanning script is fixed. The update module still works

-Added "Emsisoft" to Auto Mode and added "detectme" checks

-Fixed "detectme" file error in bitdefender module for Auto Mode ONLY

-Moved %PROCESSOR_ARCHITECTURE% variable check in "checkos.cmd" script to happen before checking directories. This avoids detecting a 64-bit processor, but having a 32-bit OS installed and the %OS% variable getting set as 64-bit

-Cleaned up old "sav32cli" files in Sophos module. Only the original EXE and DLL files were left and archived in "/data/old.zip". This saves about 95MB of space from previous module

-Fixed "Forensics Mode" option not showing up under Manual Malware Removal menu

-Changed and fixed some text on multiple menus

-Added "blacklist.txt", "greylist.txt", and "whitelist.txt" to "/data/scripts/lists/". This will be used by Forensics Mode to try and determine which folders and files are potential "baddies", based on known "good guys" and known baddies. Archives can then be made in future builds to automatically "quarantine" potential baddies for analysis. Parts of Auto Mode will incorporate this to a smaller extent

-Added Sophos to Auto Mode and now checks for "detectme" files

-Added a /wait switch for Sophos scanner in Auto Mode

-Removed vipre from Auto Mode until it can be launched and wait for the next action to happen

-Added a check for 0-byte files. This fixes issues with incomplete updates getting repacked or used in modules

-Fixed dead link issue for Sophos updates. Now using SVRT as scanner. New links pointing to the "Sophos Virus Removal Tool" are now referenced

-Fixed Sophos update script to now handle the new (again) format. This time it extracts the RAR SFX archive, extracts the MSI file, then copies the updated contents to the module

-Removed Clamwin from Auto Mode scanners until both updates and scanning scripts can be launched unattended

-Updated CCleaner to v4.17.4808. Both x86 and x64 versions were updated in PCL module

-Changed some text in regLoop scripts

-Updated "McAfee Stinger" scanner and definitions to v12.1.0.1091

-Now cleaning the PCL Temp folder on launch, and on exit, when using the X hotkey on Expert Mode

-Added the following baddies to "uninstallPF.txt" file:
   -InfoAtoms
   -OApps

-Added the following baddies to "processList.txt" file:
   -dler.exe
   -mntTMPl.exe
   -MyClaroTB.exe
   -ose00000.exe
   -sl-dlc.exe
   -SmartPCCleaner.exe
   -SPCGuard.exe
   -SPCLauncher.exe
   -SPCReminder.exe
   -SPCSchedule.exe
   -SPCSmartScan.exe
   -Startw3i.exe
   -weDownload Manager-enabler.exe

-Added the following baddies to "rmList.txt" file:
   -FunkLyrics
   -InfoAtoms
   -Zoom Downloader

-Added the following baddies to "rmListADL.txt" file:
   -Coupon Companion Plugin
   -NexGenMediaPlayer
   -Zoom_Downloader

-Added the following baddies to "rmListADLL.txt" file:
   -Claro LTD
   -DownloadManager
   -PriceGong
   -Toolbar4

-Added the following baddies to "rmListADR.txt" file:
   -Babylon
   -Claro
   -Claro LTD
   -DefaultTab
   -Iminent
   -Smart PC Cleaner
   -Strongvault
   -WebApp

-Added the following baddies to "rmListPD.txt" file:
   -Iminent
   -install_clap
   -WeCareReminder

-Added the following baddies to "rmPUP.txt" file:
   -Free Ride Games
   -ooVoo Details
   -Yahoo! Companion



v0.6.2

-Updated definitions for all compatible portable malware scanners

-Added "Check Network Status" that can be checked anytime globally. This will have many benefits, such as only updating scanners in Auto Mode when online, and running "Scan Only" when offline

-Removed "Counter Status" from top menu bar and replaced with "Network Status" display

-Added SFC Scan (System File Checker) to Auto Mode and the Manual Malware Removal menu on expert mode

-Added "clamwin" and "mcafee-stinger" modules to Auto Mode, and added "detectme" support to both

-Added a default for all modules to use "Scan Only" mode if no selection is made and ENTER is pressed

-Removed silent install switches, except "/s" on uninstall-loop script until tested further. The current method was spawning multiple instances of the uninstaller

-Fixed the Manual Malware Removal and Forensics menus not resetting the menu option when returning back

-Fixed the uninstallMSI script for both expert and auto modes, and added a default "/quiet" switch. It will no longer prompt you to remove a non-existent installer GUID

-Added the following baddies to "rmListADR.txt" file:
   -Weatherbug

-Added the following baddies to "rmListPF.txt" file:
   -BetterLinks

-Added the following baddies to "rmListPD.txt" file:
   -Linkury

-Added the following baddies to "rmPUP.txt" file:
   -uTorrentBar

-Added the following baddies to "uninstallMSI.txt" file:
   -Community Smartbar {57A8BDFA-D6AD-4F59-8008-1A290C981075}



v0.6.1

-This is a QuickFix Update Release. Tested this time, haha sorry, got excited about the last release too soon :)

-Added a cleanup routine on temp files to run first when using Auto Mode. This one was obvious, but was missed from the last release ;)

-Fixed scanners not waiting for the previous one to finish before launching for Auto Mode

-Changed the execution of scanners in Auto Mode to be called and not spawn external windows

-Added Vipre Rescue Scanner to the Auto Mode list of tasks to perform

-Fixed the detectme files not writing to the temp folder when the scannerActive variable changes

-Updated the "vipre" scanning module to support the new "detectme" checks

-Added some common silent switches to the uninstall routines. This will hopefully automate most of the uninstalls without having to click YES or UNINSTALL on each one. This will be better supported in future releases

-Fixed the rmLoop script from double launching in Auto Mode



v0.6.0

-Updated definitions for all compatible portable malware scanners

-Activated Auto Mode and set as default. Other modes can be selected at launch (Easy and Expert)

-Added Quick Tips and Help text on the main page when launched

-Added detectme checks for launching scanners, utilities, and tools in auto mode from the same modules that Expert mode uses

-Updated the "antivir" and "bitdefender" scanning modules to support the new "detectme" checks

-Added "menu" to the list of hidden keywords

-Fixed all uiMode and uiModeOverride options so you can flip through all modes using expert mode keywords and return properly when main launch menu is loaded

-Tweaked all the Auto Mode scripts to do a one-time loop and exit, except for the browser and process kill loop scripts

-Added Antivir and BitDefender to the Auto Mode list of tasks to perform. Other scanners will be added that can be completely unattended

-Added support for removing malicious registry entries. Using the same lists as "rmLoop" and "uninstallLoop" scripts for targets. This is option 9 under Manual Malware Removal menu

-Added proper title text to match the current page as you navigate through the menus

-Fixed temp folders from opening if they do not exist when selecting "View Temp Folders" from main menu

-Added a file check for "ui.%mode%" (ie /data/ui.menu, /data/ui.auto, /data/ui.easy, and /data/ui.expert). The value read from here will override and set the default ui type on launch. This is easily changeable by simply renaming the file to whatever mode you want to force. If you manually type a mode using keywords, or use the "change-ui" script from the main menu, then the selected mode will launch as normal and when execution is done it will return to the "ui.%mode%" file value



v0.5.9

-Updated definitions for all compatible portable malware scanners

-Added scripting for both Linux and Windows to download Microsoft Security Essentials update files directly to source media. They are located in "/data/scripts/linux/" and "/data/scripts/updates/" respectively

-Default layout is "Expert" until the Auto and Easy Modes are tested, and stable

-Added "auto" to UI Modes

-Removed "normal" from UI Modes

-Added "auto", "easy", and "expert" to hidden keywords. These can be typed anytime on the main menu to change the UI Mode

-Added "uimode" to hidden keywords. UI Change Options Menu to select Auto, Easy, and Expert levels can be accessed. The layout and options will be different depending on which one is chosen. The normal display will be the default EXPERT setting

-Fixed path error in "get-paths" script for the "Program Files (x86)" directory. This affected the rmLoop script variants not processing all targets in that path

-Disabled "Definition Update Reminder" in SuperAntispyware module for both x86 and x64 versions

-Fixed launching error for msiexec.exe in "uninstall-loop-msi" script. All MSI install target ID's are now properly processed for uninstall routines. Applies to Baddies, PUP, and OEM lists

-Added the following baddies to "processList.txt" file:
   -BabMaint.exe
   -g2mdlhlpx.exe

-Added the following targets to "uninstallMSIPup.txt" file:
   -JunoPreloader {6423EF83-6E1D-4D22-A36F-689CD19FD4D2}
   -NetZeroPreloader {352310C3-E46B-42D3-8F32-54721FDD72D9}

-Added the following baddies to "rmPUP.txt" file:
   -AVG SafeGuard toolbar
   -AVG Secure Search
   -AVG Security Toolbar
   -Best Buy pc app
   -Geek Squad

-Added the following baddies to "rmListPF.txt" file:
   -Driver Whiz
   -Gophoto.it
   -IMinent Toolbar
   -KeyBar_1.13
   -Speedial

-Added the following baddies to "rmListPD.txt" file:
   -DownloadnSave
   -Driver Support
   -ErrorEND64
   -Fighters
   -FileCure
   -InstallMate
   -PCSettings
   -pKIFoPAQ
   -Premium
   -QuickSet
   -Radsteroids
   -RoyaalShopPeerAPpa
   -SalesCehecker
   -SearchNewTab
   -TuneUp Software
   -webex
   -WowwCouupon

-Added the following baddies to "rmListADR.txt" file:
   -IDMSQ
   -SpeedAnalysis2
   -WinBatch

-Added the following baddies to "rmListDesktop.txt" file:
   -Continue VuuPC Installation
   -Driver Support
   -PennyBee
   -RegClean Pro

-Added the following targets to "rmListPUP.txt" file:
   -JunoPreloader
   -NetZeroPreloader

-Added the following targets to "rmListStartMenu.txt" file:
   -Driver Support


v0.5.8

-Updated definitions for all compatible portable malware scanners

-Fixed path error in parsing some sections of the rmList*.txt files. It was not processing the full path, therefore not removing items it read from those files

-Updated some scripting for the new 2.0 module framework. I will be migrating a few selected scanners over to the new format in future releases very soon

-Fixed launch error when running Windows XP for Malwarebytes and SuperAntiSpyware modules. Windows XP Pro Edition tested, Home Edition still needs testing

-Added "rmListADL.txt", "rmListADLL.txt", "rmListADR.txt", "rmListPD.txt" and "rmListPF.txt" to "/scripts/lists/" for AppDataLocalLow, AppDataLocal, AppDataRoaming, ProgramData, and ProgramFiles directories

-Added the following baddies to "uninstallPF.txt" file:
   -Astromenda
   -Groovorio
   -OpenSoftwareUpdater
   -PennyBee
   -Popcorn Time
   -WSE_Astromenda

-Added the following baddies to "rmList.txt" file:
   -57F737B4-ACBE-4AFB-87B3-6DC08B80F484
   -AllDaySavings
   -fst_us_209
   -grillaprice
   -pcmax
   -predm

-Added the following baddies to "rmListPD.txt" file:
   -{E0A9340B-C01B-42C1-9910-C307D7BE4756}
   -dowNloadIitkeepu
   -SearchModule
   -Systweak
   -Tarma Installer

-Added the following baddies to "rmListPF.txt" file:
   -BabylonToolbar
   -BlockAndSurfS
   -Browse Safe
   -Cozi Express
   -diamondata
   -Driver Support
   -DriverUpdate
   -eDealsPop
   -fst_us_135
   -Inbox.com
   -LPT
   -Pro PC Cleaner
   -ProtectedToolbar
   -Re-Markable-soft
   -SafePCRepair
   -SelectRebates
   -sizlsearch
   -TheTorntv V10
   -ver6TheBestDeals
   -v04BlockAndSurf
   -Weather It Up

-Added the following baddies to "rmListADL.txt" file:
   -DownloadTerms
   -globalUpdate
   -Pro_PC_Cleaner
   -SevereWeatherAlerts
   -SlimWare Utilities Inc

-Added the following baddies to "rmListADLL.txt" file:
   -BrowserPlus1
   -Delta
   -IMVU_Inc
   -YahooCouponAddOn

-Added the following baddies to "rmListADR.txt" file:
   -ap_logs
   -Betcat
   -KeepMySettingsX
   -OpenSoftwareUpdater
   -Optimizer Pro
   -PC Tech Hotline
   -Pro PC Cleaner
   -Uniblue


v0.5.7

-Updated definitions for all compatible portable malware scanners

-Updated Avast aswMBR Scanner to v1.0.1.2041. Also updated module update script to automatically download the newest scanner before downloading the newest definitions

-Fixed menu links for AVG Antivirus and MS Security Essentials to return to scanners menu until portable versions are properly working

-Added Notepad++ as a secondary option to open text based files. The 2 variables are "showText" and "showTextPlus" respectively for default Notepad and Notepad++

-Fixed scripting error in "unlock-manual.cmd" if ENTER was pressed and no entry was made when first loading the script



v0.5.6

-Updated definitions for all compatible portable malware scanners

-Added "injecton" and "injectoff" keywords to Main Menu. If turned ON, you will be able to inject files into the current active module while running. This can be used for Scan, Update, and Repack options. These options will be menu selectable after tested further. As is, it seems to work as intended

-Added the ability to change the destination directory for Module Injection. The Base Path will remain the same (%module%\data\) to avoid issues, but any new directories can be created and used after "\data\". If you changed it to "injected", then the new full path would be "%module%\data\injected\"

-Updated CCleaner to v4.16.4763. Both x86 and x64 versions were updated in PCL module

-Added "Norton Power Eraser" to "\data\modules\cleaning\tools\" and also added to Rootkit and Other Scanners menu

-Added basic framework scripting for new module system. This will make it easier to integrate all the types of tools with launch, update, and repack options, if applicable. I will be slowly migrating all modules to the new format as I have time to test them. In future updates, the new module system will be able to create portable modules for many different scanners and programs, semi-automatically, even using some setup EXE files as source

-Added "TrashReg" to Maintenance modules and menu

-Updated the Diagnostics Menu. All items are listed alphabetically now to match the rest of the PCL structure

-Updated "System Explorer" module to v5.9.1.5242 under diagnostics

-Added "hostsclean" to keywords. Type this at the main menu and press ENTER to clean the default HOSTS file

-Added "Show Hidden Keywords" to Help Menu options. It also includes brief instructions of how to use them

-Fixed Help Menu not resetting the last option used when returning back to Help Menu from another option

-Added the following baddies to "uninstallPF.txt" file:
   -Alnaddy.com\alnaddyToolbar\1.6.9.16
   -findopolis
   -IDMSQ
   -Giraffic
   -Savings Sidekick
   -Sk_Enabler
   -VeohWebPlayer

-Added the following baddies to "uninstallPUP.txt" file:
   -Best Buy pc app

-Added the following baddies to "rmList.txt" file:
   -Application Updater
   -Blingee Plus
   -BrowserProtect
   -CostMin
   -CouponDownloader
   -ddeaalpeak
   -DDIgiaCeoupoon
   -di2BlockAndSurf
   -DIgiSavErr
   -eDealsPop
   -FixCleaner
   -MediaPlayerplus
   -MediaViewV1
   -MediaWatchV1
   -Mysearchdial
   -Plus-HD-9.3
   -PureLeads
   -SaaVeNaEweaAAppz
   -SaveNNewaAppz
   -sAvingttoyou
   -Settings Manager
   -SmartPCScan
   -smdmf
   -SoftSafe
   -Start Savin
   -Supporter
   -ver3BlockAndSurf
   -ver7BlockAndSurf
   -ZalmanInstaller_52330

-Added the following paths to the registry dump locations script:
   -HKCU\Software\Microsoft\Windows NT\CurrentVersion\Windows\load
   -HKLM\Software\Microsoft\Windows\CurrentVersion\ShellServiceObjectDelayLoad
   -HKLM\System\Control\WOW\wowcmdline
   -HKLM\System\Control\WOW\cmdline
   -HKLM\System\CurrentControlSet\Services
   -HKLM\System\CurrentControlSet\Control\Session Manager
   -HKLM\System\CurrentControlSet\Services\VxD
   -HKLM\Software\Microsoft\Active Setup\Installed Components
   -HKLM\Software\Microsoft\Windows NT\CurrentVersion\Winlogon
   


v0.5.5

-Updated definitions for all compatible portable malware scanners

-Fixed Manual Malware Menu. Some menu items were not working correctly, all are fixed now

-Updated "Norman Malware Cleaner" module update script. It now downloads the newest EXE and copies it back to \data\ folder and to launch media as needed

-Added "get-paths" script to "\data\scripts\". This has been integrated into the PCL, and all other scripts now reference it to get all needed path variables from one source

-Fixed update script for "McAfee Stinger" and moved to Malware Scanners menu. Now properly downloads the new stinger.exe files and repacks updated files automatically

-Updated "McAfee Stinger" scanner and definitions to v12.1.0.1015

-Added "File Assassin" and "Reg Assassin" to Rootkit and Other Scanners menu



v0.5.4

-Updated definitions for all compatible portable malware scanners

-Fixed "Antivir" update script. It now properly downloads the newest VDF files via Fuse Bundle Generator and saves the vdf_fusebundle.zip file so the scanner can use the updated definitions

-Updated "Antivir" launch script to use the vdf_fusebundle.zip file to extract its contents for scanning, and remove the extracted contents after scanning is complete

-Fixed definitions not displaying the correct "Last Updated" time in SuperAntiSpyware module



v0.5.3

-Updated definitions for all compatible portable malware scanners

-Fixed "Vipre Rescue Scanner" launch script giving a "Definitions Not Found" error. Packaging and scripting was redone from scratch. Wrote a small "vLoader.exe" stub to get scanning working properly.

-Fixed "Vipre Rescue Scanner" update script. Now checks for newest build and automatically downloads, unpacks, repacks, and copies back to launch media as needed

-Cleaned up some code in main PCL script



v0.5.2

-Updated definitions for all compatible portable malware scanners

-Added "Forensics Menu" on the Manual Malware Removal Menu. This will serve people like myself in collecting and analysing malware to better understand how it works and write code to remove it from systems like yours ;)

-Fixed Avast update and launch modules not returning back to scanners menu after executing

-Updated SuperAntiSpyware Portable Scanner to 5.7.1026. Also now supports both x86 and x64 modes, depending on CPU architecture

-Wrote a quick nop.exe program for SuperAntiSpyware to bypass "SSUpdate.exe" and "SSUpdate64.exe" execution. The nop.exe replaces both the SSUpdate and SSUpdate64 files. This supresses the update nag from appearing in the lower right-hand corner

-Cleaned up code for launch and update scripts in Antivir module. The filesize was reduced by over 60MB by using only the *.GZ files from the updates, and decompressing the *.VDF files from them when launching the scanner only. *.VDF files are cleaned up after scanning is finished and only original and updated *.GZ files remain.

-Updated "Spybot Search & Destroy" to v2.4.40.0. Using the version from portableapps.com with scripting for PCL module to function

-Added "ADW Cleaner", "BHO Scanner", and "Hijack Free" to modules and Maintenance Menu

-Added "Install Spy" to modules and Diagnostics Menu

-Added "Emcosoft Malware Destroyer", "Norman Malware Cleaner", and "Vipre Rescue Scanner" to cleaning modules and to the Malware Scanners Menu

-Added "Hitman Pro" 32bit and 64bit versions to the Rootkit/Other Scanners Menu

-Added "McAfee Stinger" Portable to Rootkit/Other Scanners Menu. Using the version from portableapps.com with scripting for PCL module to function

-Added the following baddies to "uninstallPF.txt" file:
   -B021CBBD-E38E-4F8C-8E93-6624B0597A23
   -WinnerDM

-Added the following baddies to "uninstallPUP.txt" file:
   -IObit Surfing Protection

-Added the following baddies to "uninstallADL.txt" file:
   -WinnerDM

-Added the following baddies to "uninstallADR.txt" file:
   -Search Protection

-Added the following baddies to "processList.txt" file:
   -cyycfhtzro64.exe
   -dlm.exe
   -wdm.exe

-Added the following baddies to "rmList.txt" file:
   -FileOpenerPro
   -WeCareReminder

-Added the following baddies to "rmListDesktop.txt" file:
   -Winner Download Manager



v0.5.1

-Updated definitions for all compatible portable malware scanners

-Added "Display PCL Version History" and "Display Current Known Issues" to Help Menu

-Updated Sophos module update script to 1.4 to be compatible with the new update package. Everything is scripted to process the update automatically

-Fixed title text error and double launching bug in Sophos module update script

-Changed disclaimer text a bit when first launched

-Added "Uninstall MSI" script to launch after EXE script for Baddie Removal under Manual Malware Removal

-Added "uninstallMSI.txt" to "data\scripts\lists\". This will handle all the MSI uninstall routines for baddies

-Added the following baddies to "uninstallMSI.txt" file:
   -SavingsbullFilter {813BA625-B0FA-48D8-9B75-59759C88C219}

-Added the following baddies to "uninstallPF.txt" file:
   -Bitcasa
   -WebBar
   -Yula

-Added the following baddies to "processList.txt" file:
   -Bitcasa.exe
   -WebBar.exe
   -Yulasee.exe



v0.5.0

-Updated definitions for all compatible portable malware scanners

-Fixed menu entry for "HijackThis" under Maintenance Menu

-Updated Antivir Command Line Scanner to 1.9.161.2.

-Updated Antivir module update script to 1.3 to fix dead link issue. There was some heavy scripting added for handling the new update process to be completely automated and transparent to the end user. I will cleanup the process a bit more next PCL version and shave a few MB off the filesize. I wanted to release this because the old update links and files no longer work :/



v0.4.9

-Updated definitions for all compatible portable malware scanners

-Added "Avast awsMBR Scanner" to Malware Scanners Menu

-Added "HijackThis" and "Unhide" to Maintenance Menu

-Added "GooredFix" and "Rootkit Revealer" to Standalone Scanners Menu

-Added "Current Module" display for Malware Scanners menu when selecting options



v0.4.8

-Updated definitions for all compatible portable malware scanners

-Added "WinContig" to "/data/modules/maintenance/" and is also selectable through the menu

-Added install and uninstall options for Unlocker under Manual Malware Removal -> Unlock Menu

-Added "Avira Antivir Removal Tool" to Standalone Scanner Menu

-Added "Avira Antivir Uninstaller" to A/V Cleaner Menu

-Added "UI Mode" options. Default is "Normal", the other option is "Easy". Only normal is currently activated

-Updated the top banner to accomodate the new UI Mode status

-Added the following EXE names to "browserList.txt" for use with Browser Kill Loop:
   -avant.exe
   -adownloader.exe
   -avantvw.exe
   -xbrowser.exe
   -ybrowser.exe
   -zbrowser.exe
   -dragon.exe
   -icedragon.exe
   -flock.exe
   -k-meleon.exe
   -Maxthon.exe
   -MxUp.exe
   -navigator.exe
   -seamonkey.exe

-Added "uninstall" to "/data/scripts/" to help uninstall different common applications, if needed



v0.4.7

-Updated definitions for all compatible portable malware scanners

-Added a counter to append digits to certain malware targets i.e. fst_us_103, fst_us_104, fst_us_105, fst_us_106, etc. This will be integrated slowly into the PCL

-Added "counterList.txt" to "data/scripts/lists/" to accomodate the counter script in removal of malware that uses the same directory name, but with digits attached to them for stealthiness

-Added a "Toggle Counter" option to Manual Removal script. The letters "Z" and "z" toggle the status "On" and "Off"

-Fixed "Clone PCL" menu from not returning to main menu after selecting the Back option

-Updated top banner to remain static across more pages. This is merely a cosmetic thing and will be tweaked as things are updated

-Updated "Manual Malware Removal" menu. Re-organized a few menu items

-Added "hex2text.exe" to "/data/bin/". This will be used for decoding registry uninstall entries back to plain text

-Added the following baddies to "rmList.txt" file:
   -Appupdater
   -CostMin
   -LPT

-Added the following baddies to "uninstallPF.txt" file:
   -fst_us_102

-Added the following baddies to "processList.txt" file:
   -appupdater.exe
   -appupdaterd.exe
   -appupdateri.exe
   -appupdaters.exe
   -appupdatert.exe
   -appupdaterw.exe
   -freeSoftToday_widget.exe
   -gpg2.exe
   -linmsl.exe
   -predm.exe
   -Smartbar.Monetization.Proxy.ProxyRemover.exe
   -srptm.exe
   -srpts.exe



v0.4.6

-Updated definitions for all compatible portable malware scanners

-Updated both x86 and x64 CCleaner modules to v4.15.4725

-Added "bytePatterns.txt", "bytePatternsOEM.txt", and "bytePatternsPUP.txt" to "/scripts/lists/"

-Added the following baddies to "processList.txt" file:
   -appRe-Markablea89.exe
   -Bitcasa.exe
   -BoostUpdater.exe
   -cinm-host.exe
   -ConsumerInputUpdate.exe
   -cookie-retriever.exe
   -crimsoliteUn.exe
   -crimsoliteUninstall.exe
   -dca-monitoring.exe
   -driverStatus.exe
   -EZ Software Updater.exe
   -focusbase.FirstRun.exe
   -focusbaseUninstall.exe
   -updatefocusbase.exe
   -nfregdrv.exe
   -otshot.exe
   -Re-MarkablesX174.exe
   -sizlsearch.FirstRun.exe
   -sizlsearchUninstall.exe
   -SupraSavingsService.exe
   -uninstall_l.exe
   -unutil.exe
   -updatecrimsolite.exe
   -updatesizlsearch.exe
   -wdRe-MarkableO.exe

-Added the following baddies to "rmListDesktop.txt" file:
   -Live PC Help.lnk

-Added the following baddies to "uninstallPUP.txt" file:
   -Boost
   -Right Backup
   -YouTube Accelerator

-Added the following baddies to "uninstallPF.txt" file:
   -Consumer Input
   -EZ Software Updater
   -Mysearchdial\1.8.29.0
   --Re-Markable-soft

-Added the following baddies to "rmList.txt" file:
   -6E6B36EB-9156-411B-B951-C735F4747DCF
   -CoUpScanneR
   -crimsolite
   -focusbase
   -install_clap
   -LLuCekyShopPear
   -LucekyCOupoen
   -OtShot
   -sizlsearch

-Added the following baddies to "rmPUP.txt" file:
   -boost_interprocess
   -Flash Player Pro
   -PC Health Kit



v0.4.5

-Updated definitions for all compatible portable malware scanners

-Added the following baddies to "processList.txt" file:
   -SearchDonkey.exe
   -SearchDonkey64.exe
   -SearchDonkeyService.exe
   -SearchDonkeyUpdate.exe

-Added the following baddies to "rmList.txt" file:
   -SearchDonkey

-Added "scan-bin.cmd" to "/scripts/" for scanning EXE, DLL, SCR, and other binary files for known malicious bytes or patterns

-Added "detect-false-uninstallers.cmd" to "/scripts/" to detect whether an "uninstall.exe", "uninst.exe", or similar file actually triggers an uninstall routine, or if it tricks the user into updating itself or some other malicious task



v0.4.4

-Updated "Norton Removal Tool" to v21.0.0.14

-Fixed "Double Launching" issue with Spybot and ClamWin. This will also handle any other scanners that have this issue

-Fixed closing issue with Spybot after updating definitions

-Updated definitions for all compatible portable malware scanners

-Changed the order of some menu items. Manual Malware Removal is now the 1st option, followed by Malware Scanners

-Renamed "Manual Malware Uninstall Mode" to "Manual Malware Removal" under main menu options

-Added "%windir%\Temp", "%systemdrive%\Temp", and "%windir%\system32\config\systemprofile\AppData\Local\Temp" to "Clean Temp Folders" and "View Temp Folders" menu options



v0.4.3

-Updated definitions for all compatible portable malware scanners

-Added "Seagate SeaTools" to Diagnostics menu

-Added "Dump EXE Names From Target" under Manual Malware Removal -> Other Scripts

-Added the following baddies to "rmList.txt" file:
   -Object Browser
   -Select-N-Go-soft

-Added a huge list of baddies to "processList.txt" file. This is thanks to the new scripting to pull EXE names from folders



v0.4.2

-Added "rmListStartMenu.txt", "rmListStartMenu.txt", and "rmListStartMenu.txt" to "/scripts/lists/". These are used by the rmLoop script to remove baddie shortcuts placed in the Start Menu

-Added the following baddies to "processList.txt" file:
   -WebCakeDesktop.exe

-Added the following baddies to "uninstallADR.txt" file:
   -Move Networks

-Added the following baddies to "uninstallPF.txt" file:
   -FastAgain PC Booster
   -Playbryte

-Added the following baddies to "rmPUP.txt" file:
   -Ask.com
   -Extreme_Flash_Player
   -freegames111
   -Funmoods
   -Mobogenie
   -OpenCandy
   -StormAlerts
   -TornTV.com
   -Yontoo

-Added the following baddies to "rmList.txt" file:
   -BabSolution
   -buenosearch LTD
   -ConduitEngine
   -CyberDefender
   -DealSuggester
   -DesktopDialer
   -DriverCure
   -Earth Networks
   -FreeHDSport TV
   -FreeHDSport.TV
   -FunWebProducts
   -GamesBar
   -getsavin
   -HDPlayer
   -ihelper
   -ihelper2014
   -Ilivid Player
   -Iminent
   -IminentToolbar
   -iWebar
   -MixiDJ_V44
   -MyTechGurus
   -newnext.me
   -NexGenMediaPlayer
   -PageRage
   -PC Cleaner
   -PerformerSoft
   -Plus-HD-7.7
   -SearchProtect
   -Search Results Toolbar
   -SaveSense
   -SaveSenseLive
   -searchresultstb
   -SecretSauce
   -SevereWeatherAlerts
   -Smartbar
   -SolidSavings
   -SoftCoup
   -speedtest4354
   -SweetIM
   -Swift Browse
   -SySaver
   -systweak
   -Tepfel
   -TuneUp Software
   -Video-Saver-soft
   -Web Layers
   -weDownload
   -Websteroids
   -WhiteListing
   -WinRST
   -YVAvyxyk



v0.4.1

-Fixed path error in rmLoop script for AppData\LocalLow

-Added "rmListDesktop.txt", "rmOEMDesktop.txt", and "rmPUPDesktop.txt" to "/scripts/lists/". These are used by rmLoop script to remove baddie shortcuts placed on all desktops

-Added the following shortcut removals to "rmListDesktop.txt" file:
   -DRIVERfighter

-Added the following shortcut removals to "rmPUPDesktop.txt" file:
   -WeatherBug

-Removed "suprasavings" from uninstall-loop. The reference to the "uninstall.exe" was not actually triggering an uninstall routine. It has now been added to the "rmLoop.txt" list

-Added the following baddies to "rmList.txt" file:
   -browsersafeguard

-Added the following baddies to "rmPUP.txt" file:
   -AWS

-Added the following baddies to "uninstallPF.txt" file:
   -fst_us_95
   -SmartMediaConverter
   -V-bates

-Added the following baddies to "processList.txt" file:
   -DRIVERfighter.exe
   -FightersTray.exe
   -FighterSuiteService.exe
   -SmartMediaConverterApp.exe
   -updateScanTack.exe
   -vxlsnyaiet64.exe



v0.4.0

-Updated help menu, kinda ;)

-Added "pwn" variables that issue "take ownership" commands before file removal for rmLoop script

-Added Security Essentials removal tools for v1.x and v2.x to the MSE AV Cleaning module

-Changed "SafeMSI" behavior. Now it launches only if Safe Mode is detected to turn on MSI Installer Service

-Added user interaction for both "uninstall-loop" and "rmLoop" scripts for PUP (Potentially Unwanted Programs) targets to ask the user if this is something they want removed before executing on each run



v0.3.9

-Added a Help menu item. It is located on the main menu only and is currently only a placeholder

-Changed the "Exit Window" menu option from simply exiting the script to now going to the end of the script so invoke cleanup and other tasks can be performed

-Added "Hibernate", "Logoff", "shutdown", and "abort shutdown" to Reboot Options menu

-Added the following baddies to "rmList.txt" file:
   -AntiMalware
   -BigFix
   -Bofo
   -Fast Browser Search
   -FunWebProducts
   -Gameztar Toolbar
   -GetRightToGo
   -glindorus
   -Hotbar
   -KGyGaAvL
   -Move Networks
   -MyWebSearch
   -net1_sys32
   -ooVoo
   -PING_sys32
   -RelevantKnowledge
   -ScorpionSaver
   -Search Guard Plus
   -Search Guard PlusU
   -SIFXINST
   -Spigot
   -wlanext_sys32
   -Zero G Registry

-Added the following baddies to "rmPUP.txt" file:
   -Merscom
   -MSN Toolbar
   -MSN Toolbar Installer

-Added the following baddies to "uninstallPF.txt" file:
   -Automated Content Enhancer
   -Content Management Wizard
   -Dogpile Bundle Toolbar
   -ooVoo Toolbar
   -Pando Networks Media Booster
   -ParetoLogic FileCure
   -Web Search Operator

-Added safe mode status on top of main menu and re-organized other stats

-Added "check-safe-mode.cmd" to "/data/scripts". This allows the PCL to check if the current machine is in Safe Mode or not and take the appropriate actions going forward

-Added "rmOEM.txt" and "uninstallOEM.txt" for removing general OEM crapware. This is scripted to ask the user if this is something they want removed before executing on each run



v0.3.8

-Fixed problem with main menu not refreshing itself if no selection is made and ENTER is pressed

-Added "Microsoft Fixit Portable" and "Windows Registry Repair" to Maintenance menu

-Added "regdllview", "regfromapp", "regscanner", "speccy", and "unknown-device-identifier" to Diagnostics menu

-Added the following baddies to "rmList.txt" file:
   -003
   -AmiExt
   -Bench
   -CompuClever
   -Crawler
   -ddeal2dealit
   -Driver Restore
   -fassurun
   -GuffinsEI
   -GUM5282.tmp
   -Maps4PC_0c
   -Maps4PC_0cEI
   -MediaBuzzV1
   -PackageTracer_69
   -pcreg
   -RichMediaViewV1
   -Savings Wizard
   -SmileyCentral_1vEI
   -SqueakyChocolate
   -VeriBrowse-soft
   -WeatherBlinkEI
   -WolfQuest
   -Worldwide Web Research

-Added the following baddies to "processList.txt" file:
   -MyFasterPC.exe

-Added the following baddies to "uninstallPF.txt" file:
   -BlitzMediaPlayer
   -HiDefMedia
   -My Faster PC
   -PC Driver Kit
   -PC Speed Maximizer
   -PC Speed Up
   -SearchSnacks


v0.3.7

-Added "log cleaning" that silently runs on launch and exit to clean leftover log files by some tools

-Added "Kaspersky" and "Security Essentials" to "AV Cleaners" menu

-Switched the "view" and "clean" temp folder options around on main menu

-Added the follwing baddies to "rmList.txt" file:
   -Level Quality Watcher
   -SavingsbullFilter
   -Social Privacy  DNS

-Added the following baddies to "uninstallPF.txt" file:
   -Perk Prize Panel

-Added the following to "rmPUP.txt file:
   -The Weather Channel



v0.3.6

-Added Operating System stats on the top of main menu

-Removed the pause after rmloop script finishes. This was used in testing and I forgot to remove it

-Added hidden keywords that can be typed at the main menu to access features that are in testing and/or dev options that may be eliminated in a future update. Currently, the only keywords are "showdeviceoptions" which is a command line device manager, but it has not been scripted to fully function yet, the only working option currently is "Open Device Manager". The other keyword is "colortest", which is simply just that. I will be using a text based format to store keywords so they can be easily added or removed for different purposes.

-Added "rmList.txt" and "rmPUP.txt" to "/data/scripts/lists/". These are used by the rmLoop script for cleaning leftover directories and files

-Added the following baddies to "rmList.txt" file:
   -AskTBar
   -Better-Surf
   -BonanzaDealsLive
   -BuzzSearch
   -Deluge
   -Free Offers from Freeze.com
   -Inbox.com
   -My.Freeze.com Toolbar
   -OfficeGuardian
   -Play Pickle
   -ShoppingReport
   -ShoppingReport2
   -SweetPacks_A10
   -TelevisionFanaticEI
   -WebexpEnhancedV1
   -Win 7 Security 2012
   -WinZip Registry Optimizer

-Added the following baddies to "rmPUP.txt" file:
   -Freeze.com

-Added the following baddies to "uninstallPF.txt" file:
   -AppGraffiti
   -Dogpile Bundle Toolbar
   -Inbox Toolbar
   -PCPowerSpeed
   -RebateInformer
   -SuperLyrics-1
   -WebexpEnhancedV1
   -weDownload Manager Pro

-Added the following to A/V Cleaners menu:
   -Comodo
   -ESET
   -F-Secure
   -HouseCall
   -IOBit
   -OneCare
   -Panda
   -Trend Micro
   -Vipre
   -Webroot

-Moved "AVG SafeGuard toolbar" and "AVG Secure Search" from "uninstallPF.txt" to "uninstallPUP.txt"



v0.3.5

-Added "My Pictures" to Backup menu. This one seemed obvious and was missed ;)

-Fixed some menu text in various areas

-Changed default destination for PCL clone to "%SystemDrive%" (ex. C:)

-Added "Auto Open Folder" to backed up folder after backup is complete

-Added default path to be "%SystemDrive%:\backup" (ex. C:\backup) for Backup menu

-Fixed directory backup option. Now invoking "takeown.exe" to take ownership before copying files

-Fixed "rmloop" script. It now reads the same text files as the "uninstall-loop" script and takes only the root folder as a variable for removal (ex. "C:\Program Files\SearchProtect\Main\bin\uninstall.exe" reads as "C:\Program Files\SearchProtect\") 

-Re-organized main menu. Split into groups and color coded to make navigation a bit easier

-Added TeamViewer to utilities menu



v0.3.4

-Updated CCleaner to v4.14.4707.

-Added 64-bit version of CCleaner to "/data/modules/maintenance/ccleaner.pcl" archive. The script will auto-select the appropriate one to launch, so the end user will notice no difference

-Added "Recovery" option to main menu

-Added Recuva to Recovery menu. Both 32-bit and 64-bit versions were added and use the same style scripting as CCleaner to launch

-Added "Unstoppable Copier" to Recovery menu

-Added "system Explorer" and "svchost Analyzer" to Diagnostics menu

-Added "Double Driver" v4.1.0 GUI version to utilities menu as a selectable option

-Added "Clone PCL" to main menu. This option will clone all PCL files to another destination

-Added A/V cleaners to main menu. These include Avast Cleaner, AVG Removal, and Norton Removal Tool

-Added "devcon.exe", "devcon64.exe", "devconxp.exe", and "devconxp64.exe" to "/data/bin/. These will be used for handling device driver issues

-Added "2k3-support-tools" to "/data/bin/". These will be picked through and will use any files that are appopriate for the PCL



v0.3.3

-Added backup options for all common user data paths. These include "My Documents", "My Music", "My Videos", "Desktop", etc. There are currently 3 different options to choose from, these include "File/Folder Backup", "Archive Backup (zip, rar, 7z)", and "ISO Backup (.iso)"

-Sorted and removed duplicates from "scripts/lists/processList.txt"

-Updated definitions for all compatible portable malware scanners

-Rewrote code for "uninstall-loop" script. It now uses external text files that can be updated easily

-Added the following lists to "/scripts/lists/" for uninstall-loop:
   -uninstallPF.txt ("Program Files" and "Program Files (x86)" Directories)
   -uninstallCF.txt ("Program Files\Common Files" and "Program Files (x86)\Common Files" Directories)
   -uninstallPD.txt (ProgramData Directory)
   -uninstallADL.txt (AppData/Local Directory)
   -uninstallADLL.txt (AppData/LocalLow Directory)
   -uninstallADR.txt (AppData/Roaming Directory)
   -uninstallPUP.txt (Other software that is considered generally unwanted)

-Sorted and removed duplicates from "scripts/lists/uninstallPF.txt"

-Color-coded each uninstall loop path with a different color to easily see where the directory changes

-Added the following baddies to "scripts/lists/uninstallPF.txt" list:
   -24/7Help
   -4Diskclean
   -Activeris AntiMalware
   -Advanced File Optimizer
   -Anyplace Control
   -AVG Secure Search
   -BetterSurfPlus
   -blekkotb
   -BonanzaDeals
   -Coupons
   -Crawler Toolbar
   -DealPly
   -FileKiddo Download Manager
   -File Type Helper
   -FoodBuzz
   -free ven
   -media enhance
   -Mega Browse
   -Movies Toolbar
   -Mysearchdial
   -Optimizer Elite Max
   -Plus-HD-1.3
   -RegClean Pro
   -searchresultstb
   -SparkTrust PC Cleaner Plus
   -SpeedUpMyPC
   -sweetpacks bundle uninstaller
   -Updater By SweetPacks
   -WhiteSmoke_New

-Added the following to "scripts/lists/uninstallPUP.txt" list:
   -Frostwire5
   -PC Health Kit
   -The Weather Channel App

-Added "Take Ownership" to right-click context menu on launch, and removal from context menu on exit

-Added "checkbits" and "checkos" scripts for checking OS version and CPU architecture



v0.3.2

-Added a right-click option to add/remove for Unlocker under "Manual Unlock Script", for deleting stubborn files
-Fixed IE reset window not closing after resetting
-Fixed Purge Restore Points window not closing after execution



v0.3.1

-Removed MAC files and split the PCL into 3 separate projects for Windows, Linux, and Mac OSX
-Changed default dependency files directory from "data\files\" to "data\bin\"
-Updated text on Malwarebytes Anti-Malware to inform user of actions to take if it tries to update application



v0.3.0

-Added support for Mac OSX
-Added Avast, Avira, ClamXav, Comodo, eScan, MacScan, and Sophos apps to "/osx/cleaning/"
-Added CCleaner to "/osx/maintenance/"
-Added "Get Handles From Running Applications" to manual malware removal menu



v0.2.9

-Split Utilities into Diagnostics, Maintenance, and Utilities
-Re-organized diagnostics, maintenance, and utilities directories, and sorted applications based on main function
-Added "purge-system-restore-points.cmd" to /scripts. This one is self-explanatory



v0.2.8

-Added menu option under manual removal to apply various fixes and tweaks
-Added option for custom commands under manual removal
-Added "My Documents" and "Downloads" to the list of common folders
-Removed the "unlock-loop" reference from menu until stable



v0.2.7

-Added "MSISafe.exe" for uninstalling MSI installers from Safe Mode. This is used for the "Baddie Uninstall Loop" under manual malware removal
-Updated common folder paths under manual malware removal
-Changed text when unpacking a PCL module to be more suiting


v0.2.6

-Added option under manual removal to open common folders where malware like to hide.
-Updated some display text



v0.2.5

-Added "unlock-loop.cmd" to /scripts. This tries to unlock baddies in a loop
-Added "Junkware Removal Tool" to standalone scanners
-Added Global Variables to better handle specific issues with extracting PCL modules across different types



v0.2.4

-Added "Malwarebytes Anti-Exploit" and "Malwarebytes Anti-Rootkit" to standalone scanners. Currently only sandbox installed and repacked
-Updated path variable names to use a pathCleaning, pathDiagnostics, pathScanners, etc style
-Added "unlock-manual.cmd" to /scripts. This gives the user the option for file/folder input, and unlock/delete options



v0.2.3

-Added a message box before launching the main menu with important pre-release text
-Fixed PCL modules not unpacking properly from utilities menu
-Added Free Uninstaller, Cleanup!, and Clean After Me to utilities menu
-Added "unlocker" to bin files. This uses the command line for unlocking and force deleting baddies



v0.2.2

-Added OverDisk, and CoreTemp to "utilities" menu.
-Added "recovery" to "/data/modules/"
-Added GMER and TDSS Killer to standalone scanners



v0.2.1

-Fixed path issue with packing PCL modules
-Added text files under /scripts/list/ for listing and keeping track of specific directory/file baddies used for rmloop script
-Added standalone scanners to the menu. Listed as Rootkit Scanners and Other Tools



v0.2.0

-Added "rmloop.cmd" to /scripts. This will aid in cleaning up known baddies in a recursive directory loop removal
-Added CCleaner, Autoruns, Process Monitor, and Process Explorer to "utilities" menu.
-Added "maintenance" to "/data/modules/"



v0.1.9

-Added "utilities" to the main menu
-Added a "temp fix" for Spybot not launching properly. The folder now opens and you can manually select scan or update



v0.1.8

-Updated baddie list for "uninstall-loop.cmd"
-Added "diagnostics" to "/data/modules/"
-Added "sfcscan.cmd" tp /scripts. This will be used to verify system files. Currently not included in menu options
-Added Microsoft Security Essentials and AVG Free Antivirus to cleaning. Currently only sandbox installed and repacked



v0.1.7

-Added ie reset scripts for version 6 and higher of Internet Explorer to restore default settings
-Added a "temp fix" for ClamWin not launching properly. The folder now opens and you can manually select scan or update
-Added "checkuac.cmd" to /scripts. This will be used to help determine UAC status and disable as necessary



v0.1.6

-Added "dump-all-locations.cmd" to /scripts. This will export all known commonly abused and uninstall registry paths to .REG files.
-Added "fix-msi-installer-removal-bug.cmd" to /scripts. This fixes a well known problem with uninstalling MSI installers
-Added "flip-bit-mode.cmd" to /scripts. This is used to switch between x86 and x64 paths automatically, after a run during the uninstall loop
-Added Update and Repack option to Cleaning menu scanners. This will update, repack, and copy back to source media



v0.1.5

-Added "browser-loop.cmd" to /scripts. This will run through a loop of common browser exe names and terminate them. The file "lists/browserList.txt" can be updated with new EXE names
-Added paths for 32-bit and 64-bit Program Files directories for uninstall-loop script



v0.1.4

-Added "tkloop.cmd" to /scripts. This will run through a loop of known baddies and terminate the process. The file "lists/processList.txt" can be updated with new EXE names
-Fixed Malwarebytes not launching in default GUI mode
-Added "uninstall-loop.cmd" to /scripts. This will run through a recursive loop of baddie uninstall strings and try to remove the offending applications
-Fixed ClamWin "freshclam.exe" problem when launching from script



v0.1.3

-Added scripts to the main data folder
-Added "data/registry/" path to include various registry tweaks and fixes that can be applied through menu
-Added Scan and Update options to Cleaning menu for each scanner
-SuperAntiSpyware Free Edition sandboxed and made portable via file manipulation and scripting techniques
-Added ClamWin Portable. Using portable package from portableapps.com



v0.1.2

-Malwarebytes Anti-Malware sandboxed and made portable via file manipulation and scripting techniques
-Sophos Antivirus sandboxed and made portable via CLI and nircmd
-Added data/config.ini to be used to track scanner and utility version number, file names, and more.
-Added "utilities" to "/data/modules/"



v0.1.1

-Emsisoft sandboxed and made portable via CLI and scripting techniques
-Panda Antivirus sandboxed and made portable via CLI and scripting techniques
-Added "nircmd.exe" to bin files. Used for a ton of stuff / Link
-Added "wget.exe" to bin files. Used for downloading updates
-Added "rar.exe" to bin files. Used for packing and unpacking PCL Modules (rar archives)



v0.1.0

-Initial Version
-Avira Antivir sandboxed and made portable via CLI (Command Line Interface) and scripting techniques
-BitDefender sandboxed and made portable via CLI and scripting techniques
-RemoveIt Pro sandboxed and made portable
-Spybot Search and Destroy sandboxed and made portable
-Added "cleaning" to "/data/modules/"





Version History (Linux)
--------------------------

v0.1.0

-Initial Version