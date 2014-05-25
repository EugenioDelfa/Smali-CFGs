Smali-CFGs
==========

Smali Control Flow Graph's

Smali Class Method CFG.

	$ flow.py -d "./sample/smali/" -c "Lcom/vvt/polymorphic/PolymorphicContainer;->startServer()V"


![](https://raw.github.com/EugenioDelfa/Smali-CFGs/master/imgs/method_flow_example.png)


Smali Calls XRefs CFG.

	$ xref.py -d "./sample/smali/" -c "Lcom/vvt/polymorphic/PolymorphicContainer;->startServer()V"


![](https://raw.github.com/EugenioDelfa/Smali-CFGs/master/imgs/startServer_single.png)

-

![](https://raw.github.com/EugenioDelfa/Smali-CFGs/master/imgs/startServer_full.png)
