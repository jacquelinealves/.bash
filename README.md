# .bash
BASH Prompt Options

Here is a list of most of the options you can use for the BASH prompt.
_Some of these commands may not work on all versions of Linux._

    \a – A bell character
    \d – Date (day/month/date)
    \D{format} – Use this to call the system to respond with the current time
    \e – Escape character
    \h – Hostname (short)
    \H – Full hostname (domain name)
    \j – Number of jobs being managed by the shell
    \l – The basename of the shells terminal device
    \n – New line
    \r – Carriage return
    \s – The name of the shell
    \t – Time (hour:minute:second)
    \@ – Time, 12-hour AM/PM
    \A – Time, 24-hour, without seconds
    \u – Current username
    \v – BASH version
    \V – Extra information about the BASH version
    \w – Current working directory ($HOME is represented by ~)
    \W – The basename of the working directory ($HOME is represented by ~)
    \! – Lists this command’s number in the history
    \# – This command’s command number
    \$ – Specifies whether the user is root (#) or otherwise ($)
    \\– Backslash
    \[ – Start a sequence of non-displayed characters (useful if you want to add a command or instruction set to the prompt)
    \] – Close or end a sequence of non-displayed characters
    \e[ – Begin color changes
    0;32m – Specify the color code
    [\u@\h \W]\$ – This is the code for your normal BASH prompt (username@hostname Workingdirectory $)
    \e[0m – Exit color-change mode

The first number in the color code specifies the typeface:

    0 – Normal
    1 – Bold (bright)
    2 – Dim
    4 – Underlined

The second number indicates the color you want:

    30 – Black
    31 – Red
    32 – Green
    33 – Brown
    34 – Blue
    35 – Purple
    36 – Cyan
    37 – Light gray
    
Here are the different meanings for the different parts of the BASH prompt:

    PS1 – This is the primary prompt display. This is where you set special characters or important information.
    PS2 – This is the secondary prompt string. This is usually set as a divider between the prompt display and the text entry. It is also used to display when a long command is broken into sections with the \ sign.
    PS3 – This is the prompt for the select command.
    PS4 – This is the prompt for running a shell script in debug mode.

Under most circumstances, you’ll be working with just the PS1 option and maybe the PS2 option as well.

_Reference [HERE](https://phoenixnap.com/kb/change-bash-prompt-linux)_
