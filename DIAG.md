# Diagnostics
This file contains tests for each version of unity-n-body. The versions are in chronological order, going from latest to oldest.

### v0.1.0-alpha1

| Speedup | GC Pressure / Step | Script Time |
| :----:  | :-----------------: | :---------: |
| 1x | 9.7-10.7KB | 0.10-0.15ms
| 5x | 9-20KB, 50KB Spike | 0.11-0.26ms, 0.57ms Spike
| 10x | 9-20KB, 93.3KB Spike | 0.12-0.3ms, 0.94ms Spike
| 20x | 19-30KB, 199.8KB Spike | 0.24-0.49ms, 2.35ms Spike
| 30x | 34-60KB, 269.0KB Spike | 0.41-0.63ms, 3.02ms Spike
| 40x | 45-95KB, 350KB Spike | 0.62-1.14ms, 3.62-3.94ms Spikes
| 50x | 67-118KB, 500KB Spike | 0.74-1.18ms, 4.49-5.81ms Spikes
| 60x | 96.6-119.6KB, 500KB Spike | 0.96-1.61ms, 7.33-9.83ms Spikes
| 70x | 111.9-144.8KB, 1500 KB Spikes | 1.84-4.51ms, 8.80-12.97ms Spikes
| 80x | 132KB-326KB, 800KB Spikes | 1.69-4.80ms, 14.94ms Spike
