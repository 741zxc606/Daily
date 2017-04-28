[Windows PowerShell Cookbook](http://www.reedbushey.com/86Windows%20Powershell%20Cookbook%203rd%20Edition.pdf)

[Learn Windows PowerShell3](https://endusercompute.files.wordpress.com/2015/07/learn-windows-powershell-3-in-a-month-of-lunches-don-jones-jeffrey-hicks.pdf)


# You have to solve the issue on the paralles desktop

## [Package Installation Instructions](https://github.com/PowerShell/PowerShell/blob/master/docs/installation/windows.md)
### MSI 
To install PowerShell on Windows Full SKU (works on Win8 and above - x64 based systems), download either the MSI from AppVeyor for a nightly build, or a released package from our GitHub releases page. The MSI file looks like this - PowerShell_6.0.0.buildversion.msi

There is a shortcut placed in the Start Menu upon installation.

* By default the package is installed to $env:ProgramFiles\PowerShell\

* You can launch PowerShell via the Start Menu or $env:ProgramFiles\PowerShell\powershell.exe

* Note: On Windows 8.1 / Windows 2012R2, ensure Visual C++ Redistributable for VS2015 is installed from [here](http://download.microsoft.com/download/9/3/F/93FCF1E7-E6A4-478B-96E7-D4B285925B00/vc_redist.x64.exe).

[影响C++开发者的Visual Studio 2015 的安装改变](https://blogs.msdn.microsoft.com/c/2015/07/28/cvisual-studio-2015/)

[最新支持的 Visual C++ 下载](https://support.microsoft.com/zh-cn/help/2977003/the-latest-supported-visual-c-downloads)
