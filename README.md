# ❤️‍🔥Chaturbate CLI❤️‍🔥

cb-cli is a bash script to watch chaturbate streams in mpv from the terminal. You can subscribe to your favorite streamers, watch or download a live stream, update and print the help menu. That's it for now.

![smugumin](https://github.com/user-attachments/assets/289fe816-349a-4609-ba9b-60422628f833)

# Features

look at all these great features!!!!

    ✔ Watch streamers with mpv

    ✔ Download currently live streams with yt-dlp

    ✔ Locally stored subscriptions

    ✔ Easily update cb-cli with -u flag

    𐄂 Check which streamers are online (feature not implemented yet)

    𐄂 Feed your cat (feature not implemented yet)

# Usage

To watch or download a chaturbate stream, you can use either the -w/--watch or -d/--download flags respectively;

    cb-cli -w/--watch jessicaparkerrr
    cb-cli -d/--download jessicaparkerrr

You can add a streamer to your ~/.config/cb-cli/subscriptions.conf file with the -s/--subscribe flag;

    cb-cli -s/--subscribe jessicaparkerr

You will be able to use the o/--online flags to list which of your subscriptions are live.

    cb-cli -o/--online
    
    note; this feature has not been implemented yet

To update cb-cli, you can use the cb-cli --update command;

    cb-cli -u/--update

Lastly, to run the help dialog, use the -h/--help flags

    cb-cli -h/--help

> Note: More options may be implemented in the future such as --query to search for streams with specific tags. As of right now this is TBD and not on my list of priorities.

# Installation

Dependencies:

    grep
    curl
    mpv
    yt-dlp

To install, simply run the following command;

    sudo curl -L -o /usr/bin/cb-cli https://raw.githubusercontent.com/tapebysea/cb-cli/refs/heads/master/main/cb-cli && sudo chmod +x /usr/bin/cb-cli

> note: this cli is currently work-in-progress and not yet feature complete. right now you may as well just drag a chaturbate url into mpv. if you'd like to contribute, please raise an issue or pull request.
