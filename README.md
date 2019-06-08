# wxPython-bin
NVDA's wxPython dependency

This repository fulfils NVDA's dependency on wxPython.
It was created with the following command: `pip3 install -t ./ wxPython==4.0.3`

It contains the following packages:

* wxPython 4.0.3: wxPython 4.0.4 and above contain breaking changes to the accessibility layer
* six 1.12.0
* PyPubSub 4.0.3: needed by the wx.lib.evtmgr which is currently not in use by NVDA