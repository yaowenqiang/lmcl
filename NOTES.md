Linux Multitasking at the Command Line
> bash sleep-then-echo.sh
> bash sleep-then-echo.sh &

> bg %number-of background-job
> fg %number-of background-job
> fallocate -l 4GB bigfile

> ctrl + z suspend current task

> jobs
> fg -
> bg %4 %5

> help jobs

> jobs -l

> kill -STOP pid
> kill -CONT pid
> kill -STOP %2  # job id
> disown %1  

> help disown

## Screen

> ctrl + a Default keybinding
> man screen
> ctrl a c  # make new screen
> ctrl a p  # cycle
> ctrl a n  # cycle
> ctrl a  ctrl a 
> ctrl a  1
> ctrl a  2
> ctrl a  "
> ctrl a  A # change screen name
> ctrl a  d # detach
> screen -ls
> screen -r # reconnect 
> screen -r session pid # reconnect 

; sessionname

> ctrl a k
> ctrl a \


## tmux

> ctrl b , # change window name
> ctrl b & # close window
> ctrl b arrow key
> ctrl b ; # switch to recent pan
> ctrl b ctrl o # switch to last-used pane
> ctrl b ctrl arrow 
> ctrl b ! # promote pans to full window
> ctrl b x # close pane
> tmux attach -s 0
> ctrl b $ # set session name
> ctrl b % # kill a session
> tmux kill-session -t session-name

> ; new window
> ; new window -c /var/
> ; select-window -t 0
> ; set-option -g monitor-activity o


### configure file

set-option -g allow-rename off
set -g status-bg cyan
set-option -g prefix C-a
unbind C-b

> http://www.hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf
> https://goo.gl/PLd7YL














