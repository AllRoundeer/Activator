			KMSAuto Net 2016 Portable от Ratiborus,
                                       MSFree Inc.

       		                 Системни изисквания: 
                          —————————————————————————————————
VL-редакции: Windows Vista, 7, 8, 8.1, 10, Server 2008, 2008 R2, 2012,
2012 R2, Office 2010/2013/2016.



       		                      Описание:
                          —————————————————————————————————

KMSAuto Net - автоматичен KMS-активатор за операционни системи
Windows VL-версии: Vista, 7, 8, 8.1, 10, Server 2008, 2008 R2, 2012,
2012 R2, 2016, а также Office 2010, 2013, 2016.

Допълнително програмата активира:
	Windows 8.1 Single Language;
	Windows 8.1 Core;
	Windows 8.1 Core N;
	Windows 8.1 Pro WMC;
	Windows Embedded 8.1 Industry Pro;
	Windows Server 2012 R2 Standard;
	Windows Server 2012 R2 Datacenter.
Базиран на KMS Server Service от mikmik38 (MDL)



       		                 Работа с програмата:
                          —————————————————————————————————
Стартирайте файлът KMSAuto Net.exe и използвайте интерфейса. Включете
професионалния режим на работа на програмата, ако са ви нужни допълнителни настройки.
Копчето за пускане/изключване на професионалния режмим на работа се намира върху
"About" - бутонът с дракончето.
Най-простия начин за ползване на програмата е да се използва в автоматичен режим.
От Вас се иска само да натиснете копчето за активация и да се съгласите
за създаването на планирана задача за реактивация чрез натискане на копчето.

Съвет: първо трябва да се активира Windows и Office в ръчен режим, и чак след това, когато
сте сигурни, че активацията е преминала, да създадете планирана задача за реактивиране на всеки 25 дни.
Ако системата въобще не иска да се активира, преминете в Професионален режим
и чрез бутона "Utilites" опитайте принудително да инсталирате GVLK-ключ за вашата версия
на Windows и отново опитайте да активирате.

         		    
          		    Допълнителна информация:
                          —————————————————————————————————
За активацията на Windows 8.1 непосредствено е необходимо да се пусне ТАР мрежов адаптер
и да се използва IP-адрес 10.3.0.2-254, или да се използва специален драйвер. Всичко това е 
вградено в програмата.
За активация по локална мрежа  ТАР-интерфейса може да не се стартира, а да се ползва за 
активация мрежовият адрес на компютъра.
Ако сте пренастройли програмата и тя е престанала да работи нормално, изпълнете пункта от менюто
"Reset the program". Всички настройки се зануляват.


			Допълнителни параметри на програмата (ключове/switches):
                          —————————————————————————————————
/win=act	- Стартира програмата в тих режим, активира Windows и изключва програмата.

/off=act	- Стартира програмата в тих режим, активира Office и изключва програмата.

/log=yes	- Стартира програмата в тих режим, създава файл ActStatus.log и изключва програмата.

/kmsset=yes	- Стартира програмата в тих режим, стартира KMS-Service и изключва програмата.
		  Това е само KMS-Service, без TAР, WinDivert, Hook.
/kmsdel=yes	- Стартира програмата в тих режим, премахва KMS-Service и изключва програмата.

/key=yes	- Стартира програмата в тих режим, инсталира Windows ключ и изключва програмата.

/task=yes	- Стартира програмата в тих режим, създава планирана задача за Windows и Office
		  активация на всеки 25 дни и изключва програмата.

/taskrun=yes	- Стартира програмата в тих режим, изпълнява планираната задача за Windows и Office
		  активация и изключва програмата.

/convert=	- Стартира програмата в тих режим, подготвя изпълнение за конвертиране на версията
		  на Windows и изключва програмата.

/sound=yes	- Включва звуците.
/sound=no	- Изключва звуците.


                          —————————————————————————————————
Активацията ще бъде изпълнена спрямо настройките, заложени в бутона KMS-Service.


                          —————————————————————————————————
При пренасяне на програмата на друг компютър трябва да се ресетне Auto Mode.
Активацията пак ще е автоматична, но режимът може да не е оптимален за новия компютър.
За завръщане на автоматичният режим режим в първоначално състояние трябва да се превключи на всеки
друг режим и след това отново да се избере автоматичен режим.


		   Начините на активация, вградени в програмата:    
                          —————————————————————————————————
Програмата активира чрез вградения в нея KMS-server по няколко различни начина.
Защо са няколко?: стандартния начин за свързване към сървъра за активация през
localhost (127.0.0.2-254) е блокиран в Windows 8.1. За това всякакви претенции...
Всички използвани методи за активация са предназначени да излъжат системата и тя
да си "мисли", че KMS-сървърът не е на вашия компютър, а някъде из мрежата.


                          Накратко за режимите на програмата:
                          —————————————————————————————————
Auto		- Програмата автоматично се опитва да намери начинът за активиране, който
		  най-добре подхожда за вашата система. Правят се опити за активиране на
		  системата или Office чрез всички допустими за вашата система начини.
		  И начинът, който успее да активира, се запомня от програмата.
		  За завръщане на автоматичният режим в първоначално състояние трябва да се
		  превключи на всеки друг режим и след това отново да се избере Auto.
		  Този режим е заложен в програмата по подразбиране.

Hook		- Методът се базира на подмяна на оригинален файл от системата на
		  специално променен такъв. След активация оригиналния файл се връща на мястото.
		  В новите версии на програмата този метод се изпълнява без подмяна на файлове:
		  всички операции се изпълняват в паметта.

WinDivert	- В системата по време на активация се създава специален драйвер, който емулира
		  отдалечено включване към KMS-сървър.

NoAuto		- Това е режим без никаква автоматика: както го настроите, така ще работи.
		- Това е за хора, които по-добре от мен знаят какво, как и кога трябва да се направи,
		  и трябва ли да се прави. :)

ТАР		- Системата е виртуално устройство. ТАР-активацията преминава през виртуалното
		  устройство. Програмата включва два драйвера за ТАР-адаптер. Ако вече имате
		  инсталиран един от драйверите, програмата ще използва другият и вашият драйвер
		  остава цял и непокътнат.


*		- Имена на режимите в бутонът System. Представляват хиперлинкове, чрез които може
		  да се променят някои настройки.


				Параметри на KMSSS.exe
                          —————————————————————————————————
Command Line Parameters:
  -Port <Port Value> - KMS Port. Range from 1 to 65535
         -PWin <PID> - Windows PID
         -PO14 <PID> - Office 2010 PID
         -PO15 <PID> - Office 2013 PID
      -AI <Interval> - Activation Interval. Range from 15 to 43200 minutes
      -RI <Interval> - Renewal Interval. Range from 15 to 43200 minutes
              -Debug - Detailed info.
                -Log - Log file Enabled.
		 -IP - Show IP address Clients Computers.
        -Hwid <HWID> - Machine Hardware Hash.


                          —————————————————————————————————
Програмата изисква наличието на .NET Framework 4.5
За нормална работа на програмата понякога трябва да се добави файлът KMSSS.exe
в изключенията на вашият антивирус, или да се спре антивирусът по време на активация.

Понякога KMS-Service не се инсталира правилно. Причините може да са различни.
Трябва 2-3 пъти да се изпълни "Removing KMS-Service" и да се рестартира компютъра.
При работа с програмата през флашка има смисъл да се отметне тикчето "Save 
settings in the program folder". В този случай файлът с настройки ще се съхрани в папката
на програмата, а не в C:\Users\username\AppData\Local\MSfree Inc.

                          —————————————————————————————————
KMS Log Analyzer.xlsm от предните версии не е съвместим с KMS Server Service v1.1.7.
За да се съхранят старите записи, трябва да се пренесат в новия KMS Log Analyzer
чрез copy-paste функцията.

			  "I wasn't able to activate!!!"
                          —————————————————————————————————
Perhaps you have a non VL product, not intended for activation of KMS-Service, for instance 
Windows 7 Ultimate can't support KMS activation, or your antivirus blocks the activation.
If an antivirus is the culprit you can do the following: in the "System" tab click on the 
blue label "KMS-Service" and in the window that appears remove the check mark. Then add the 
folder to exceptions in your antivirus program.


                          —————————————————————————————————
Искам да благодаря на mikmik38. Без неговата работа тази програма би била невъзможна.

На Hotbird64 - за неговия KMS Client, Evgeny972 и на хората от forum.ru-board.com 
за доброволната помощ и тестване на многобройните версии на програмата.

                                                                Ratiborus



Changelog:
v1.4.9
-Added Keys for Windows Server 2016 Essentials.
-KMS Server Service v2.0.3.

v1.4.8
 -Added Keys for Windows Server 2016.

v1.4.7
 -New KMS-Service.

v1.4.6
 -Added Keys for Windows 10 and Office 2016.

v1.4.5
 -Fixed minor bugs.

v1.4.4
 -Small changes in program code.

v1.4.3
 -Small changes in program code.

v1.4.2
 -Changes in program for compatibility with antivirus software.

v1.4.0
 -Added: Conversion from Office 2016 Mondo.

v1.3.9
 -Conversion from Office 2016 Word, Excel, Access,
  OneNote, OutLook, PowerPoint, Publisher RETAIL to VL.

v1.3.8
 -Fixed: mapping display buttons when the font is enlarged to 125%.
 -Added: Display the license expiration date (180 days 0 hours 0 minutes).
 -Added in "Other utilities" restore system files from the disk with your 
  version/edition of Windows.


v1.3.7
 -Fixed: Encoding readme_ru.txt.
 -Added readme.txt in the Bulgarian language.
 -Utility to save activation MSActBackUp v1.0.8.

v1.3.6
 -Updated program ProduKey v1.70 to v1.80.
 -Fixed: Setting keys for Office 2016.
 -Fixed: The task in the scheduler runs every 10 days.


v1.3.5
 -Updated ProduKey v1.66 to v1.70.
 -New TAP driver to support Windows 10. A random IP address is used and when the activation fails check box is cleared.
 -Re-compiled KMS Service. So antivirus software will not detect it as threat/false positive.
 -Included utility MSActBackUp.
 -Added Keys for Windows 10 and Office 2016.
 -Conversion from Office 2016 RETAIL to VL.
 -If Office is not installed, the button "Activate Office" is disabled.
 -In the "About" tab you can find a link to a page with my programs.
 -Added program for Windows 10 "Show or hide updates"

v1.3.4
 -Changes in program for compatibility with antivirus software.

v1.3.3
 -The program, when attempting activation of Office 2013 RETAIL converts the license channel 
  of OfficeProPlus, VisioPro, ProjectPro on Windows 7, 8, 8.1, 10 to KMS client.

v1.3.2
 -Small changes to the interface, added compatibility with Windows Technical Preview.
 -Now the program has French interface, thanks to coleo.
 
v1.3.1.b4
 -Added function that runs the script from heos(ru-board.com).
  This script searches for installed but outdated update Office 2010/2013 
  and makes it possible to remove them.

v1.3.1.b3
 -Added function for switching language interface.
 
v1.3.1.b2
 -Fixed bug when working with command line parameters creating a scheduled task.

v1.3.1.b1
 -Added support to activate Windows Technical Preview, Windows 10.

v1.3.0
 -Added support to activate OEM editions: "Windows 8.1 Single Language with Bing",
  "Windows 8.1 with Bing" and   "Windows 8.1 Pro for Education"
 
v1.2.8
 -ProduKey program updated from v1.65 to v1.66.
 -Replaced SppPatcher in the Hook SECO Injector method.
 -Eliminated an error that displays "Activation interval" in ES, VI, UA transfers.
 
v1.2.7
 -To view the log in the activation program now KMS Log Analizer.xlsm is integrated.
 -The computer should have an application installed to view .xlms files (MS Excel).
 -Work on adapting the program to the new format of the log file performed by Bort_Nick,
  forum.ru-board.com.
 -New KMS Server Service (KMSSS.exe) v1.1.7.
 -Expanded list of systems for converting edition.
 
v1.2.6.1
 -Changed the way "Program Information" button works on the "About" tab.
 -Fixed the nonworking "Get ePID and Hwid KMS-Service" button.
 
v1.2.6
 -Fixed a problem with key installation after executing the command "slmgr.vbs /upk".
 -To avoid detection from antivirus modules, driver files are password protected. 
  Moreover, is imperative to add to exclusions the following folders:
  %SYSTEMDRIVE%\ProgramData\KMSAuto\*.* 
  %SYSTEMDRIVE%\ProgramData\KMSAutoS\*.* 
  %TEMP%\KMSAuto\*.*
  %TEMP%\PDK\*.*
  
v1.2.5
 -When activation fails a message is displayed and an attempt is made to set 
  a GVLK forcibly.
 -Added option to disable Task Scheduler which monitor user actions.
 
v1.2.4.1
 -Fixed bug when working with command line parameters creating a scheduled task.

v1.2.4
 -Activating in Auto mode starts using Windivert method.
 -In the TAP method the TAP adapter is not re-installed.
 
v1.2.3
 -Activation functions are optimized for Windows and Office.
 -Fixed minor bugs.
 -Changed the "Utilities" tab. Added "KMS Client by Hotbird64"
 -New KMSSS.exe supporting installation Hwid KMS-Server.

v1.2.2
 -Fixed date and time displayed in hexadecimal format in the log file. 
 
v1.2.1
 -Added the utility from ShowHideControls miXOnIN. To convert Systems Editions. 
 -In Professional Mode, Advanced tab, the button "Convert Office RETAIL to VL". 
  Runs on Windows 8-8.1, doesn't work on Windows 7!.
 -New KMSSS.exe supporting installation Hwid KMS-Server.
  
v1.2.0
 -Changed the "Settings" tab.
 
v1.1.9.b1
 -Updated program for ProduKey v1.62 v1.65
 -Added the choice of Activation intervals of 10 and 20 days.
 -Installing GVLK Key at "Utilities" tab, works through slmgr.vbs.
 -Changed setting keys function for "Unsupported Product" (so reports WMI OS).
 -Added the program KMS Log Analyzer, for easy viewing and conservation of
  information of the log file from KMS-Service. The computer must have installed 
  an application for working with files .xlsm (MS Excel). Not ready yet!

v1.1.7 ? v1.1.8
 -Small changes in the program interface. Added a link to a video.
 -In "Auto" mode the program starts searching for a solution with the correct IP address.
 -Fixed a rarely occurring bug related to the inability to delete files "Injector by deagles".
  Program could hang with the message "Installation Hook, Injector by deagles"
 -Activation functions are optimized for Windows and Office.
 -On the Utilities tab a button was added "Resetting the system is not valid."
  Carefully read the message that appears when you click on this button!

v1.1.6
 -Added the ability to reset the program to default values.
 -New containers for modules. Unpacking modules and drivers is faster.
 -Task scheduler creates tasks on behalf of the Administrator.
 -Deleting addresses from KMS Server is working correctly.
 -Fixed some minor bugs.
  *** Happy New Year 2014 ! ***

v1.1.4
 -Program settings can be saved in a folder containing the program.
 -All modules of the program can work from ProgramData or the folder containing the program.
 -Fixed minor bugs.

v1.1.2.b8
 -ProduKey program is integrated into the executable file.

v1.1.2.b7
 -Fixed bug accessing the folder.

v1.1.2.b6
 -Fixed a bug in the Scheduler.

v1.1.2.b4
 -In Auto mode, you can disable any method of activation.
 
v1.1.2.b3 
 -Hook method uses a modified SECO Injector. Works at Activation and Renewal intervals 
  and set own ePID.

 v1.1.2b2
 -Option to connect to the KMS server where Hook mode works without replacing files.
 -Added option in the task scheduler to create the task in the ProgramData\KMSAutoS path.

v1.1.1
 -Added activation method with temporary substitution of 8.1 files.

v1.0.9.1
 -Eliminating annoying bug with non-removed service TunMirror.

v1.0.9
 -Program requires .NET Framework 4.5 again, as per users request.
 -Dialog to change the product key appears only once per session with the program.
 -When the scheduled task executes, the KMS-Service is no longer removed from the system,
  if it was installed the first time.
 -New added NoAuto option to disable automatic loading KMS-Service during activation.
  Hence, if NoAuto then full NoAuto.
 -In Auto mode when the configuration switch is added, the analysis of the
  system will always begin from the start position, and not from the previously stored.
  This is convenient if the program is run on different computers.
 -Before activating the system editon is defined and if it is 8.1 then the classic way
  of local host activation is excluded.
 -Added a second type of TAP adapter to resolve the conflict with the already established TAP VPN.
 -WinDivert v1.1 has been applied, so not "incidents" result in BSOD on x86 systems.
 -Eliminate errors when in the file path a sign "&" (ampersand) is present.
 
v1.0.8
 -Added a setting to remove the WinDivert driver. To avoid a possible crashing of your
  system in a BSOD, the unconditional removal can be turned on.
  By default, the removal is made after reboot.
 -Added the ability to run the program with switches at the command line.
 
v1.0.8.b5
 -The program combines three ways to connect to the KMS server, first try automatic mode
  setting.

v1.0.7
 -New KMS Server Service (KMSSS.exe). Added function to display the IP 
  address of the client in the log file. More in KMSSS.txt
  
v1.0.6
 -New KMS Server Service (KMSSS.exe). More in KMSSS.txt
 -Cosmetic changes to the interface
 
v1.0.5
 -Log file that includes information about de client OS version.
 -Fixes the problem with the definition of a folder Sysnative.
 
v1.0.4
 -New KMSSS.exe, KMS Server Service.
 -KMS Service Log output in the specified folder.
 -Fixed some minor bugs :)
 
v1.0.3
 -Applied a modified KMS-Service. Allows for the use of each product your own ePID. 
  Including CSVLK from actual key.
 -Changed the installation and removal of TunMirror.
 -Changed the installation and removal of TAP interface.
 -Added support for activation of Core, Embedded Industry, Single Language, etc.

v1.0.2
 -Change the setting of TAP interface.
 -New feature for activation Backup / Restore.
 -Cosmetic changes to the interface.
 -Added the ability to create a task scheduler to activate.

v1.0.1
 -Added GVLK keys to Server R2.
 -Cosmetic changes to the interface.

v1.0.0
 -First release.