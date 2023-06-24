# Quasar

[![Build status](httpsci.appveyor.comapiprojectsstatus5857hfy6r1ltb5f2svg=true)](httpsci.appveyor.comprojectMaxXorquasar)
[![Downloads](httpsimg.shields.iogithubdownloadsquasarQuasartotal.svg)](httpsgithub.comquasarQuasarreleases)
[![License](httpsimg.shields.iogithublicensequasarQuasar.svg)](LICENSE)

Free, Open-Source Remote Administration Tool for Windows

Quasar is a fast and light-weight remote administration tool coded in C#. The usage ranges from user support through day-to-day administrative work to employee monitoring. Providing high stability and an easy-to-use user interface, Quasar is the perfect remote administration solution for you.

## Screenshots

![remote-shell](Imagesremote-shell.png)

![remote-desktop](Imagesremote-desktop.png)

![remote-files](Imagesremote-files.png)

## Features
 TCP network stream (IPv4 & IPv6 support)
 Fast network serialization (Protocol Buffers)
 Encrypted communication (TLS)
 UPnP Support (automatic port forwarding)
 Task Manager
 File Manager
 Startup Manager
 Remote Desktop
 Remote Shell
 Remote Execution
 System Information
 Registry Editor
 System Power Commands (Restart, Shutdown, Standby)
 Keylogger (Unicode Support)
 Reverse Proxy (SOCKS5)
 Password Recovery (Common Browsers and FTP Clients)
 ... and many more!

## Download
 [Latest stable release](httpsgithub.comquasarQuasarreleases) (recommended)
 [Latest development snapshot](httpsci.appveyor.comprojectMaxXorquasar)

## Supported runtimes and operating systems
 .NET Framework 4.5.2 or higher
 Supported operating systems (32- and 64-bit)
   Windows 11
   Windows Server 2022
   Windows 10
   Windows Server 2019
   Windows Server 2016
   Windows 88.1
   Windows Server 2012
   Windows 7
   Windows Server 2008 R2
 For older systems please use [Quasar version 1.3.0](httpsgithub.comquasarQuasarreleasestagv1.3.0.0)

## Compiling
Open the project `Quasar.sln` in Visual Studio 2019+ with installed .NET desktop development features and [restore the NuGET packages](httpsdocs.microsoft.comen-usnugetconsume-packagespackage-restore). Once all packages are installed the project can be compiled as usual by clicking `Build` at the top or by pressing `F6`. The resulting executables can be found in the `Bin` directory. See below which build configuration to choose from.

## Building a client
 Build configuration          Usage scenario  Description
 ----------------------------------------------------------
 Debug configuration          Testing         The pre-defined [Settings.cs](Quasar.ClientConfigSettings.cs) will be used, so edit this file before compiling the client. You can execute the client directly with the specified settings.
 Release configuration        Production      Start `Quasar.exe` and use the client builder.

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md)

## Roadmap
See [ROADMAP.md](ROADMAP.md)

## Documentation
See the [wiki](httpsgithub.comquasarQuasarwiki) for usage instructions and other documentation.

## License
Quasar is distributed under the [MIT License](LICENSE).  
Third-party licenses are located [here](Licenses).

## Thank you!
I really appreciate all kinds of feedback and contributions. Thanks for using and supporting Quasar!
