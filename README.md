default_orientation vertical #start in opposite orientation from your monitor
for_window [class=".*"] split toggle #toggles split at each new window
bindsym $mod+shift+q split toggle kill #kill command resets the split
bindsym $mod+e layout toggle split # should already exist but use if split orientation  messes up
