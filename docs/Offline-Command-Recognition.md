# Offline Command Recognition

*  Sources:  
** [ReSpeaker – First Impressions + Simple Offline Voice Recognition](https://spin.atomicobject.com/2016/09/19/respeaker/)  
** [nxp-gf / ReSpeaker Python Library](https://github.com/nxp-gf/respeaker_python_library)  

* How-To:
```Bash
pip install pyusb
cd /tmp/run/mountd/mmcblk0p1
git clone https://github.com/respeaker/respeaker_python_library
cd respeaker_python_library
python setup.py develop
python examples/offline_voice_assistant.py
```

Result after telling "_Hey ReSpeaker_" :
```Bash
INFO:mic:Start detecting
INFO:mic:Detected respeaker 
Wake up
INFO:mic:Start listening
INFO:mic:Stop listening
```
