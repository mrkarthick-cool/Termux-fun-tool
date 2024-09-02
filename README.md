# Termux-fun-tool
Termux fun tool 

# Tool Installation 

👉 pkg update -y && clear && pkg upgrade -y && clear 

👉 pkg install termux-api 

👉🏻 pkg install termux-toast

👉 git clone https://github.com/mrkarthick-cool/Termux-fun-tool.git


# How to run tool 🔥


👉 cd Termux-fun-tool

👉 chmod +x *

👉 ./Fun.sh  ( or ) bash Fun.sh



#Tool package Breakdown 

To install `termux-toast` in Termux, you can use the following command:

`apt install termux-toast`

This will install the `termux-toast` package, which allows you to display toast notifications in Termux.

If you want to use the `termux-toast` command to display a toast notification, you can use the following syntax:

`termux-toast [options] <message>`

Replace `<message>` with the text you want to display in the toast notification.

Here are some options you can use with `termux-toast`:

- `-t <time>`: Set the duration of the toast notification (e.g., `-t 3000` for 3 seconds)
- `-g <gravity>`: Set the gravity of the toast notification (e.g., `-g top` or `-g center`)
- `-c <color>`: Set the color of the toast notification (e.g., `-c red` or `-c #FFFFFF`)

Example:

`termux-toast -t 3000 -g top -c red "Hello, World!"`

This will display a red toast notification at the top of the screen with the message "Hello, World!" for 3 seconds.
