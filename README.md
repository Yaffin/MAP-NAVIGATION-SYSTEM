WinBGI Graphics Library
Overview
The WinBGI Graphics Library is a Windows-based implementation of the Borland Graphics Interface (BGI), which was originally designed for DOS environments. This library provides a set of functions for drawing basic graphics, handling mouse and keyboard inputs, and managing graphical windows in a Windows environment. It allows users to create graphical applications using standard C++.

Features
Drawing Primitives: Functions for drawing basic shapes such as lines, circles, ellipses, rectangles, polygons, and arcs.
Text Rendering: Functions for displaying and manipulating text in graphical windows.
Mouse and Keyboard Input: Functions to handle mouse clicks, keyboard input, and other user interactions.
Color and Fill Management: Support for various colors, fill patterns, and line styles.
Window Management: Functions to create, manage, and close graphical windows.
Double Buffering: Support for double buffering to prevent flickering during animations.
Image Handling: Functions for capturing, saving, and displaying images.
Requirements
Operating System: Windows 95, Windows NT 4.0, or newer.
Compiler: Compatible with the MinGW g++ compiler. For more information, visit WinBGI with MinGW.
Note: This library may not be compatible with 64-bit versions of Windows.

Installation
Download the Library: Download the WinBGI header (winbgi.h) and source files.
Include the Header: Include the winbgi.h header file in your C++ project.
Link the Library: Link the required libraries during the compilation process. Ensure that the Windows API is properly linked.
