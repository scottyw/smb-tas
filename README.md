# Tool-Assisted Speedrun of Super Mario Bros (1985) in under 5 minutes (just)

The `tasproj` file is all you need if you want to try the run yourself. It's a zip-formatted file so I included the expanded version of it for the sake of interest.

I used:
* [BizHawk 2.6.1](https://github.com/TASVideos/BizHawk)
* Super Mario Bros (World) ROM file

[Youtube video](https://www.youtube.com/watch?v=0Q3MNauEN-8)

## References

I spent a lot of time watching [Kosmic](https://www.youtube.com/channel/UC6esFMAIud24sYSHfHGzPhg)'s incredible [4:55.64 run](https://www.youtube.com/watch?v=1wR8x5b_ExM).

Kosmic also has a [fantastic tutorial](https://www.youtube.com/watch?v=kyZ4yF3ynsA) on breaking the 5 minute barrier. 

[Darbian](https://www.youtube.com/channel/UC_wB4WC7FTdXcjPAqVlS7mA) has some great videos too.

## Notes on Timing 

I used the rules defined on [speedrun.com](https://www.speedrun.com/smb1).

You'll find a marker in each world on the frame when the clock appears and on the last frame of the run.

You can use [this timer from somewes](https://somewes.com/smb-time) to determine the frame count based on that last frame. For example, [this one is mine](https://somewes.com/smb-time/?game=smb1&category=Any%25&console=NES&time_estimate=4%3A59.84&frame_rule_offset=0&lag_frames=0&axe_frames=0).

Since we're using an emulator you can cross-check against the frame count directly. The first frame of this run is 196 (when the 400 timer appears on World 1-1) and the last frame is 18215 (the last one before the sprites disappear). That's a total of 18020 frames (including both 196 and 18215) running at 60.0988139 frames/sec for a total of 299.840 seconds.
