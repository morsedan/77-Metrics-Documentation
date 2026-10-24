# Troubleshooting

Solutions to common issues with 77 Metrics.

## GPS and location

**Metrics show dashes after starting a drive**

GPS acquisition takes a few seconds, especially indoors or in dense urban areas. Move to an area with a clear view of the sky and wait up to 30 seconds for the signal to lock.

If dashes persist, check that location permission is granted: go to **Settings → Privacy & Security → Location Services → 77 Metrics** and select "While Using App" or "Always."

**Speed or distance readings seem inaccurate**

GPS accuracy varies with signal strength. The GPS tile shows current horizontal accuracy (±n meters). Speed readings from GPS are generally accurate above walking pace; very low speeds may have more noise.

**Altitude readings drift or jump**

77 Metrics fuses barometric and GPS altitude to reduce drift. On drive start, allow 10 seconds for the sensors to converge. Driving through tunnels or parking garages can cause temporary barometric drift, which the app detects and compensates for automatically.

## Drives

**A drive was not saved after I closed the app**

If the app closed unexpectedly during a drive, look for an interrupted drive recovery prompt on next launch. If no prompt appears, the drive may have been too short to produce a checkpoint (checkpoints begin after the first GPS sample is received).

**The Drive Complete screen did not appear**

The drive complete screen appears only when you explicitly tap **Stop**. If you closed the app without stopping the drive, use the interrupted drive recovery on next launch.

**I can't resume a previous drive**

Only the most recently completed drive is eligible for continuation. If a newer drive has since been saved, it becomes the resumable drive instead.

## Dashboard

**A tile disappeared from my dashboard**

When you resize a tile to a size that no longer fits alongside other tiles, smaller tiles may shrink or become temporarily displaced. Shrinking the large tile or removing another tile will restore the displaced tile.

**Changes to my dashboard layout were lost**

Dashboard changes are saved to disk immediately. If layout changes appear to have reset, check whether the app was force-quit before the save could complete.

## Widgets

**The home screen widget is not updating**

WidgetKit widgets update on iOS's schedule, not in real time. During an active drive, the widget updates more frequently via Live Activities. If the widget seems stale after a drive is complete, try editing the home screen and saving to prompt a refresh.

## Performance

**The app uses a lot of battery**

GPS and the barometric altimeter run continuously during an active drive. This is expected behavior. To reduce battery use when you do not need all features, you can pause the drive when stopped for extended periods.
