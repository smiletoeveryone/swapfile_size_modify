# swapfile_size_modify

![](https://github.com/smiletoeveryone/swapfile_size_modify/blob/master/swapfile_size.jpg)

1. run terminal in the raspberry pi

2. sudo vim /etc/dphys-swapfile

3. modify the line as "CONF_SWAPSIZE=1024". # default is "CONF_SWAPSIZE=100(mb)".

4. sudo /etc/init.d/dphys-swapfile stop # stop the swap service.

5. sudo /etc/init.d/dphys-swapfile start # restart the service.

6. free -m # check out the information of memory consumption and swap

![](https://github.com/smiletoeveryone/swapfile_size_modify/blob/master/mem_check.jpg)

7. you would see the output like it.
