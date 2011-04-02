Apple's CoreFoundation - Version 550.42
========================================

About
-----

This is Apple's CoreFoundation, as available from the Apple's website:
http://opensource.apple.com/source/CF/CF-550.42/

Apple does unfortunately not provide a direct download link, hence this repository on GitHub.

About CoreFoundation
--------------------

Source: Wikipedia

Core Foundation (also called CF) is a C application programming interface (API) in Mac OS X, and is a mix of low-level routines and wrapper functions.
Apple releases most of it as an open source project called CF-Lite that can be used to write cross-platform applications for Mac OS X, Linux, and Windows (via Cygwin);
Most Core Foundation routines follow a certain naming convention that deal with opaque objects, for example CFDictionaryRef for functions whose names begin with CFDictionary, and these objects are often reference counted (manually) through CFRetain and CFRelease. Internally, Core Foundation forms the base of the types in the Objective-C runtime as well.

The most prevalent use of Core Foundation is for passing its own primitive types for data, including raw bytes, Unicode strings, numbers, calendar dates, and UUIDs, as well as collections such as arrays, sets, and dictionaries, to numerous OS X C routines, primarily those that are GUI-related. At the operating system level Core Foundation also provides standardized application preferences management through CFPropertyList, bundle handling, run loops, interprocess communication through CFMachPort and CFNotificationCenter, and a basic graphical user interface message dialog through CFUserNotification.

Other parts of the API include utility routines and wrappers around existing APIs for ease of use. Utility routines perform such actions as file system and network I/O through CFReadStream, CFWriteStream, and CFURL and endianness translation (Byte Order Utilities). Some examples of wrapper routines include those for Core Foundation's wrapper routines for Unix sockets, the CFSocket API.

Some types in Core Foundation are "toll-free bridged", or interchangeable with a simple cast, with those of their Foundation Kit counterparts. For example, one could create a CFDictionaryRef Core Foundation type, and then later simply use a standard C cast to convert it to its Objective-C counterpart, NSDictionary *, and then use the desired Objective-C methods on that object as one normally would.

License
-------

Copyright (c) 2010 Apple Inc. All rights reserved.

This file contains Original Code and/or Modifications of Original Code as defined in and that are subject to the Apple Public Source License Version 2.0 (the 'License'). You may not use this file except in compliance with the License. Please obtain a copy of the License at http://www.opensource.apple.com/apsl/ and read it before using this file.

The Original Code and all software distributed under the License are distributed on an 'AS IS' basis, WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, AND APPLE HEREBY DISCLAIMS ALL SUCH WARRANTIES, INCLUDING WITHOUT LIMITATION, ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, QUIET ENJOYMENT OR NON-INFRINGEMENT.
Please see the License for the specific language governing rights and limitations under the License.
