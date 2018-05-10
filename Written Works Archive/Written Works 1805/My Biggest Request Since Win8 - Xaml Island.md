In Build 2018, Microsoft Answered My Number One Request Since Windows 8

Windows 8 was made globally available nearly six years ago, in October 2012, indisputedly becoming one of the most contraversial versions of Microsoft Windows operating system ever to be released. While most customers demanded the retrun of the Start menu and removal of the touch-first user interface from non-touch desktops and laptops--device form factors on which the majority of the copies of the operating system were installed, I had a different request from Microsoft. Make no mistake, I very much wanted a resolution to the biforcated UI introduced with the OS, a decision that is at the heart of the controversy. However, I saw a path that appeared to pave a very smooth transition to the app vision of Windows 8, a path, frustratingly, Microsoft showed no intent on taking.

To my pleasent surprise, Microsoft announced what is essentially the path I have envisioned. The announcement answered the biggest feature request on to which I was holding for the past five plus years.

-----

When Windows 8 was announced, I was an enthuistic supporter of the new application development platform, known as Windows Runtime (WinRT). WinRT aimed to solve some of the biggest gripes of the Windows's native application platform, Win32, which was a result of the fact that it dates back from the early 90s.

WinRT, to my understanding, represented to be Microsoft's third big attempt at revamping the operating system's primary app platform, with .NET Framework being its first attempt and WPF bieng its second. These initiatives intended to have Windows app developers eventually transition away from building Win32 apps into building apps on top of these apstraction layers.

WinRT seemed to be Microsoft's most ambitious of the attempts to transition away from Win32. The company had put the future of its entire operating system on the line this time by making WinRT the primary focus of Windows 8. Whereas in the past, the likes of WPF and .NET Windows Forms never were able to a focus of an individual release of Windows. They ended up becoming an optional development platform, with Win32 continuing to remain the primary platform.

-----

What I had hoped for over five years was that Microsoft didn't keep many of the advantages of the WinRT APIs exclusive to Universal Windows Platform apps. I always asked why did a developer have to abandon thier existing Win32 apps and rewrite their apps from scratch just so that they can use the modern Xaml-based UI in thier apps. Why couldn't I simply add, say, a dark theme in my Windows Froms application. Why did I have to be stuck with the ancient pixel-based bitmap rendering systems?

-----

I had been hoping that Microsoft would introduce a an update to the development platform that would allow any Windows application to use the new, modern, Xaml based user interface. I was hoping that I could take my old Windows Forms app and give it a UI facelift to llow the interface to be rendered with hardware acceleration using DirectX, which the UI for UWP apps do by default. I wanted to render the basic user interface elements using the vector based model rather than the bitmap based one that becomes blurry on higher density displays and that fails to scale to various sizes and resolutions.

UWP are able to run with perfect clarity, without becoming blurry when running on a device with multi monitor setup where each monitors have a different display resolution and density. The old GDI based UI is unable clearly render the user interface dynamically between the different monitors.

Why is it, so, that my WinFOrm app would be forced to use this ancient UI platform when a modern one, clearly, exists natively in Windows. Why would such a fantastic UI platform be restricted to the UWP apps only?

