== MCU MediaServer Precise Build

This is a build of MCU MediaServer for Ubuntu Precise Pangolin 12.04

This is an apt repository. However, you cannot reference it directly hosted on github.

You must clone locally and refer to it directly:

    git clone https://github.com/sous/mcumediaserver-precise
    ( echo deb file://`pwd`/mcumediaserver-precise precise main
      echo deb-src file://`pwd`/mcumediaserver-precise precise main ) > /etc/apt/sources.list.d/mcumediaserver-precise.list

The gpg key for this repo can be imported using:

    curl https://raw.github.com/sous/mcumediaserver-precise/master/apt-key.gpg | sudo apt-key add -

