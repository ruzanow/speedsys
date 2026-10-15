# SPEEDSYS

Some cosmetic changes in the latest beta version of SpeedSys for (relatively) modern processors.

If the processor supports SSE4.2 (which we consider an indicator of a modern CPU, 2008+), the cache test is performed for 16 MB (instead of 8), which gives more adequate results (it does not fit entirely into L3). The main screen also now displays the maximum SSE version supported by the processor.
Fixed two overflows in the code that were breaking cache detection. Cache speed is stored in kilobytes and multiplied by 100 in a couple of places; if the speed exceeds ~40 GB/s, the result exceeds 2^32, causing the detection logic to fail.

Build - tasm5 + upx under dosbox or vmware. Just run SPEEDSYS.BAT.

>This repository contains the unmodified source code for 'System Speed Test' as I received it from Vladimir on August 12, 2006 upon my request.
>IIRC, it is a WIP version 4.79, while the latest binary release was v4.78.


# Screenshots
q9400 Before

<img width="640" height="480" alt="q9400-v478" src="https://github.com/user-attachments/assets/e7bc9cdd-76f0-433c-87fd-8afc1b749c12" />

After

<img width="640" height="480" alt="q9400-v479" src="https://github.com/user-attachments/assets/b6ed297f-e46b-41d4-a059-f86634997ef3" />
