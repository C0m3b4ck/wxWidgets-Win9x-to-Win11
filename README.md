

<a href=https://github.com/C0m3b4ck/wxWidgets-Win9x-to-Win11/blob/main/README_PL.md>🇵🇱🇵🇱🇵🇱🇵🇱🇵🇱POLSKA WERSJA🇵🇱🇵🇱🇵🇱🇵🇱🇵🇱🇵🇱</a>
<br>![GitHub All Releases](https://img.shields.io/github/downloads/C0m3b4ck/wxWidgets-Win9x-to-Win11/total)
<br><b>🇪🇺🇪🇺🇪🇺Made in Europe🇪🇺🇪🇺🇪🇺
# wxWidgets-Win9x-to-Win11
wxWidgets 2.8.8 compiled for all versions from Windows 95 to Windows 11.
I made this because I plan to use wxWidgets in future projects.
# Instructions
<h2><b>Required:</b></h2>
<pre><code>wxMSW 2.8.8, found here: <a href=https://github.com/wxWidgets/wxWidgets/releases/tag/v2.8.8>https://github.com/wxWidgets/wxWidgets/releases/tag/v2.8.8</a></code></pre>
<pre><code>DevC++ 5.11 with TDM GCC 4.7.3 (GCC needs to be below 4.9)</code></pre>
<pre><code>OPTIONAL: after installation, register DevCPP\MinGW\Bin to PATH</code></pre>

<h2><b>Commands:</b></h2>
<h3>Step 1: Navigate to correct directory</h3>
<p>Go to <code>wxwidgets-folder-name\build\msw</code></p>

<h3>Step 2: Clean after previous build</h3>
<pre><code>mingw32-make -f makefile.gcc BUILD=release clean</code></pre>

<h3>Step 3: Build</h3>
<pre><code>mingw32-make -f makefile.gcc BUILD=release SHELL=CMD.exe SHARED=1 UNICODE=0 MONOLITHIC=0 CXXFLAGS="-fpermissive"</code></pre>

# Supported OSes
<b>Supports all versions of Windows, from Windows 95 up to Windows 11:</b>

    Windows 95

    Windows NT 4.0

    Windows 98 

    Windows 98 SE

    Windows 2000

    Windows Me

    Windows XP (tested: x86, x32 and 64-bit, Home, Professional, includes: Starter, Tablet PC, Media Center, Embedded)

    Windows Server (all versions including 2003, Small Business Server 2003, 2003 R2, Home Server,
    2008, Small Business Server 2008, 2012, 2012 R2, 2016, 2019, 2022, 2025)

    Windows Embedded versions, including: Windows Embedded for Point of Service, Windows Embedded Standard 2009, Windows Embedded POSReady 2009

    Windows Vista

    Windows 7

    Windows 8

    Windows 8.1

    Windows 10

    Windows 11

    (probable future desktop OS from Microsoft)

# Author
Original link here: <a href=https://github.com/wxWidgets/wxWidgets/releases/tag/v2.8.8>https://github.com/wxWidgets/wxWidgets/releases/tag/v2.8.8</a>

