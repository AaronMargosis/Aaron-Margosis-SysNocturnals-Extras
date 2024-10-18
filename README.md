# Aaron Margosis' SysNocturnals Extras

The **"SysNocturnals Extras"** are some binaries and tools that I published on my blogs at Microsoft that are no longer available
on Microsoft's blog platform, including LUA Buglight and the App Install Recorder scripts. I'm making them available, once again. (Note that the compiled tools do not include source code.)

Click on this repo's `Releases` to download the extras.

## SysNocturnals Extras

### LUA Buglight

`LUA Buglight` is a tool I wrote years ago while at Microsoft for identifying admin-permissions issues (a.k.a., "LUA bugs") in 
desktop applications. That is, it identifies the specific reasons that a particular application works only when run with 
administrative rights. The blog post that describes LUA Buglight is still online but the LUA Buglight download disappeared a few years ago. 
It's now available again.

[Online documentation about LUA Buglight](https://techcommunity.microsoft.com/t5/windows-blog-archive/lua-buglight-2-3-with-support-for-windows-8-1-and-windows-10/ba-p/701459)

### App Install Recorder blog post and scripts

`The Case of the App Install Recorder` is a troubleshooting case 
in _[Troubleshooting with the Windows Sysinternals Tools](https://www.microsoftpressstore.com/store/troubleshooting-with-the-windows-sysinternals-tools-9780735684447)_ in which
elaborate scripts take a Process Monitor trace of an application install and make it possible to replicate that installation without
the original installer program. It first appeared on my blog along with the scripts in a downloadable zip file. After migrating through 
multiple blog platforms, the blog post is still online, [kind of](https://techcommunity.microsoft.com/t5/windows-blog-archive/the-case-of-the-app-install-recorder/ba-p/701461),
but the many screenshots and illustrations are gone, as are the scripts. They're now back, here. The zip file contains the original HTML
(with all the embedded screenshots), and the original zip file containing the scripts.

(Since I wrote that post, there have been numerous improvements to Procmon that would probably improve this solution, particularly in distinguishing "write" from other
operations.)

### IEZoneAnalyzer

IEZoneAnalyzer is a tool I last worked on in 2015 for viewing and comparing Internet Explorer security zone settings, and for
determining to which zone a given URL is assigned. With Internet Explorer now long gone, IEZoneAnalyzer is of significantly 
less value than it had when I first published it, but I understand that IE's security zones are still relevant in some scenarios.

As with the attachments and other downloadable content from my old blogs, IEZoneAnalyzer has gone missing for a while. It's now
available here, along with its full documentation (Word doc).

The surviving original blog posts also document its purpose and usage, even with some screenshots:
* [IEZoneAnalyzer v3](https://learn.microsoft.com/en-us/archive/blogs/fdcc/iezoneanalyzer-v3)
* [IEZoneAnalyzer v3.5 with Zone Map Viewer](https://learn.microsoft.com/en-us/archive/blogs/fdcc/iezoneanalyzer-v3-5-with-zone-map-viewer)
* [IEZoneAnalyzer update: v3.5.0.5](https://learn.microsoft.com/en-us/archive/blogs/fdcc/iezoneanalyzer-update-v3-5-0-5)


