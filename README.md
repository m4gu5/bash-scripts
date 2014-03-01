+--------------------------------------------------+
|__________________________________________________|
|                m4gu5 bash scripts                |
|__________________________________________________|
|                                                  |
|          .;'     ..                              |
|            ,:.  .:'          ..                  |
|              ;, :c.          .c' .,'             |
|               ;co'            .:,:.              |
|               ,oc             .c;                |
|               :':.           .:co'               |
|              ;, .c,        .:;. ::               |
|             ;:   .c:      ;c.   .:'              |
|            :o.     ;:   .:,      ,c.             |
|           ;l'       ,c';;.        ;;             |
|          .l'         :lc.         .o.            |
|         .:'        '::':,         .c:.           |
|         ,.        ...   ..          .,.          |
|         .                                        |
|                                                  |
+--------------------------------------------------+

+==================================================+
| downforjustme                                    | 
| ------------------------------------------------ |
| Uses http://downforeveryoneorjustme.com to check |
| if a site is down for everyone or just you.      |
|                                                  |
| Example usage:                                   |
| ./downforjustme http://github.com                |
+==================================================+

+==================================================+
| hostChecker                                      |
| ------------------------------------------------ |
| Checks what hosts are online in an IPv4 class c  |
| (/24) network. Requires the fping and ifconfig   |
| packages                                         |
|                                                  |
| Example usage:                                   |
| ./hostChecker ./hostChecker 192.168.2.0          |
+==================================================+

+==================================================+
| run_after                                        |
| ------------------------------------------------ |
| Lets you execute a program after all instances   |
| of the specified program had quit.               |
| For example, you could do a shutdown -h now      |
| after all updates were installed.                |
|                                                  |
| Example usage:                                   |
| ./run_after pacman shutdown "-h now"             |
+==================================================+

+==================================================+
| setAPOD                                          |
| ------------------------------------------------ |
| This script sets the current "Astronomic Picture |
| Of The Day" as wallpaper in Gnome.               |
| You can specify the directory where the pictures |
| should be saved, else /tmp/ is used.             |
| If you use feh or another program to set your    |
| desktop wallpaper you have to change the last    |
| line of this script.                             |
|                                                  |
| Example usage:                                   |
| ./setAPOD /home/$USER/Pictures/APOD              |
+==================================================+
