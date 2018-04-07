# TPFanControl

This is a Fork of https://github.com/ThinkPad-Forum/TPFanControl/tree/master/fancontrol. I've updated it to work with two fan devices, such as the P51. This has only been tested on my P51, but it should work on the P50, P70, and P71 as well, as well as any other dual-fan Thinkpads that are released. A working debug build is included in fancontrol/Debug, but it will need to be run each boot, or added to startup. The default fan profile that is included is a silent one, with the fans only coming on at 60c. This can be changed by editing tpfancontrol.ini in the debug folder. I used Visual Studio 2017 Community to build, but earlier versions may work as well.