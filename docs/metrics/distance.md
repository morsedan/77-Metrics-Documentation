# Distance metrics

Two metrics track how far the vehicle has traveled.

---

## Distance

**Label:** Distance · **Short:** DST · **Unit:** mi or km

Total distance traveled since the drive started, including any continued segments from a resumed drive. Distance is calculated from consecutive GPS positions filtered for accuracy. It accumulates continuously and is never reset during a drive.

Shows 0.0 at drive start before any distance has been traveled.

---

## Trip Distance

**Label:** Trip Distance · **Short:** TRP · **Unit:** mi or km

A resettable distance counter. Trip Distance measures the distance traveled since the most recent reset — similar to a car's trip odometer.

Trip Distance resets automatically to zero at the start of each new drive. During a drive, you can reset it manually at any time from the dashboard long-press menu; the reset does not affect total Drive Distance or any saved statistics.

When continuing a previous drive, Trip Distance starts at zero for the new segment.

Trip Distance is always less than or equal to Drive Distance.
