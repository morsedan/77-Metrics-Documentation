# Recording drives

77 Metrics records GPS data, speed, elevation, and G-force while you drive. This page covers the full drive lifecycle.

## Starting a drive

Tap **Start Drive** on the dashboard. The app begins accumulating GPS data immediately. All live tiles start updating as soon as the first GPS reading arrives.

On drive start:
- The Trip Distance counter resets to zero
- The screen idle timer is disabled (the display stays on)
- The barometric altimeter and G-force sensor start recording

## Pausing a drive

Tap **Pause** to suspend data accumulation without ending the drive. While paused:
- Elapsed time stops counting
- Distance, elevation, and G-force stop accumulating
- The GPS service continues running so it can re-lock instantly on resume
- Drive data is checkpointed to disk

Tap **Resume** to continue. All counters resume from their paused values. The gap between pause and resume is excluded from elapsed time and moving time.

## Stopping a drive

Tap **Stop** to end the drive. The Drive Complete screen appears with:

- Distance, duration, average speed, and max speed
- Elevation gain, loss, and a scrubable elevation profile
- G-force summary and heat map
- GPS route map

From here, optionally enter a name and tap **Save** to add the drive to trip history. Tap **Discard** to delete it without saving.

## Continuing a previous drive

After reviewing the Drive Complete screen (or from trip history), you can resume the most recently completed drive. The new recording appends to the existing drive as a new segment. When you stop, both segments are merged into a single drive record carrying all combined statistics.

Only the most recently completed drive is available for continuation. A newer saved drive supersedes it.

## Interrupted drive recovery

77 Metrics writes a checkpoint to disk approximately every 30 seconds during recording. If the app is force-quit or crashes, the checkpoint survives.

On next launch, if an uncommitted checkpoint is found, a recovery prompt appears. Tap **Review** to open the Drive Complete screen for the interrupted recording and save it normally. Tap **Discard** to permanently delete the checkpoint.

## Drive data

Each saved drive stores:

- Ordered GPS samples (used for route reconstruction and speed profile)
- Total distance, average speed, and maximum speed
- Elevation gain, loss, minimum elevation, maximum elevation, and net change
- Moving time, elapsed time, and segment boundaries (for continued drives)
- Maximum G-force and a 32×32 G-force heat map
- An optional name assigned at save time
