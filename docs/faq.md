# FAQ

Frequently asked questions about 77 Metrics.

## General

**Does 77 Metrics work without a cellular connection?**
Yes. 77 Metrics uses GPS, which works independently of cellular or Wi-Fi. An internet connection is not required during a drive.

**Does the app run in the background?**
77 Metrics keeps your screen on while a drive is active (the idle timer is disabled). If the app moves to the background, GPS updates may slow depending on your iOS location permission setting. Granting "Always" access enables the most reliable background operation.

**What happens if I close the app during a drive?**
Your drive is automatically checkpointed to disk approximately every 30 seconds. If the app is closed unexpectedly, you will be offered the option to recover the interrupted recording on next launch.

## Dashboard

**Can I have different metrics on different pages?**
Yes. Each dashboard page has its own independent set of tiles. You can create multiple pages, each with a different metric selection and layout.

**Why is a tile showing a dash (—)?**
A dash indicates the metric is not yet available. This is normal for the first few seconds of a drive while GPS acquires a fix, or for metrics that require accumulated data (such as Max Speed or Elevation Gain).

**What is Enhanced Information mode?**
When enabled for a page, tiles at Size 2 and larger display additional context alongside the primary value — for example, Average Speed tiles show how your current speed compares to the average.

## Drives

**Can I pause and resume a drive?**
Yes. Tap **Pause** to suspend data accumulation. The location service keeps running so GPS re-locks immediately when you tap **Resume**. Elapsed time stops accumulating while paused.

**Can I continue a drive I already saved?**
Yes. From trip history you can resume the most recently completed drive. The new recording appends to the saved drive; both segments are combined into a single record when you stop.

**How is moving time different from elapsed time?**
Elapsed time counts all time from drive start to stop (excluding pauses). Moving time counts only the time the vehicle was moving above approximately 3.6 km/h (1 m/s). The difference between the two is stopped time.

## Elevation

**Why does altitude take a moment to appear after starting a drive?**
77 Metrics uses a combination of GPS and barometric altimeter data. On drive start, the app waits for the barometric and GPS values to converge before displaying the elevation profile. This typically takes under 10 seconds.

**Why do Elevation Gain and Net Elevation show different values?**
Elevation Gain accumulates every uphill segment throughout the drive (a measure of total climbing effort). Net Elevation Change is simply the difference between your current altitude and your starting altitude — it can be positive, negative, or zero regardless of how much climbing occurred.

## Units and display

**How do I switch between imperial and metric units?**
Open **Settings** (accessible from the dashboard edit view) and select your preferred unit system. The change applies immediately to all tiles and trip history.

**What does Display Precision control?**
Display Precision sets the number of decimal places shown in metric values. The default is one decimal place.
