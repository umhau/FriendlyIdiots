#!/bin/bash

Download the fabric server launcher - you do not need to download anything from minecraft.net.

    wget https://meta.fabricmc.net/v2/versions/loader/1.19.2/0.14.13/0.11.1/server/jar -O $serverdir/server.jar

Perform an initial run of the server - do this before you add any mods. This command MUST be run from within the directory where the server configurations are kept. Might as well accept the sula ahead of time, too.

    echo eula=true > eula.txt
    java -Xmx2G -jar server.jar

