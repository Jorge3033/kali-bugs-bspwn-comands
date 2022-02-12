# Keyboard
> Keyboard Latam
> sudo setxkbmap -layout 'latam,latam' -model dell105
# Brightness
> sudo chmod 777 /sys/class/backlight/radeon_bl0/brightness
# Sound Set
> alsamixer
** Up Sound
> alias sup='amixer -D pulse set Master 5%+ '
** Down Sound
> alias sup='amixer -D pulse set Master 5%- '
