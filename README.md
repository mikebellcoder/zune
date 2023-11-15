# zune
Items necessary to install Zune software on Windows 11

Install the Zune Software -> http://zuneupdate.com/resources/

Download and run ExecTI -> https://winaero.com/download-execti-run-as-trustedinstaller/

Type cmd into the filed and press OK

This will open up a new command prompt window.

In that window, copy and paste the following commands

copy C:\WINDOWS\System32\DriverStore\FileRepository\zune.inf_amd64_bae1a2a65e3c2cfb\en-US\ZuneCoInst.dll.mui C:\WINDOWS\system32\en-US\ZuneCoInst.dll.mui

pnputil /add-driver "C:\Program Files\Zune\Drivers\Zune\Zune.inf" /install

Your Zune should now be recognized by Windows 11.

------------
Source Codix
https://www.youtube.com/watch?v=rWbWZt_T34w
