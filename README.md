# SPEEDSYS

Some cosmetic changes in the latest beta version of SpeedSys for (relatively) modern processors.

If the processor supports SSE4 (in which case we consider it modern), the cache test is performed for 16 MB (instead of 8), which gives more adequate results (it does not fit entirely into L3). Also, the main screen now shows the maximum supported SSE version. 

Build - tasm5 + upx under dosbox or vmware. Just run SPEEDSYS.BAT.

>This repository contains the unmodified source code for 'System Speed Test' as I received it from Vladimir on August 12, 2006 upon my request.
>IIRC, it is a WIP version 4.79, while the latest binary release was v4.78. I do not remember if source code builds correctly.

