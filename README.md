
RevRev | Experimental Reverse Reverb Sampler

# IMPORTANT END USER AGREEMENT
UNSTABLE SOFTWARE. By using the software you agree to accept full responsibility for it use
and that the creator is not liable for any damages, loss of data, etc.
PlugData is still in beta and this patch is not thoroughly tested.
Crashes/bugs are very possible. Plugdata has a built-in limiter by default, and the patch has
an additional limiter, but you may still want to add a 3rd limiter in the FX chain after
the PlugData VST.


# ABOUT
An experimental sampler using a reversed reverb effect.
Contained in a simple project to be user-friendly for those who are unfamiliar with PureData/PlugData.
Intended for use in plugdata-fx VST; use with PlugData standalone app is not recommended.
Not abstraction-ready (uses "init" setting; no savestate objects).


# INSTALLATION / USE
1. Install PlugData (version 0.80 or later recommended)
2. Load plugdata-fx VST3 and open RevRev_0900.pd
3. Before use, click on the menu button top left of the plugdata window (horizontal bars), choose "Save Patch As..",
and save it somewhere (DAW project folder, for example) with a name of your choosing.

NOTES: 
= PlugData may save the PlugData patch with a DAW project, but this is not a certainty. When you wish to save
the current state of the patch, I recommend navigating to the aforementioned file menu in PlugData and using
"Save Patch" or "Save Patch As.."


# KNOW PROBLEMS
- Crashes in some hosts (FL Studio) when changing buffer Length or project tempo. If you want to change the
length, do it in the PlugData standalone .exe, save, then use that saved patch in your DAW/host.
