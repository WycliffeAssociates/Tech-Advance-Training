PTXprint - PDF production
^^^^^^^^^^^^^^^^^^^^^^^^^

Basic steps - Use hamburger (3 lines) button to choose view (full view
showing) - Basic: choose layout, name configuration, add copyright and
license; save - Layout: choose page size, font size, columns, margins
(start with defaults) - Fonts & scripts: choose font - Body: start with
defaults - Header+Footer: select from options - Peripherals: select
Table of contents; toc1; fill in Variables and Values - Peripherals:
select Local Front Matter; click Edit (takes you to View+Edit) -
View+Edit: click Generate; choose Basic when printing a quick draft -
contact Scripture Access for assistance with Advanced FRT matter

PTXprint - Text Editing
^^^^^^^^^^^^^^^^^^^^^^^

PTXprint is not an editor. One needs to edit the underlying USFM files
in order to make changes in the printed PDF.

If you are using USFM exported from BTT-Writer make edits in Writer.
Then export the project again and save it in the appropriate My Paratext
9 Projects folder, replacing the original file that is there.

If PTXprint was open, close it and reopen it to make use of the updated
file. If you obtained USFM files from another source such as WA
Scripture Accessibility, editing is done in a text editor. Windows
Notepad is not recommended as it does not support searching with regular
expressions (regex).

There are several text editors to choose from. One recommendation is
Microsoft VS Code available at https://code.visualstudio.com/Download

**To edit USFM using a text editor:** - Close PTXprint. - Open the
appropriate USFM file from the My Paratext 9 Projects folder in VS Code.
- Make edits and save the updated file. - Open PTXprint. The project
will now use the updated file.

PTXprint - PDF reader
^^^^^^^^^^^^^^^^^^^^^

The output from PTXprint is viewed in a PDF reader. The file opens
automatically when compiling is completed.

Windows typically uses **Adobe Acrobat** as the default PDF reader. A
disadvantage of Acrobat is that open PDFs cannot be updated. In other
words, the file needs to be closed before printing from PTXprint again.
PTXprint will give a warning and halt printing until the PDF is closed.
**SumatraPDF** allows PDFs to be updated while they are open. It is
available at https://www.sumatrapdfreader.org/download-free-pdf-viewer.

For this to take effect, you will need to make SumatraPDF the default
app for the .pdf file type, at least while you are using PTXprint. This
is done in Windows settings. SumatraPDF can be used freely. It is
Windows only, so if you are using Linux you will need to use something
like **Okular** or **Evince**. Both of these support this feature in
**SumatraPDF**.
