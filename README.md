#Note

I find that this projects have done much better jobs than I did, thus this project is droped.

    * https://github.com/ohsc/ThunderLixianAssistant
    * http://aria2.sourceforge.net
    * or
    * https://github.com/iambus/xunlei-lixian

#ThunderBatchGet

A web UI for retrieving Thunder(Xenlei) Cloud Downloads without their client software via wget. Runs under Linux.

This program consists of 2 parts:

1. A python program providing WEB UI and managing background wget subproceses.
2. Browser Extension (supports chrome and firefox greasemonkey) to insert useful links into the Thunder Clound WEB UI(lixian.xunlei.com)

#HOW to use

1. Install the extension in the BrowserExtension directory.
    * For chrome, enable the developer mode and load an unpacked extension.
    * For Firefox, install greasemonkey and install the `cloudbatchget.user.js` file.

2. Run `ThunderBatchGet_daemon.py` in the command line.
3. Open Lixian Cloud in the browser, login, when page fully loaded, 2 extra links are insert into the page left sidebar. Click `InsertDownLink`, a bottom will appear in each downloaded files in the main list. Click that bottom will begin a download in the background, process can be seen in the automaticly opened browser, which a simple UI listening at `localhost:8080`.
    
