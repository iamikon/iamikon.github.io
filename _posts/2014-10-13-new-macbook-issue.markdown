---
layout: post
title:  "new macbook linux pain"
date:   2014-10-13 10:10:25
categories: macbook
---
i haven't seen this error listed anywhere before. having a mid 2013 13" macbook
air has actually been a great success with linux. unfortunately for me and other
and anyone else who wants linux on their macbook the osx yosemite beta updates
some hardware firmware. as soon as this update (beta4) did what it did linux has
been un-usable on the macbook. the kworker process is constantly pinged at about
75% the entire time the system is up. obviously this makes for some very quick
heating of the macbook and is not a great deal of fun. the only work around i
have found is to disable acpi completely by adding `acpi=off` as a kernel option
in grub or refind. this fixed the kworker problem but introduces others, most
notably is the system is far less responsive. i will continue to look into a
solution for this but i believe if you are on the yosemite beta linux will not
be very usable for quite awhile until the firmware patch is integrated into the
kernel.
