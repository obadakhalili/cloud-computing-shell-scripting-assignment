- For the script `LinuxStatus`, you need to make it executable with `chmod +x LinuxStatus`.
- To use it, simply run `./LinuxStatus`.
- You can run it with an option as follows `./LinuxStatus -p`.
- To add `./LinuxStatus` to `PATH`, we need to append the directory of the script to the `PATH` variable as follows `export PATH=$PATH:/path/to/LinuxStatus/directory`.
- Make the script `deploy` executable with `chmod -x deploy`.
- To run the deployment script automatically at midnight, we open the crontab file with `sudo crontab -e` and add the line `0 0 * * * /path/to/deploy.sh`.
