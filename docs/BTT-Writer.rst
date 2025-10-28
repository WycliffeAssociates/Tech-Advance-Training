.. |my-hamburger| image:: images/hamburger.*
    :height: 14pt

.. |wifi| image:: images/network.*
    :height: 14pt
    :width: 14pt

.. |ellipsis-v| image:: images/ellipsis-v.*
    :height: 14pt

##########
BTT-Writer
##########

BTT-Writer is the main software we use to prepare translation to be uploaded to WACS. It can be used during the translation process, and it can also be used to enter a translation that has already been done (for example, on paper). It can even be used for simple printing of translated material. The main reason we encourage people to use BTT-Writer, and to be clear on how it works, is that it works hand-in-hand with WACS.

In order to complete this section, you will need an **email address** that you can check while doing this work. (Of course, you will need some kind of Internet connection, too.)

If BTT-Writer will only be used off-line, i.e. there will not be any uploads or downloads, you don’t need an account on WACS, and you won’t need an email for this section. However, the full power of BTT-Writer is only realized when you upload your work to WACS for safe-keeping.

BTT-Writer can be downloaded from GitHub, at https://github.com/Bible-Translation-Tools/BTT-Writer-Desktop/releases/latest. If you are using an Android device, the most recent version is in the Google Play Store. (See below.)


BTT-Writer Desktop and BTT-Writer Android work very similarly, but they are completely different programs. Most of this training is oriented towards use of BTT-Writer Desktop (which can be used on any computer that runs a recent version of Windows, macOS, or Linux). Where there are differences for BTT-Writer Android, we will try to make note of them. **If you notice something in the documentation that is different than what is seen on Android, please contact the Help Desk.**

Every current version of BTT-Writer (including for Android) is available for download from Basic Translation Tools https://basictranslationtools.org.

.. admonition:: Lab 11: BTT-Writer Lab 1

    BTT Writer can be downloaded from many different places.

    1. If you want to download BTT-Writer without using the word “Bible” in your browser, which site should you use?
    2. If you want to be completely sure you have the newest version, which site should you use?
    3. Which site will allow you to download either the Desktop or the Android version of BTT-Writer?
    4. Before continuing the training, make sure you have downloaded the latest version of BTT-Writer

******************
Getting BTT-Writer
******************

Installing BTT-Writer on PC
===========================

There are several different versions of BTT-Writer available. BTT-Writer has versions for Linux, for macOS, and for Windows. In addition, the Windows version comes in both 32-bit and 64-bit versions. Most Windows computers sold in the last 5 years are 64-bit.

 - Installing on Linux https://youtu.be/8cj7Iwwc20c
  .. image:: images/linux-install-video.*
    :width: 0.75in

 - Installing on macOS https://youtu.be/Z2mv1uIAE6o

  .. image:: images/macos-install-video.*
      :width: 0.75in


 - Installing on Windows https://youtu.be/UbX-MIRks6c

  .. image:: images/windows-install-video.*
      :width: 0.75in

Git
---

The Windows installer installs git along with BTT-Writer. For Linux and macOS, you will need to install it separately. For macOS we recommend the open-source `git-scm` available from https://sourceforge.net/projects/git-osx-installer/. You can use Apple’s version of git, but the download is over 2GB, so unless you have that kind of data, it’s better to use `git-scm` if you can. The version of `git-scm` is `2.33.0` as of the writing of this manual, and it works on both Intel and Apple Silicon computers.

For versions of BTT-Writer before 1.4.0, macOS and Linux also need a custom .ssh/config file. **Updating to the latest version fixes this requirement.**

.. admonition:: Lab 12: BTT-Writer Lab 2

    1. When installing BTT-Writer for Windows, do you need to install git?
    2. When installing BTT-Writer for Windows, should you choose 64-bit or 32-bit?
    3. What is a reason not to use Apple’s version of git with BTT-Writer?
    4. Before continuing the training, make sure you have installed BTT-Writer on your device.

Installing BTT-Writer for Android
=================================

Starting with **Version 1.5.1**, BTT-Writer Android is again available on the Google Play Store. You can find it by searching for BTT-Writer, or you can use this link: https://play.google.com/store/apps/details?id=org.bibletranslationtools.writer.android

.. image:: images/writer-android-install-link.*
    :width: 0.75in

You can also download an **.apk** of the program that can be manually installed on an Android device. That is available here: https://github.com/Bible-Translation-Tools/BTT-Writer-Android/releases/latest or at **Basic Translation Tools** https://BasicTranslationTools.org

Because of changes required by Google, the new version of BTT-Writer will not automatically see your old projects — they must be imported. Also, if your Android device becomes inoperable, there will be no way to recover the translation data. It is no longer in an easy-to-access place. Look at the section on :ref:`Exporting<Exporting>` to learn how to upload to WACS.

**There is no version of BTT-Writer for iOS (iPhone or iPad).**

.. admonition:: Lab 13: BTT-Writer Android

    1. I found BTT-Writer in the Google Play Store. Should I install it from there?
    2. I found BTT-Writer in the Apple iTunes Store. Should I install it on my iPad or iPhone?
    3. What is a good place to get BTT-Writer for Android?
    4. If you are going to be using BTT-Writer on Android, you should install it before continuing this course.

Updates to BTT-Writer
=====================

If you want to be notified when there is a new version of one of our programs, the easiest way is to “watch” the download site. This way, you will receive an email when there is a new release.

You do need to have an account on Github in order for them to know where to send the notification, but this account is free.

Please note that if you live in a place where your work is dangerous or illegal it is possible for others to discover which projects you are watching. Be mindful of what is needed for your safety.

We also have a newsletter that you can subscribe to where we mention new releases of BTT-Writer, and they are also mentioned in the Telegram channel.

**BTT-Writer for Android will notify you like all other Android updates when one is available, if you install from the Google Play Store.**

.. admonition:: Lab 14: Updates

    1. How can you be notified when there is an update to BTT-Writer?
    2. What would be a reason not to watch a project on GitHub?

************************************
How Do I Get Help to Use BTT-Writer?
************************************

We have many videos to help on the MAST Tech Talk channel on YouTube: https://www.youtube.com/@masttechtalk1916

We also have many helps at https://techadvancement.com

The Help Desk is always ready to help with questions and problems: helpdesk@techadvancement.com

Finally, we have an active help community on Telegram[^2]

.. admonition:: Lab 15: How Do I Get Help?

    1. What are three ways to get help for using BTT-Writer?

**************************
“Logging In” to BTT-Writer
**************************

.. image:: ./images/login-en.*

-  If you have already created an account on WACS, use the first option.
-  If you have not yet created an account on WACS, use the second option. Creating an account on WACS is explained :ref:`here<WACS>`

|wifi| Both of these options require an Internet connection, and will connect you to bibletranslationtools.org. If you need to hide this connection, be sure to connect a VPN before using one of these options.

- The third option can be used if there is no Internet available, but should always be temporary. For example, you can use it for a typist that you will collect the typing from manually, or if you are away from Internet temporarily. You should always log out before letting someone else use your computer. This allows them to enter their name into the “Contributors” of the project they work on, and keeps it straight where a project will be uploaded. It also protects your account from unauthorized uploads.

.. admonition:: Lab 16: “Logging In” to BTT-Writer

   1. If you have not yet created an account on WACS, you should do so before continuing with this training.
   2. Practice logging in with a WACS account, logging out, and then logging in with a “local account”.

Hamburger Menu (3 Dots) on Login Screen
=======================================

On the Login Screen, you can access the **Hamburger Menu** |ellipsis-v| to change the :ref:`Settings<Settings>`

********************
Important Agreements
********************

CC BY-SA
========

All of the content of BTT-Writer is either in the Public Domain or licensed with the Creative Commons license[^3]: https://creativecommons.org/licenses/by-sa/4.0/ This means that the translation does belong to the people who did the work, but they are making this translation openly available with few limitations. There are three restrictions on this license.

1. BY: Someone who uses the translation must say who he got it from. We call this “attribution”.
2. SA: Someone who uses the translation must make the end result available under the same license. This is called “share alike”.
3. The licensor cannot take away these freedoms as long as you follow the license terms.

.. admonition:: Lab 17: CC BY-SA

   1. What is a license?

   2. What does CC mean in our license?

   3. What does BY mean in our license?

   4. What does SA mean in our license?

Statement of Faith
==================

The Statement of Faith makes sure that we are all working together towards the same goal. While we have seen fruitful work in translation from non-believers, we don’t believe it’s best.

We insist that certain things are true, and not negotiable.

   1. The Bible is divinely inspired by God and has final authority. This means that we cannot impose our opinions or our culture on the content of the Bible.
   2. God is one and exists in three persons: God the Father, God the Son, and God the Holy Spirit.
   3. Because of the fall of man, all humans are sinful and in need of salvation.
   4. The death of Christ is a substitute for sinners and provides for the cleansing of those who believe.
   5. By God’s grace, through faith, people receive salvation as a free gift because of Jesus’ death and resurrection.
   6. The resurrection of all at the end of time — the saved to eternal life and the lost to eternal punishment.

.. admonition:: Lab 19: Statement of Faith

   1. What is the purpose of the Statement of Faith?

Translation Guidelines
======================

The Translation Guidelines state that a translation needs to be **Accurate**, **Clear**, and **Natural**. This is not normally something the technician needs to worry about, but it is part of the agreement to use the software.

Accurate
--------

Accurate translations effectively communicate the intended meaning of the original, divinely inspired text. An accurate translation expresses the meaning the author intended for the original audience in the original context.
1. To the extent that is possible, nothing is added, misconstrued, or deleted from the original message.
2. It does not recast the meaning of the original text to make it more relevant to the contemporary audience.
3. An accurate translation does not distort the meaning in order to favor a specific interpretive perspective. It should be free from theological, cultural, or personal biases.
4. An accurate translation communicates historical events and facts accurately.

Clear
-----

Clear translations will use whatever language structures are needed to help readers easily read and understand it.

1. A clear translation may use as many or as few terms as necessary to communicate the original meaning as clearly as possible.
2. Making a clear translation does not mean that the translator clarifies something that is ambiguous in the source text.
3. Making a clear translation does not mean that the translator gives the reader a specific interpretation for every passage where meaning is genuinely debated. ### Natural Natural translations use language forms that are reflect the way the target language is used in corresponding contexts.
4. Natural Bible translations sound like they were produced by an adult native speaker who speaks and/or writes well.
5. A natural Bible translation does not use expressions that are particular to their own culture in order to make the translation appear natural.
6. It is more important for a portion of Scripture to be translated accurately than for it to sound perfectly natural to everyone who reads it. We believe that a translation has the highest likelihood of being good quality when after applying the guidelines above, the following are completed:
7. It is tested and approved by believers of the language community and their church leaders.
8. Ongoing revisions and improvements are made.

.. admonition:: Lab 18: Translation Guidelines

    1. What are the three goals of the Translation Guidelines?

    2. What is the overall goal of the Translation Guidelines?

**********************
BTT-Writer Home Screen
**********************

.. image:: images/home-en.*
    :alt: Home Screen Image
    
① Logout is only used when a different translator is going to use the program, or to switch between on-line and off-line use. **You do not need to log out to use the program off-line.**

② Create a new project by clicking either the green button at the top right, or the Start a New Project button.

Once a project has been created, the project list fills in the space where the **Start a New Project** button is, so you can only use it for the first project.

③ The “3 dot” |ellipsis-v|, or “Hamburger”|my-hamburger|, menu, We will normally refer to the Hamburger menu as the 3 dot menu.

Occasionally, BTT-Writer will get confused about whether you’re logged in to WACS or not. If this happens (and you can’t upload) you can often fix the problem by clicking Logout (①) and logging back in again. You will need to click I Agree to the three agreements each time you log in. |wifi| Logging in uses your Internet connection.

.. admonition:: Lab 20: BTT-Writer Home Screen

   1. Do you need to log out if you are using BTT-Writer without Internet?

   2. What’s another name for the “3 dot” menu?

   3. What might cause you to need to log out?

Hamburger Menu (3 Dots) on Home Screen
======================================

.. image:: images/home-menu-en.*
    :align: left

- **Update** allows you to check for updates to Source Texts and Target Language Codes.
- **Import** allows you to import files from WACS, an exported Project File (``.tstudio`` file), a USFM File, or even a resource container for a new Source Text.
- `TranslationAcademy`_ is a translation manual that discusses the translation process, and how to evaluate a translation for quality.
- **Feedback** allows you to send an anonymous report to GitHub about BTT-Writer. Please note that because it is anonymous, unless you include your contact information in your message, you will not get a reply. These reports are lited here: https://github.com/Bible-Translation-Tools/BTT-Writer-Desktop/issues
- **Logout** is like the Logout option at the top of the screen.
- **Settings** gives access to many ways to customize BTT-Writer.

.. admonition:: Lab 21: Hamburger Menu

   1. Which option do you choose to change the user that is logged in?

   2. What option do you choose to customize BTT-Writer?

   3. What option do you choose to bring in a project from somewhere else?

   4. Which option opens a manual that teaches the translation process?

   5. Which option would you choose to get a new language code?

Update
------

.. image:: images/update-menu-en.*
    :align: right

- **Update List of Available Source Texts**
  - Check to see if there is a new GL in the catalog, or an update to a GL.
- **Download New index.sqlite**
  - Download a complete copy of the database.
- **Download Available Source Texts**
  - If there is an updated or new Source, this will let you choose what to download
- **Update List of Available Target Languages**
  - Check to see if there are any new language codes.

BTT-Writer Android has an additional menu option: **Check for Update to BTT-Writer**.

BTT-Writer keeps a database of available Source (**Gateway Language**, “GL”) Texts. The database also keeps a list of available **Target Language** codes, for translation projects. In addition, BTT-Writer stores **Source Texts** on your hard disk drive, ready to be used for a translation project. *Every time BTT-Writer is updated*, the new release will include all of the sources available at that time. It will also include all of the target language codes currently available. However, over time, new codes will be added, and sometimes language names will be spelled differently, although they keep the same codes.

The process to update the codes and Source Text versions can take a long time, and because it uses an |wifi| Internet connection, it can time out while you are trying to update. This can be very frustrating, so we have another choice for you.

Each week, a database file with all of the most up-to-date language codes and Source Text versions is posted online. **Download New index.sqlite** will download this database and simply replace your existing database. It could be out of date for as much as a week, but never more than that.

Every language in the world has a code to identify it as being separate from other languages. For example, we are currently aware of four languages called **“Kamba”**. One of them, in Kenya, has the code ``kam``. The related language in neighboring Tanzania has the code ``kam-TZ-kamba``. The languages in PNG and Brazil have the codes ``fad-x-kamba`` and ``xba``, respectively.

If a minority language does not yet have a code in our system, the translation project managers need to communicate with their supervisors to get the code added in PORT. Then, in a week or so, or after running the Update List of Available Target Languages, the new code will be available.

It is very important to use the correct code for the language. If you are unsure of what the code is, ask the project manager.

It can be helpful to ask this question before going to the translation event.

.. admonition:: Lab 23: Updates

  1. Updating the Source Texts is a two step process.

     1. What is the first step?

     2. What is the second step?

  2. Are the source texts or the language codes updated more often?

  3. If a new version of BTT-Writer has just come out, and you have installed the new version, will you need to update the source texts?

  4. If you are unable to run Update List of Available Source Texts or Update List of Available Target Languages, what can you do?

Update List of Available Sources
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. image:: images/update-list-sources-en.*

Updating Source Texts (GL) is a two-step process. It is not usually a good idea to change the content of the source text while translation is happening. (It makes it difficult to check.) Therefore, the first part of the update is to see what updates are available.

.. image:: images/no-new-sources-en.*
    :align: left
    :width: 45%

.. image:: images/132-new-sources-en.*
    :align: right
    :width: 45%

Once you have been notified that an update is available, you can see if it’s available for your current project when you select sources for that project.

If you choose Download Available Source Texts from the Hamburger Menu, you can select multiple books for download. However, available updates are not shown by green arrows here.

.. admonition:: Lab 24: Updating Sources

     1. Does checking for source updates automatically download them?

     2. How can you download updates for more than one book at a time?

     3. How can you check if an update is available for a particular book

Download Available Source Texts
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. image:: images/select-source-language-en.*

When updating Sources from the Hamburger Menu |ellipsis-v|, you are first asked to choose a language for the updates. Then, choose the Testament that you want to update. **Other** allows you to update translationWords, which is a resource for the whole Bible.

.. image:: images/select-testament-en.*
    :align: center

Within a Testament, you can choose individual books. Please note that this is by language, not by text. As a result, you can choose from multiple sources. Here, you can see both the **Unlocked Literal Bible (ULB)** and the **Unlocked Dynamic Bible (UDB)**. In Arabic, we have both the **Ketab El Hayat** and the **Van Dyke** translation available.

.. image:: images/select-book-version-en.*
    :align: center

|wifi| **All updates**, whether using the green arrow or the **Updates Sources** menu, use an Internet connection, will use Internet data, and will make a connection to bibletranslationtools.org. If it’s dangerous for you to visit that site, please use a VPN before updating the sources in BTT-Writer.

.. admonition:: Lab 25: Updating Sources Lab 2

   1. If you have just downloaded and installed a new release of BTT-Writer, do you need to update your sources?

   2. How many resources can be downloaded at the same time?

Download New index.sqlite
^^^^^^^^^^^^^^^^^^^^^^^^^

We’ve mentioned that BTT-Writer keeps a database of information about **Source Texts** and **Target Language codes**. Sometimes, because of poor Internet performance, it can be painfully slow to update the list of available source texts, or the list of available target languages. If you could just update the database, the download of the actual source files wouldn’t be too bad. (Note that this has become much faster in recent versions of BTT-Writer.)

Downloading a new **index.sqlite** replaces your existing database with a fresh copy from our servers. It is much faster than the other updates, however there are a couple of reasons to use the other methods.

- Specifically, the index.sqlite that is downloaded is only updated once per week, or so. Because of this, it may not have the most recent changes.

- Also, if you have made updates, the downloaded database may remove them, if the downloaded file is behind your local copy.

|wifi| **Downloading a new `index.sqlite`** uses an Internet connection, uses Internet data (although not much), and makes a connection to bibletranslationtools.org. If it's dangerous for you to visit that site, please use a VPN before updating the sources in BTT-Writer.

.. hint::
    :collapsible: closed

    You can copy the `index.sqlite` file from one computer or device to another. The file is located in the :ref:`Data Path<Data Path>` directory, inside the **library** directory.

.. admonition:: Lab 27: index.sqlite

  1. When should you download a new index.sqlite file?

  2. When should you hesitate to download the index.sqlite file?

Update List of Available Target Languages
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

When you update the list of Available Target Languages, BTT-Writer communicates with the server and compares the list of known languages with what is stored in the database in BTT-Writer.

|wifi| This uses an Internet connection, will use Internet data, and will make a connection to bibletranslationtools.org.

If it’s dangerous for you to visit that site, please use a VPN before updating the sources in BTT-Writer.

You will be notified whether language codes have been added or not.

Target language codes are updated very often, and it is much more likely that you will need to update target codes than source texts.

.. image:: images/target-added-en.*
    :align: center

.. admonition:: Lab 26: Updating Target Languages

  1. When should you use a VPN to update target languages?

  2. How often do target languages need to be updated?

Import
------

.. image:: images/import-menu-en.*
    :align: left

**Imports** are done from the Import menu on the Home Screen. *This menu is not available while editing a project.*

**Import from Server** allows importing from any account on WACS. |wifi|

**Import Project File** will allow you to import a `.tstudio` project file.

**Import USFM File** allows you to import a USFM file from BTT-Writer or another program.

**Import Source Text** allows importing a Source Text Resource Container. - You do not need to be logged in to WACS to import any of these things, although Import from Server will use |wifi| Internet data and will connect to bibletranslationtools.org.

.. admonition:: Lab 34: Imports

   1. When you collect or “harvest” a book from another computer, which import option will you use?

   2. Do you need an account on WACS to Import from Server?

   3. Which option do you use to import from a different translation program?

Import from Server
^^^^^^^^^^^^^^^^^^

.. image:: images/import-from-server-en.*
    :align: center

Import from Server will allow you to search the server for a project by User Name and/or by project name (here called “Book or Language”). On PC, *if you are logged in to WACS*, your user name will be filled in on the left side, and projects from your WACS account will fill in below. If you have many projects in your account, it will take some time before changes made to user name or book or language will be reflected. This is especially true if you have slow Internet. On Android, your user name is not filled in automatically.

Importing from the server and importing a project file are very similar. In both cases, git is used to preserve the change history of the project, and the manifest file that indicates which chunks have been closed and who the translators are (Contributors) is included.

.. admonition:: Lab 35: Import from Server

  1. What is the effect of being logged in to WACS when you select Import from Server?

  2. What can cause the initial search to take a long time?

Import Project File
^^^^^^^^^^^^^^^^^^^

Import Project File will open a standard file picker5 window that defaults to the Backups folder in your Backup Location (from the Settings). The only files that can be selected are `.tstudio` project files.

`.tstudio` files contain the standard project folder (from the data path) and a second manifest file with information about the project. All of this is zipped (compressed with the zip format) into another folder and given the file extension .tstudio.

While project files can be manually changed, it is an advanced technique and should not be attempted casually. A project can only be imported and exported from or to a project file if the project has a valid git history. The import/export process uses git to validate the data.

The “standard file picker” is different for every operating system. It is the window that your computer opens when it wants you to select a file for opening.

.. admonition:: Lab 36: Import Project File

    1. Where does BTT-Writer look for files when you Import a Project File?

    2. What file extension does BTT-Writer look for when importing a Project File?

Merging
^^^^^^^

When you import a project from the server or from a project file, sometimes you already have another copy of the same project on your computer. There are three elements of a project that define it. If only one or two of these elements are the same, the projects are considered different projects. However, if all three are the same, they are considered the same project, and you must either **Cancel, Merge Projects, or Overwrite Project**.

The three elements of a project are

  1. the Project Name (or Book of the Bible),
  2. the Type (which should almost always be text),
  3. and the Language Code.

With Bible translation, there are **66** different Projects (for the 66 books), **3** Types (Regular Text, ULB, & UDB), and many different language codes.

.. image:: images/three-project-elements-en.*
    :align: center

In the above example, the **Project Name** (3 John) is the same, and the **Language Code** is the same (Icelandic Sign Language: `icl`), but the **Type** is different (one is **reg** `Text`, and the other is **ULB**). They are considered *different* projects.

The only way to import a **3 John Icelandic Sign Language** project without some kind of conflict would be if the incoming project were **UDB**, the third *Type* of project.

If the two projects being merged have a *common git history* it is possible to merge them without any difficulty. Also, if the project being merged has *no chunks* in common with the other project, there will be no problem. The *git* software underlying BTT-Writer will add the changes to the *git history* for future reference, and everything will be put together nicely.

.. admonition:: Advanced Note
    :collapsible: closed

    The `manifest.json` file will *always* conflict between two project files, but BTT-Writer remakes the `manifest` so that you don't have to worry about it.

We will discuss handling merges and merge conflicts later, but note that this can only happen when importing from the server or from a project file.

Import USFM File
^^^^^^^^^^^^^^^^

Importing from USFM is slightly simpler than importing from a Project File or the server. **There is no merging.** But some information is not available in USFM. If a project already exists, BTT-Writer will ask for permission to **overwrite the existing project**. Although USFM import has improved over the years, some data, like the language code, is not preserved. It is not part of USFM. This data must be re-entered. Some data, like the translator names, can be tedious to re-enter. Project files, because they save the manifest file, save the level of completion of the project. USFM doesn’t know which chunks have been checked all the way.

- **USFM Import and Export should be done rarely.** Most of the time, Project File import export (or upload to the server!) is better.
- USFM Import and Export can be helpful when working with other programs, like Paratext or PTXPrint.

.. admonition:: What is USFM?

    USFM stands for Unified Standard Format Markers. It is a system for writing Scripture so that the content (meaning) of the words is kept separate from the format (way it is displayed). For example, you can buy Bibles that don't have verse numbers. These numbers are "part of" the received text, but they are *not* "part of" the content of Scripture. Moses and Paul did not write verse notes while they were writing. Those were added later to make it easier for people to find a specific passage and discuss it with one another.

    Most USFM markers start with a backslash (\\). There will generally be a space after the marker. Some markers need to be on their own line. Writing with USFM can be very complicated, so BTT-Writer handles most of it for us, and it also only supports a few different markers.

.. admonition:: Lab 42: USFM Import

     1. Are you able to merge text during a USFM Import?

     2. Does USFM keep all of the information about the project?

     3. When should you use USFM Import?

Import Source Text
^^^^^^^^^^^^^^^^^^

The most rare kind of import is the Source Text. Almost any time you need a new Source Text, you will get it from Updating the List of Source Texts, and then downloading the new text.

So, when do we use the Source Text Import?

You may go to an event where there is very poor Internet, and where you know the computers have an outdated version of the source. Then, you can side-load the source text to the computers using this. Or, you may work on a project for a language that uses a source that is not a Gateway Language. Sometimes, we get permission to use a text, but only for a specific country, or for specific work. In that case, you will get the Source Text in a resource container from Tech Advance, and you will import it using this option.

.. admonition:: Lab 43: Import Source Text

  1. What is the normal way to import a Source Text?

translationAcademy
------------------
**translationAcademy** is a collection of materials explaining the translation process, and giving examples of the best practices to use. While some translation teams may find this information useful or helpful, it is not part of the functioning of BTT-Writer.

Feedback
--------

.. image:: images/feedback-form-en.*

When you use the Feedback option on the menu, an **Issue** [#github_issue]_ will be created on GitHub for you. This issue will contain any text you type in the box, and also the contents of the *log file* that BTT-Writer keeps. This log file may contain useful information (like error messages) that will help us to understand and correct the problem. It may also contain your username, which will allow us to reply to you. However, if the log file does *not* contain any of your user information, you will not receive a response from us, because the Feedback is otherwise anonymous. If you want to receive a reply, be sure to include your email address in the Feedback text you enter in the box.

.. [#github_issue] https://github.com/bible-translation-tools/BTT-Writer-Desktop/issues

Logout
------
The **Logout** option does the same thing as the :ref:`Logout<BTT-Writer Home Screen>` option next to your username at the top of the screen.


Settings
--------

Interface Language & Basic Settings
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. image:: images/settings-1-en.*
    :align: center

The first three options in Settings are for the general operation of BTT-Writer.

① Starting in version 1.4.0, BTT-Writer is able to work in different languages.
    BTT-Writer (Desktop) is able to work in English, French, Spanish, Portuguese, Farsi, and Russian.

.. image:: images/crowdin.*
    :width: 0.75in
    :align: right

Unfortunately, BTT-Writer (or its ancestor, translationStudio) was not designed to be multi-lingual. This was very difficult to correct, and we have only recently finished changing the program to allow for different languages.
We are not yet done. Now that the program has been changed, we will need people to create the translations of the interface. For this, we use a site called CrowdIn (https://crowdin.com). If you are interested in helping us to put BTT-Writer’s menus in your language, contact helpdesk@techadvancement.com.

② **Gateway Language Mode** is only for making resources for GL translations. If you don’t know that you are working on a GL project, turn this off.
③ **Blind Edit Mode** enables additional features in BTT-Writer that support the Eight Step methodology. This should normally be on.

.. admonition:: Lab 44: Settings Lab 1

    1. For most projects, should Gateway Language Mode be on or off?
    2. For most projects, should Blind Edit Mode be on or off?
    3. How can you change the language that BTT-Writer uses for its interface?https://www.sphinx-doc.org/en/master/man/sphinx-build.html
    4. What can you do if your language isn’t yet available?
    5. Make sure that Gateway Language mode is off in your copy of BTT-Writer (unless you are working with a Gateway Language project).
    6. Make sure that Blind Edit Mode is on in your copy of BTT-Writer.
    7. If English isn’t your preferred language, look to see if BTT-Writer has your language available.


Fonts and Colors
^^^^^^^^^^^^^^^^

.. image:: images/settings-2-en.*
    :align: center

BTT-Writer supports light and dark mode Color Themes. If you select **System**, it will follow the light or dark theme of your operating system. ① You can set the **font** and **font size** for the **Target Translation** and ② have a different **font** and **size** for the **Source Text**. Some languages use a writing style that has the same letters as another, but is more readable in a different font, or at a different size. You can download fonts to your computer and use them in BTT-Writer, but **Android** requires a special build of the program to use a font that’s not part of the Android system.

If you need a special font when displaying a translation on BIEL, a special change needs to be made to the repository for that book. That’s an advanced topic that we’ll discuss later.

.. admonition:: Lab 29: Settings Part 2

    1. What options are available for Color Themes?

    2. What options are available for changing the fonts in BTT-Writer?

    3. What needs to be done to have a custom font in BTT-Writer for Android?

    4. Experiment in your copy of BTT-Writer with different color themes and font settings.


Backups and File Locations
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. image:: images/settings-3-en.*

① BTT-Writer automatically makes a backup every 5 minutes of the active project. It is saved to this location in a subfolder called *automatic_backups*. Backups are also made of every project when BTT-Writer first starts. If a project is broken and can’t be normally backed up, a zip file will be made of it and placed in the **automatic_backups** folder. (These are the folder names on Desktop. Android has special limitations, which can be discussed separately.)

When you export a project, it will default to this location, sometimes in a backups folder here.

② If you have problems with your BTT-Writer, we will ask you what **version** you are using. That information can be found here. (It’s also displayed when BTT-Writer first starts.) When a new version comes out, you can check to see if you are up to date.

③ The **git** version is also important, but we don’t ask for it as often.

④ This may be the most important item. BTT-Writer stores its working files in the **Data Path**. This is sometimes called the “happy path”.

⑤ Under **Legal** are copies of the **License Agreement**, **Translation Guidelines**, and **Statement of Faith** that were agreed to when the user logged in.

Under **Software Licenses** are the licenses for the various different software programs that are used together to make BTT-Writer.

.. admonition:: Lab 30: Settings Part 3

  1. If you save a file or export something, where should you look for it?

  2. If you want to find the automatic backup made of your project, where should you look?

  3. If you think a project is damaged, where should you look?

  4. If you want to see the working files being used by BTT-Writer, where should you look?

  5. How can you find the version of BTT-Writer you are using?

Advanced Settings
^^^^^^^^^^^^^^^^^

The **Advanced Settings** nearly all concern the |wifi| Internet servers used by BTT-Writer.

 - The **Server Suite** lets you switch all of the settings from WACS-facing to DCS-facing. DCS was a server that we previously used. We no longer use DCS.
 - The **Data Server** is WACS – where your data will be stored, and where you download *from* when you :ref:`Import from Server<Import from Server>`.
 - The **Media Server** is used under the hood by the program.
 - The **Reader Server** is where you will be able to read uploaded projects in a *presentation* format.
 - The **Create Account URL** is the address where :ref:`WACS<WACS>` accounts can be created.
 - The **Languages URL** is where the list of :ref:`Available Target Languages<Update List of Available Target Languages>` comes from.
 - The **Index.sqlite URL** is the address from which a complete `index.sqlite` file can be downloaded.

Finally, **Developer Tools** (on Desktop) will open another window on your screen showing debug information about BTT-Writer. A technician can sometimes use this information to fix a problem.

A Final Word About Language Codes
=================================

.. image:: images/french-codes.*
    :align: right

Language codes are either set by an International Standards Organization (codes like ``zh``, ``en``, or ``pt-br``) or by language researchers. Once a code is set for a language it should not be changed. The code is needed to uniquely identify the language. It is not intended to be the same as what the people call their language. In this example, Modern French uses the French name for the language, **français**, including the lower case first letter.

For the other versions of French, the English name is used, along with date information for older versions of French. If the French people decided that they wanted all of these languages to be labeled in French, they could contact Translation Services. The names would then be adjusted in PORT. However, the language codes would remain the same. **It is not the Tech’s responsibility to change a language name or code.**

.. admonition:: Lab 31: Language Codes

  1. Where does BTT-Writer get its language code information from?

  2. Who can change the information about a language in BTT-Writer?

  3. How can a language group change the code used for their language?

******************
Creating a Project
******************

When creating a translation project in BTT-Writer, first you must choose the target language. You can scroll down and select a language from the list, or you can start typing the name or the code of the language.

The best practice is to type the code. You should always have the code from the Project Manager before the typing begins. There are many languages in the world with the same name, but each language has only one code.

If, for some reason, you are forced to begin a project for a language that doesn’t have a code, try to pick a code that will be easy to spot and change later on. A sign language code is one suggestion, since sign language translations are done using video instead of BTT-Writer. *Icelandic Sign Language*, for example, uses the code ``icl``. If you don’t use the correct code for a language, you should always make a note. One place you can put a note that will stay with the project is in the **Contributors** field. Say something like, “Using icl code for Ugaritic language in Syria”. That way, it will be simpler for someone to fix the code later.

① The language name and ② code will be displayed as you are asked to choose a Testament to translate from. Finally, you will be able to choose a book to translate.

.. admonition:: Lab 32: Creating a Project

  1. What information do you need to know before you can begin a translation project?

  2. What is the best way to search for a language in the list?



Hamburger Menu |ellipsis-v| (in a Project)
==========================================

The Hamburger menu is context sensitive, which means that it shows different things at different times. We’ve just gone through all of the options it shows on the Home Screen. While working on a project, however, the Hamburger menu has additional options.

- **Home** will return the user to the Home Screen.
- **Upload/Export** is available under details for each project on the Home Screen.
- **Project Review** will be discussed under Finishing a Project.
- **Print** is just a different version of Export.
- **Search** allows searching for a particular group of letters in either the Source or Translation panes of BTT-Writer.
- **Mark All Chunks Done** will mark all chunks done if they contain text.

.. admonition:: Lab 22: Hamburger Menu 2, the Sequel

  1. The Print option is really just a version of what other option?

  2. Which option will allow you to search for a word?

  3. If you need to close all chunks in a project, how can you do that?

