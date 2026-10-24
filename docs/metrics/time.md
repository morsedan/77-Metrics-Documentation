# Time metrics

Three metrics track how time has been distributed during the drive.

---

## Elapsed Time

**Label:** Elapsed Time · **Short:** TIME

Total recorded drive time from start to stop, excluding pauses. Elapsed Time is a wall clock of active recording: it counts every second the drive is in the active phase, and stops counting while paused or stopped.

For continued drives (where a previous drive is resumed), elapsed time accumulates across all segments.

---

## Moving Time

**Label:** Moving Time · **Short:** MVG

The portion of elapsed time during which the vehicle was moving above approximately 3.6 km/h (1 m/s). Moving Time is always less than or equal to Elapsed Time.

Moving Time is what most cycling computers and GPS devices use for average speed calculations. 77 Metrics exposes it directly as a tile and uses it to calculate Moving Avg speed.

---

## Stopped Time

**Label:** Stopped Time · **Short:** STP

The difference between Elapsed Time and Moving Time — the total time spent stopped during the drive. Useful for understanding how much time was spent at traffic lights, rest stops, or in traffic.

Stopped Time = Elapsed Time − Moving Time.
