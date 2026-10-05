# SPEEDSYS

Some cosmetic changes in the latest beta version of SpeedSys for (relatively) modern processors.

If the processor supports SSE4.2 (which we consider an indicator of a modern CPU, 2008+), the cache test is performed for 16 MB (instead of 8), which gives more adequate results (it does not fit entirely into L3). The main screen also now displays the maximum SSE version supported by the processor.

Build - tasm5 + upx under dosbox or vmware. Just run SPEEDSYS.BAT.

>This repository contains the unmodified source code for 'System Speed Test' as I received it from Vladimir on August 12, 2006 upon my request.
>IIRC, it is a WIP version 4.79, while the latest binary release was v4.78. I do not remember if source code builds correctly.

