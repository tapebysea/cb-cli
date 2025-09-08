# ❤️‍🔥Chaturbate CLI❤️‍🔥

cb-cli is a bash script to watch chaturbate streams in mpv from the terminal. You can subscribe to your favorite streamers, check who's online, watch or download a live stream, and update cb-cli all from the terminal!

![smugumin](https://github.com/user-attachments/assets/9027fd5f-1e40-428b-a0d6-dcd39521c122)

# Features

look at all these great features!!!!

    ✔ Watch streamers with mpv

    ✔ Download currently live streams with yt-dlp

    ✔ Locally stored subscriptions

    ✔ Easily update cb-cli with -u flag

    ✔ Check which streamers are online

    𐄂 Feed your cat (feature not implemented yet)

# Usage

To watch or download a chaturbate stream, you can use either the -w/--watch or -d/--download flags respectively;

    cb-cli -w/--watch jessicaparkerrr
    cb-cli -d/--download jessicaparkerrr

You can add a streamer to your ~/.config/cb-cli/subscriptions.conf file with the -s/--subscribe flag;

    cb-cli -s/--subscribe jessicaparkerr

You can also use the o/--online flags to list which of your subscriptions are live.

    cb-cli -o/--online

    note; this feature may be subject to future changes
    
To update cb-cli, you can use the cb-cli --update command;

    cb-cli -u/--update

Lastly, to run the help dialog, use the -h/--help flags

    cb-cli -h/--help

> Note: More options may be implemented in the future such as --query to search for streams with specific tags. As of right now this is TBD and not on my list of priorities.

# Installation

Dependencies:

    grep
    curl
    sed
    tr
    mpv
    yt-dlp

To install, simply run the following command;

    sudo curl -L -o /usr/bin/cb-cli https://raw.githubusercontent.com/tapebysea/cb-cli/refs/heads/master/src/cb-cli && sudo chmod +x /usr/bin/cb-cli

> Note; Contributors are welcome. This cli is currently work-in-progress and not yet feature complete. Right now you may as well just drag a chaturbate url into mpv. If you'd like to contribute, please raise an issue or pull request.
