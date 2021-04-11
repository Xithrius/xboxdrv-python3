# xboxdrv-python3

Updated dependancies of 

To build/install into an arch-based system:
1. `cd` into some place (temporary folder would probably be best)
2. `git clone https://github.com/Xithrius/xboxdrv-python3.git`
3. `cd xboxdrv-python3`
4. `makepkg -sirc`
5. `cd ..`
6. `rm -rf xboxdrv-python3`
7. `sudo systemctl start xboxdrv.service && sudo systemctl enable xboxdrv.service`

7. Play your favorite games with a non-existant controller!
