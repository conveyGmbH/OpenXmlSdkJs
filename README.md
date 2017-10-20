# Open XML SDK for JavaScript
This is a small JavaScript library that enables you to implement Open XML functionality. Interesting platforms are: In-browser applications using IE, Chrome, FireFox, and other browsers. 
- Server-side functionality using NodeJs. 
- Windows 8 'Store' applications that are written in HTML5 and JavaScript. 
- Word 2013 JavaScript Apps 
- SharePoint 2013 JavaScript Apps. 
- SharePoint 2010 JavaScript Web Parts.

# Usage
- Documentation and examples at Eric White's blog on [Open XML SDK for JavaScript](http://ericwhite.com/blog/blog/open-xml-sdk-for-javascript/)
- ECMA 376 Standards [Office Open XML File Formats](http://www.ecma-international.org/publications/standards/Ecma-376.htm)
- ISO/IEC 29500

# Release 1.01.02 (December 20, 2013)
Added new example, examp10-open-xlsx.html, which shows loading a spreadsheet from a template string, making a modification to it, and then enabling the user to save the generated spreadsheet locally.

# Release 1.01.01
Fixed an issue where UTF8 characters were not serialized properly if the XDocument for a part was not loaded.

# Release 1.01
Perf improvement - opens and saves in 50% of the time. 
Added support for loading and saving blobs. 
In distribution, replaced jszip.js, jszip-load.js, jszip-inflate.js, jszip-deflate.js 
Added support for asynchronous loading and saving of blobs, flatOpc, and base64 
Added FileSaver.js to the zip. 
Added four examples examp06-template-documents.html shows how to create a template document in string literals 
examp07-load-save-via-html5.html shows one approach to using HTML5 to open/save local documents 
examp08-load-save-via-html5-b.html shows a second approach to using HTML5 to open/save local documents 
examp09-open-base64-async.html shows asynchronous opening / saving of documents


# Release 1.0
Initial release.

# Acknowlegements
OpenXML is a rewrite of Open XML SDK for JavaScript (http://openxmlsdkjs.codeplex.com) by Eric White (http://ericwhite.com)

# License
Microsoft Public License (Ms-PL)

This license governs use of the accompanying software. If you use the software, you accept this license. If you do not accept the license, do not use the software.

1. Definitions

The terms "reproduce," "reproduction," "derivative works," and "distribution" have the same meaning here as under U.S. copyright law.

A "contribution" is the original software, or any additions or changes to the software.

A "contributor" is any person that distributes its contribution under this license.

"Licensed patents" are a contributor's patent claims that read directly on its contribution.

2. Grant of Rights

(A) Copyright Grant- Subject to the terms of this license, including the license conditions and limitations in section 3, each contributor grants you a non-exclusive, worldwide, royalty-free copyright license to reproduce its contribution, prepare derivative works of its contribution, and distribute its contribution or any derivative works that you create.

(B) Patent Grant- Subject to the terms of this license, including the license conditions and limitations in section 3, each contributor grants you a non-exclusive, worldwide, royalty-free license under its licensed patents to make, have made, use, sell, offer for sale, import, and/or otherwise dispose of its contribution in the software or derivative works of the contribution in the software.

3. Conditions and Limitations

(A) No Trademark License- This license does not grant you rights to use any contributors' name, logo, or trademarks.

(B) If you bring a patent claim against any contributor over patents that you claim are infringed by the software, your patent license from such contributor to the software ends automatically.

(C) If you distribute any portion of the software, you must retain all copyright, patent, trademark, and attribution notices that are present in the software.

(D) If you distribute any portion of the software in source code form, you may do so only under this license by including a complete copy of this license with your distribution. If you distribute any portion of the software in compiled or object code form, you may only do so under a license that complies with this license.

(E) The software is licensed "as-is." You bear the risk of using it. The contributors give no express warranties, guarantees or conditions. You may have additional consumer rights under your local laws which this license cannot change. To the extent permitted under your local laws, the contributors exclude the implied warranties of merchantability, fitness for a particular purpose and non-infringement.
