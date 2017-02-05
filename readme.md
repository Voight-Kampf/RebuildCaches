RebuildCaches
==============

At a glance. You may not imagine that this script is just for fun. To be honest. It's too boring at the airport and therefore I wrote it...
Ah. This script aims at rebuilding system caches easily under macOS.
Also. Cuz I wrote this with several kinds of text editor like Xcode, Sublime Text, Atom... and the code will look like a mess. But everything will be fine under Sublime Text. Who cares. 😉

How to use?
-------------
Download the latest openGate.sh by entering the following command in a terminal window:

``` sh
sudo curl -o /usr/local/bin/RebuildCaches https://raw.githubusercontent.com/PMheart/RebuildCaches/master/RebuildCaches
```

This will download ```RebuildCaches``` to /usr/local/bin and thus you can run it just by typing:
``` sh
RebuildCaches
```

Now we shall change the permissions of the script so that it can be run:
``` sh
sudo chmod +x /usr/local/bin/RebuildCaches
```

Details for using:
If you run ```RebuildCaches``` directly and then it will print something like this:

```
RebuildCaches, Copyright (c) 2007-2017 Angel W. All rights reserved.

Usage:
    RebuildCaches <args>

    The following arguments are currently available:
    -h: Show help infomation. (Print this.)
    -t <target volume>: Rebuild caches for <target volume>.
      Example: -t /

```

This is fine. So you need ```RebuildCaches -t <volume>``` to rebuild the system caches of a specific volume.

Change Log
------------
02/05/2017
- Initial commit.

Bug Reporting
---------------
All bugs should be filed [here] (https://github.com/PMheart/RebuildCaches/issues).
