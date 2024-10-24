# Raspberry Pi NVMe SSD (256GB)

## Details
### Device Identification:

- Manufacturer: Samsung (Vendor ID: 0x144d)
- Model: MZ9LQ256HBJD-00BVL
- Firmware Version: FXM71V1Q

### Basic Specifications:

- Storage Capacity: 256GB (tnvmcap: 256,060,514,304 bytes)
- NVMe Version: 1.4 (ver: 0x10400)

### Temperature Specifications:

- Warning Temperature: 83°C (wctemp: 356 Kelvin)
- Critical Temperature: 85°C (cctemp: 358 Kelvin)
- Minimum Operating Temperature: 45°C (mntmt: 318 Kelvin)
- Maximum Operating Temperature: 83°C (mxtmt: 356 Kelvin)

### Power States (ps):

- PS0: 5.36W - Full power operational mode
- PS1: 4.47W - Reduced power operational mode
- PS2: 2.23W - Low power operational mode (500μs exit latency)
- PS3: 0.05W - Sleep state (entry: 210μs, exit: 1.2ms latency)
- PS4: 0.005W - Deep sleep state (entry: 1ms, exit: 9ms latency)

### Features:

- Supports SMART/Health monitoring (NVME Set Identifier Maximum: 0)
- Supports firmware updates (frmw: 0x16)
- Sanitize capabilities present (sanicap: 0x60000002)

## PCIe Gen 2

| Block Size | 4k (IOPS)                | 8k (IOPS)                | 64k (IOPS)              | 512k (IOPS)             | 1m (IOPS)               | 16m (IOPS)              |
|------------|--------------------------|--------------------------|-------------------------|-------------------------|-------------------------|-------------------------|
| Read       | 430.27 MB/s (107568)    | 436.29 MB/s (54536)     | 441.33 MB/s (6895)     | 442.19 MB/s (863)      | 443.27 MB/s (432)      | 442.62 MB/s (27)       |
| Write      | 385.19 MB/s (96297)     | 390.04 MB/s (48756)     | 395.03 MB/s (6172)     | 395.34 MB/s (772)      | 395.36 MB/s (386)      | 396.05 MB/s (24)       |
| Randread   | 424.98 MB/s (106246)    | 430.64 MB/s (53830)     | 439.83 MB/s (6872)     | 441.91 MB/s (863)      | 442.18 MB/s (431)      | 442.37 MB/s (27)       |
| Randwrite  | 361.05 MB/s (90264)     | 366.00 MB/s (45750)     | 390.24 MB/s (6097)     | 396.60 MB/s (774)      | 397.28 MB/s (387)      | 396.05 MB/s (24)       |

## PCIe Gen 3

| Block Size | 4k (IOPS)                | 8k (IOPS)                | 64k (IOPS)              | 512k (IOPS)             | 1m (IOPS)               | 16m (IOPS)              |
|------------|--------------------------|--------------------------|-------------------------|-------------------------|-------------------------|-------------------------|
| Read       | 806.98 MB/s (201745)    | 782.15 MB/s (97768)     | 771.78 MB/s (12059)    | 870.75 MB/s (1700)     | 870.59 MB/s (850)      | 871.34 MB/s (53)       |
| Write      | 680.47 MB/s (170118)    | 739.07 MB/s (92384)     | 742.57 MB/s (11602)    | 746.81 MB/s (1458)     | 745.25 MB/s (727)      | 748.61 MB/s (45)       |
| Randread   | 787.78 MB/s (196947)    | 820.45 MB/s (102557)    | 866.28 MB/s (13535)    | 870.46 MB/s (1700)     | 870.31 MB/s (849)      | 869.88 MB/s (53)       |
| Randwrite  | 606.77 MB/s (151692)    | 610.23 MB/s (76279)     | 735.03 MB/s (11484)    | 747.79 MB/s (1460)     | 748.09 MB/s (730)      | 748.47 MB/s (45)       |
