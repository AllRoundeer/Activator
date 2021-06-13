
                        KMSAuto Net 2016 Portable 编写由 Ratiborus,
                                       MSFree Inc.

       		                    描述
                          —————————————————————————————————
KMSAuto Net - Windows 操作系统自动 KMS 激活程序。
支持 Windows Vista，7，8，8.1，10, Server 2008，2008 R2，2012，2012 R2, 2016, 
以及 Office 2010，2013, 2016 VL（卷许可） 版本。
基于在 mikmik38 (MDL) 的KMS Server Service 之上。

  
       		                 使用说明
                          —————————————————————————————————
请以管理员身份运行 KMSAuto Net.exe 。要调整附加设置，请开启本程序的专业
模式，请在 “关于 ” 标签内开启或关闭 专业模式。 

要激活 Windows 8.1，您必须安装 TAP 网络适配器并使用 IP  地址且驱动程序的版本号
必须为 10.3.0.2-254。这些都已经整合到了程序里。


	                              本程序的附加参数
                          —————————————————————————————————
/win=act	- 以隐秘模式运行本程序，激活 Windows 然后退出。
/off=act                - 以隐秘模式运行本程序，激活  Office 然后退出。
/log=yes	- 以隐秘模式运行本程序，创建文件 ActStatus.log 然后退出。
                          —————————————————————————————————
在  KMS 服务 标签内定义的设置是用于激活。


                          —————————————————————————————————
当您传输本程序到其它计算机上时，请复位 自动模式。
您仍然可在其它计算机上运行本程序以自动模式进行激活，但此时它并非初始状态。
要复位 自动模式 到初始状态，请先切换为其它模式，然后再切换回自动模式，现在
自动模式已处在初始状态了。


                          —————————————————————————————————
本程序需要 .NET Framework 4.5
要正常运行，请将执行文件 KMSSS.exe 添加到您的反病毒软件的白名单内。或
使用时临时禁用您的反病毒软件。

有时可能因为各种原因不能正确安装 KMS 服务。
需要执行 ” 移除 KMS 服务“ 并重启计算机 这两个动作 2-3 次。
                          —————————————————————————————————
                                                                 Ratiborus

更新日志：
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

v1.3.2
 -Small changes to the interface, added compatibility with Windows Technical Preview.
 -Now the program has French interface, thanks to coleo.

v1.1.7 ÷ v1.1.8
 -Small changes in the program interface. Added a link to a video.
 -In "Auto" mode the program starts searching for a solution with the correct IP address.
 -Fixed a rarely occurring bug related to the inability to delete files "Injector from deagles".
  Program could hang with the message "Installation Hook, Injector from deagles"
 -Activation functions are optimized for Windows and Office.
 -On the Utilities tab a button was added "Resetting the system is not valid."
  Carefully read the message that appears when you click on this button!

v1.1.4
 -Program settings can be saved in a folder containing the program.
 -All modules of the program can work from ProgramData or the folder containing the program.


v1.1.2.b3 
 -Hook method uses a modified SECO Injector. Works at Activation and Renewal intervals 
  and set own ePID.

v1.1.2b2
 -Option to connect to the KMS server where Hook mode works without replacing files.
 -Added option in the task scheduler to create the task in the ProgramData\KMSAutoS path.

v1.0.9.2
 -释放了简体中文版本。

v1.0.9.1
 -消除移除 TunMirror 服务时的错误。

v1.0.9
 -Программе снова требуется .NET Framework 4.5, по просьбам пользователей.
 -Диалог изменения ключа продукта появляется один раз за сеанс работы с программой.
 -При выполнении запланированного задания KMS-Service теперь не удаляется из системы,
  если на момент выполнения он был установлен.
 -В режиме NoAuto добавлена возможность отключить автоматическую загрузку KMS-Service
  во время активации. Уж если NoAuto - то полный NoAuto.
 -В режиме Auto добавлен переключатель при включении которого анализ конфигурации
  системы всегда будет начинаться со стартовой позиции, а не с запомненной ранее.
  Это удобно если программа запускается на разных компьютерах.
 -Перед активацией определяется редакция системы и если это 8.1 то классический способ 
  активации от локалхост исключается.
 -Добавлен второй тип TAP адаптера, для устранения конфликта с уже установленным TAP VPN.
 -Применён WinDivert v1.1, не "падающий" в BSOD на x86 системах.
 -Устранил ошибку когда в пути к файлу присутствует знак "&", амперсанд.

v1.0.8
 -Добавлена настройка удаления WinDivert драйвера. Кто хочет, у кого система 
  не "падает" в BSOD при безусловном удалении могут его включить.
  Но по-умолчанию настроено удаление после перезагрузки.
 -Добавлена возможность запуска программы с ключами из командной строки.

v1.0.8.b5
 -В программе совмещены три способа подключения к KMS Серверу, введён режим
  автоматической настройки.

v1.0.7
 -Новый KMS Server Service (KMSSS.exe). Добавлена функция отображения IP
  адреса клиента в лог файле. Подробнее в KMSSS.txt


v1.0.6
 -Новый KMS Server Service (KMSSS.exe). Подробнее в KMSSS.txt
 -Косметические изменения интерфейса.


v1.0.5
 -В лог файл включается информация о клиенте, редакция OS.
 -Устранил ошибку с определением папки Sysnative.

v1.0.4
 -Новый KMSSS.exe, КМС Сервер Сервис.
 -Лог выводится из папки установленного КМС Сервиса.
 -Устранил некоторые незначительные ошибки, без которых никак. :)

v1.0.3
 -Применён модифицированный KMS-Service. Позволяет для каждого продукта использовать
  свой ePID. В том числе и от реальных CSVLK ключей.
 -Изменена установка и удаление TunMirror.
 -Изменена установка и удаление TAP интерфейса.
 -Добавлена поддержка активации редакций Core, EmbeddedIndustry, Single Language и др..

v1.0.2
 -Изменена установка TAP интерфейса.
 -Новые функции сохранения/восстановления активации.
 -Косметические изменения интерфейса.
 -Добавлена возможность создать задачу для активации в планировщике.

v1.0.1
 -Добавил GVLK ключи для Server R2.
 -Косметические изменения интерфейса.


v1.0.0
 -Первый релиз.



