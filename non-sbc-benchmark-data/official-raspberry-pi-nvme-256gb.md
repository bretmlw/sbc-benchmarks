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

| Block Size | 4k (MB/s) | 4k (IOPS) | 8k (MB/s) | 8k (IOPS) |
|------------|-----------|------------|------------|------------|
| Read       | 430.27    | 107568     | 436.29     | 54536     |
| Write      | 385.19    | 96297      | 390.04     | 48756     |
| Randread   | 424.98    | 106246     | 430.64     | 53830     |
| Randwrite  | 361.05    | 90264      | 366.00     | 45750     |

| Block Size | 64k (MB/s) | 64k (IOPS) | 512k (MB/s) | 512k (IOPS) |
|------------|------------|-------------|-------------|-------------|
| Read       | 441.33     | 6895       | 442.19      | 863        |
| Write      | 395.03     | 6172       | 395.34      | 772        |
| Randread   | 439.83     | 6872       | 441.91      | 863        |
| Randwrite  | 390.24     | 6097       | 396.60      | 774        |

| Block Size | 1m (MB/s) | 1m (IOPS) | 16m (MB/s) | 16m (IOPS) |
|------------|-----------|-----------|------------|------------|
| Read       | 443.27    | 432       | 442.62     | 27        |
| Write      | 395.36    | 386       | 396.05     | 24        |
| Randread   | 442.18    | 431       | 442.37     | 27        |
| Randwrite  | 397.28    | 387       | 396.05     | 24        |

## PCIe Gen 3

| Block Size | 4k (MB/s) | 4k (IOPS) | 8k (MB/s) | 8k (IOPS) |
|------------|-----------|------------|------------|------------|
| Read       | 806.98    | 201745     | 782.15     | 97768     |
| Write      | 680.47    | 170118     | 739.07     | 92384     |
| Randread   | 787.78    | 196947     | 820.45     | 102557    |
| Randwrite  | 606.77    | 151692     | 610.23     | 76279     |

| Block Size | 64k (MB/s) | 64k (IOPS) | 512k (MB/s) | 512k (IOPS) |
|------------|------------|-------------|-------------|-------------|
| Read       | 771.78     | 12059      | 870.75      | 1700       |
| Write      | 742.57     | 11602      | 746.81      | 1458       |
| Randread   | 866.28     | 13535      | 870.46      | 1700       |
| Randwrite  | 735.03     | 11484      | 747.79      | 1460       |

| Block Size | 1m (MB/s) | 1m (IOPS) | 16m (MB/s) | 16m (IOPS) |
|------------|-----------|-----------|------------|------------|
| Read       | 870.59    | 850       | 871.34     | 53        |
| Write      | 745.25    | 727       | 748.61     | 45        |
| Randread   | 870.31    | 849       | 869.88     | 53        |
| Randwrite  | 748.09    | 730       | 748.47     | 45        |
