## What's New in Visual Studio 2022

Visual Studio 2022 has been in [preview](https://visualstudio.microsoft.com/vs/preview/) for a while now and is set to be released next month with [.NET 6](https://dotnet.microsoft.com/download/dotnet/6.0).

# Visual Studio 2022

What can we expect from this new release? I'll take you for a quick spin through some of the new features and the new look for Visual Studio 2022. This isn't a complete list, but a few of the things I'm excited about with Visual Studio.

# Hello 64 Bit


Believe it or not, Visual Studio has always been 32-bit. Though operating systems have been 64-bit for a long time, VS remained at 32. Where it matters is memory access. While running 32bit Visual Studio's main process (devenv.exe) can only access 4GB of RAM. This is perfectly adequate for most projects. Larger processes would push into virtual memory at this point.


![8iZbqhcv7.jfif](https://cdn.hashnode.com/res/hashnode/image/upload/v1650320665204/Naw5CexVM.jfif)

However, Microsoft is looking to the future and has rebuilt Visual Studio as a 64-bit application. The 4GB limitation is gone, and Microsoft tested this with a solution containing 1600 projects with over 300k worth of files. More than enough for the future.

Additional Templates


There are far more creation templates available for whatever you want to develop with.


![YDSoFpFB4.jfif](https://cdn.hashnode.com/res/hashnode/image/upload/v1650320692744/S7arWPD0A.jfif)

Whether you want to create JavaScript SPA applications, traditional .NET applications, or Azure apps you're covered here.


![xj5iECmu7.jfif](https://cdn.hashnode.com/res/hashnode/image/upload/v1650320712223/mbU-Zf_AJ.jfif)

# Hot Reloading


VS 2022 now provides support for "hot reloading" in .NET applications, so you can see your work changing in real time.

You can see your changes in real time, with [Web Forms](https://channel9.msdn.com/Shows/Visual-Studio-Toolbox/Web-Live-Preview), as well as many others such as WPF, .NET Maui, [ASP.NET](http://asp.net/), and more.

Why does this matter? It can rapidly speed up your development time. Watching changes instead of saving, compiling, and running can cut your cycle time down considerably, allowing you to develop faster.

You can get [more information about hot reloading here](https://devblogs.microsoft.com/dotnet/introducing-net-hot-reload/).

# Hello .NET 6


Although in preview now, .NET 6 will be released in November, and VS 2022 has full support for it and defaults to .NET 6 for new projects.


![gazMOaHfi.jfif](https://cdn.hashnode.com/res/hashnode/image/upload/v1650320812622/hT1LIRxBc.jfif)

If you'd like to learn more about .NET 6, here's [what is coming](https://devblogs.microsoft.com/dotnet/announcing-net-6-preview-7/).

# Intellicode AI Autocompletion


AI autocompletion is quickly becoming a part of every developer's toolbox. Products like [GitHub Pilot](https://copilot.github.com/), [TabNine](https://www.tabnine.com/), and others have been quickly developing smart AI autocompletion.


![bobn-vNN4.jfif](https://cdn.hashnode.com/res/hashnode/image/upload/v1650320889642/EBPvCa6fn.jfif)

Having this built into Visual Studio can help you make the right choices about your code quickly, as well as reduce repetitive tasks.

# .NET Maui


VS 2022 has full support for .NET 6 unified framework for web, desktop, and mobile applications. This includes .NET Maui.


![GvuEGYthu.jfif](https://cdn.hashnode.com/res/hashnode/image/upload/v1650320961647/2U9kKxdl1.jfif)

.NET Maui supports Windows, Android, macOS, and iOS. You can build applications in C# and deploy them anywhere. A lot of incredible work has gone into this technology over the years.

You can learn more [about .NET Maui here](https://docs.microsoft.com/en-us/dotnet/maui/what-is-maui).

# Conclusion

These are just a few of the features I'm excited about. I've been using Visual Studio 2022 for a while now, and I'm not sure if I'll change all my projects to it right away, but it has been very smooth and stable for me.

I'm excited about the .NET 6 and Visual Studio releases next month. We'll cover some more of the cool stuff coming in future articles.

If you use Visual Studio 2019, there is a great [selection of courses here](https://www.pluralsight.com/paths/visual-studio-2019?utm_source=allhandsontech&utm_medium=organic-web&utm_campaign=allhandsontech) to help you really get to know the IDE and leverage it for development.