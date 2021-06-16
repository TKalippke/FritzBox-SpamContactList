FritzBox-SpamContactList
========================

A spam list as FritzBox address book (contact list).

Introduction
------------

You can block up to 32 numbers in your FRITZ!Box. If you want to block more than 32 phone numbers, you can also create a phone book in which you store all unwanted numbers and have this automatically blocked by the FRITZ!Box.

See at: https://avm.de/ratgeber/nie-wieder-werbeanrufe/

In order to simplify the work, I provide an xml file for the import on the FRITZ!Box.

Installation
------------

Download the [xml-file](./contactlist/FritzBox-Spam-Phonebook.xml) `FritzBox-Spam-Phonebook.xml` in the sub folder `contactlist`.

After that login to your FRITZ!Box select "*Telefonbuch*" (phone book) and create a new one.

![FRITZ!Box menu](./img/Fritzbox-Menu.png)

Select the the phone book and click "*Wiederherstellen*" (restore).

![FRITZ!Box restore phone book](./img/Fritzbox-Restore.png)

Select the downloaded file.

Blocking calls
--------------

To block the calls you need to activate the new phone book as a spam list.

Select "*Rufbehandlung*" in the main menu and click "*Bereich hinzufügen*" in the section "*Rufnummernbereiche sperren*":

![FRITZ!Box menu](./img/Fritzbox-Menu2.png)

Then select "*Telefonbuch*" in "*Bereich*" and the new phone book in "*Telefonbuch*":

![FRITZ!Box menu](./img/Fritzbox-CallBlocking.png)

That's it.

- - -