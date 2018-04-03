# Gettting help on Scribus

## Where to get help

- the freenode irc channel
- the forums
- http://graphicdesign.stackexchange.com (tag #scribus)
- riot.im
- gitter.im
- facebook
- google+
- twitter

TODO:
- add the links
- is there more?

## Describing your issue

- Issues with text
  - Most of the time, sharing a .sla that shows the issue is enough.
  - If you have issue with the exact positioning of the text, you might need to also share the font you're using.
- Issues with images
  - You will need to 

## How to prepare test files

- Create a simple document that shows the issue you're facing.
- Make a screen shot of what you see
  - If you're sharing a full screen caputre, draw on the image or otherwise describe where you see the issue.
  - If your screen shot contains sensitive information that you don't want other people to see then you can use something like GIMP to quickly blur sections of the image.
- Collect the sample file for output ("File > Collect for output").
  - By using this function you can create a new folder which will contain a copy of the document, copies of all of the images used, and - if you use the right check boxes - copies of all of the fonts and colour management information used in the document.
- Zip the directory "Collect for output" has created
- If the issue happens while editing the file, write a step by step description that leads to the issue (in this case, it might be useful to share to .sla files: one before the action and one after the action).

The test files provide people with a neat package of everything that you're using and makes it much easier to see what's going on. Essentially they're working with the same document that you are.

TODO: prepare a sample file, screenshot and step by step description

## Protecting your files

Be aware of the copyright situation of the images and fonts you collect for output. By collecting for output and posting a ZIP with them in you are essentially distributing them and could be doing so illegally if they have copyright restrictions.

If you're unsure if you're allowed to distribute the files you can:

- Create a short demo file that only contains free content (text, images, fonts, ...) and share that file.
- Privately share the files with the persons that are helping you (upload the file to a non public place and share the link per email or private message).


## How to upload files

Some of the communication channels (like the forums) allow you to upload files up to a given size.

On some of the communication channels (like the mailing lists) you can technically send files but you should refrain from doing it.

If you can publically share your files you can use a service like https://framadrop.org/

If you want to keep the data in your "ownership" you can put on a webserver you own or on a service like Google drive and share the link with the person(s) who is helping you (and trust them not to further share the documents)

## Technical details

In most cases, you should concentrate on providing a good explanation of the issue you're facing. If technical details are needed to give an answer, you will be asked for them.

There is one exception: if you're using a development version of Scribus (currently 1.5.3svn) you should mention it.

### The Operating System

If you're asked to provide your Operating System, we will be expecting one of the followingn answers:

- Microsoft Windws
- Mac OS X
- Linux (Ubuntu, Debian, Fedora, Suse, Archlinux, ...)
- Other (yes, there is more: FreeBsd, OS 2, Haiku, ...)

### The Scribus version

If we ask you which version you are using we expect one of the following answers:

- Scribus 1.4.6 (the latest stable version)
- Scribus 1.5.2
- Scribus 1.5.3svn

If you're using a different version, you might want to first update to one of those versions before asking your question or explain why you are using that version.

The standard way for getting Scribus is

- For Windwos by following the links on the [Get Scribus](https://www.scribus.net/downloads/stable-branch/) on the Scribus homepage or by installing a [Portable App](http://portableapps.com/apps/office/scribus_portable)
- For Mac by following the links on the [Get Scribus](https://www.scribus.net/downloads/stable-branch/) on the Scribus homepage or by installing it from Homebrew
- For Linux by installing the package provided by your distribution or from [Appimage](https://bintray.com/probono/AppImages/Scribus)
- For self compiled version from the Scribus svn server or from the [Scribusproject mirror](https://github.com/scribusproject/scribus) on Github.

If you got Scribus from a different place, you should mention it.

### The fonts

If you're asked to provide the fonts you're using, you should provide the font files themselves, not just their name. There are issues that exist only in specific versions of the fonts (and there are "very different" fonts that share almost the same name).

If the font is not free, you should provide it in a way that does not make them public (as an example, by sharing a short living link through private messages).

#### How to share a font file

am einfachsten geht es so:

- finde eine freie schrift (wenn möglich in gute qualität) die (noch nicht) auf dein computer installiert ist (mögliche quellen sind google font oder https://www.fontsquirrel.com/)
- kopiere sie in einen neuen beliebigen ordner (mit dem namen "fonts" oder "Schriftarten")
- starte scribus ohne ein dokument zu öffnen
- in den eigenschaften (preferences) füge den neuen ordner zu denen wo scribus sucht seine schriften.

jetzt hast du eine schrift die du einfach in scribus für demo-dateien gebrauchen kannst du dann teilen (du musst du auch nicht wieder hochladen... einfach den genaue link nennen, wo du sie heruntergeladen hast)

## Languages

There are a few non-english speaking communities where you can ask questions about Scribus. Few of them are really lively, still in some of them you can get high quality answers (see below for a list).

As so often, the international communities are mainly english speaking. But differently to many similar places, in the Scribus communities, all languages are welcome: the fact that you don't feel comfortable enough in English, should not stop you from asking questions.

When asking questions in your language (assuming it's not English...), the best thing is to try to provide a short summary of your question in English (even automatically translated from an online service) and then ask your question in your own language.

We have many participants from all over the world and there are good chances that you will get a reply in your language or that somebody will be able to understand enough of your question and provide you an answer in english.

Also, if somebody thinks that the summary is not good enough, she will eventually provide a better and more complete translation...

Here is a list of well known places where you're welcome to ask questions about Scribus

- German:
  - https://scribus-user.de
- French:
  - http://www.linuxgraphic.org/forums/viewforum.php?f=20
