In Build 2018, Microsoft Answered My Number One Request Since Windows 8

Windows 8 was made globally available nearly six years ago, in October of 2012, indisputedly becoming one of the most contraversial versions of Microsoft Windows operating system ever to be released. While most customers demanded the retrun of the Start menu and removal of the touch-first user interface (UI) from non-touch desktops and laptops--which made up of the majority of Windows 8 devices, I had a different request from Microsoft.

But let us be clear: I, too, wanted a resolution to the biforcated UI introduced with the OS, an interface which was at the heart of the Windows 8 controversy. However, in trying to look beyond the immediate problems of Windows 8, I saw a path that appeared to pave a very smooth transition to the Windows 8 app vision in the long term; a path, frustratingly, Microsoft showed no intent on taking at the time.

To my pleasent surprise, Microsoft announced what is essentially the path I have envisioned. The announcement answered the biggest feature request on to which I was holding for the past five plus years.

-----

When Windows 8 was announced, I was an enthuistic supporter of the new application development platform, named Windows Runtime (WinRT). WinRT aimed to solve some of the biggest gripes of Windows's native application platform, Win32, which was a result of the fact that the platform dates back to the early 90s.

WinRT, to my understanding, represented Microsoft's third big attempt at revamping the operating system's primary app platform, with .NET Framework's WinForms and WPF being the earlier efforts. These initiatives intended to allow Windows developers to transition to more modern ways to build applications for the operating system.

With WinRT, Microsoft took much of what it learned from past efforts, from what worked to what didn't. For instance, WinRT code could be native code, leveraing the full performance of the underlying hardware on which it runs. This is unlike WinForms, which ran on the Common Language Runtime (CLR) on top of Win32. WinRT apps also use visually rich user interface, hardware accelerated by DirectX and utilizing the Exendable Application Markup Language (XAML) for drawing the UI, an effort that started with WPF, released over half a decade before the launch of Windows 8.

WinRT seemed to be Microsoft's most ambitious of the attempts to transition away from Win32. The company had put the future of its entire operating system on the line this time by making WinRT the primary focus of Windows 8. Whereas in the past, the likes of WPF and WinForms were never able to become a the primary focus for an individual release of Windows. They ended up becoming an optional development platform, with Win32 continuing to remain the primary platform.

In addition to the aformentioned improvements, WinRT brought forth capabalaties that made applications more secure with technologies such as sandboxing, improved privacy by requring explicit user consent to use hardware such as the camera or microphone, and kept the system clean from left over cruft and causing the likes of so-called "DLL hell", which was one of issues that could result with the classic methods of installation of Win32 apps.

WinRT, on paper at least, appeared to be the miracle solution for all problems with Windows's platform we were looking for. But there was just one problem. We could only use WinRT to develop touch-first Universal Windows applications (UWP) that were limited in their capabilities and not fully optimized for non-touch devices at the time.

There were two major problems with this. First, the WinRT application platform interface (API) was brand new; so, it needed a relatively long time to fully mature, especially if it wanted catch up with the now multiple decades old Win32 API. As a result, it would quite literally be impossible for many developers to fully rewrite their existing complex Win32 apps merely by the fact that many of the functions such apps might have relied on could not be replicated on WinRT in any form. Second, it is logistically impractical ask a developer to rewrite their complex Win32 app to the completely new, WinRT platform, even if it were possible to do so, especially if the Win32 app had years of development. There is no sense in abandoning a fully working application and rewriting it from scratch just to be able to make use of some of the benefits of WinRT offered. Third, with WinRT APIs being resricted for use in Universal Windows apps that ran on a touch-first full-screen environment, visually seperated from the Windows desktop, most of the existing Win32 desktop apps would be unsuitable for the touch-environment when the apps were initially written with keyboard and mouse use in mind. For example, The Microsoft Visual Studio IDE was created with desktops and laptops in mind. It would be unwise to re-write the Visual Studio for a touch environment when most of its users use the IDE to develop software using keyboard and mice. As we see in the Visual Studio example, if Microsoft wanted to add some WinRT elemnts to the IDE, it would need to re-write the entire software for an environment is unsuitable for, even when we disregard the fact that such complex IDE software would be impossible to fully port to WinRT in the first place
 

-----

What I had hoped for over five years was that Microsoft didn't keep many of the advantages of the WinRT APIs exclusive to Universal Windows Platform apps. I always asked why did a developer have to abandon thier existing Win32 apps and rewrite their apps from scratch just so that they can use the modern Xaml-based UI in thier apps. Why couldn't I simply add, say, a dark theme in my Windows Froms application. Why did I have to be stuck with the ancient pixel-based bitmap rendering systems?

-----

I had been hoping that Microsoft would introduce a an update to the development platform that would allow any Windows application to use the new, modern, Xaml based user interface. I was hoping that I could take my old Windows Forms app and give it a UI facelift to llow the interface to be rendered with hardware acceleration using DirectX, which the UI for UWP apps do by default. I wanted to render the basic user interface elements using the vector based model rather than the bitmap based one that becomes blurry on higher density displays and that fails to scale to various sizes and resolutions.

UWP are able to run with perfect clarity, without becoming blurry when running on a device with multi monitor setup where each monitors have a different display resolution and density. The old GDI based UI is unable clearly render the user interface dynamically between the different monitors.

Why is it, so, that my WinFOrm app would be forced to use this ancient UI platform when a modern one, clearly, exists natively in Windows. Why would such a fantastic UI platform be restricted to the UWP apps only?

