# rclone_cli  : Rclone CLI Samples
    ##
    ##
#! /usr/bin/bash
rclone --no-check-certificate --transfers=40 --checkers=50 sync Source-Remote:source-bucket Target-Remote:target-bucket
rclone --no-check-certificate --transfers=40 --checkers=50 sync Source-Remote:source-bucket Target-Remote:target-bucket
    # nohup ./my-rclone-script.sh &
    # my-rclone-script.sh & disown
