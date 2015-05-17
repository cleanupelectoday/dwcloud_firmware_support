# DW.CLOUD firmware support.
This repository is official DW.CLOUD firmware supported by Deaware System. We will update new feature and bug fixed. If there are any bug, please create new issue to report us.

## How to install DW.CLOUD firmware to Arduino IDE (version >= 1.6.4)

#### 1) Add Board Manager URLs
* In **Arduino IDE (version >= 1.6.4)** goto **File > Preference**
* Insert **"Addition Board Manager URLs"** with the link following below.

```
http://github.com/deaware/dwcloud_firmware_support/raw/master/package_deaware_index.json
```

![](http://128.199.203.210/dwcloud_support/images/insert_board_man_url.png)

#### 2) Install **DW.CLOUD**
* Open **"Boards Manager"** by goto **Tools > Board > Boards Manager...**
![](http://128.199.203.210/dwcloud_support/images/select_boards_manager.png)

* Select **DW.CLOUD** and press **"Install"**
![](http://128.199.203.210/dwcloud_support/images/instsall_dwcloud.png)

* Check the DW.CLOUD is ready to used by goto **Tools > Board** and you will see **"DW.CLOUD"** like a picture following below.
![](http://128.199.203.210/dwcloud_support/images/dwcloud_shown.png)
