Processor Info
==============

This is a project to collect processor model details and share lscpu
reports collected by BSD users at https://bsd-hardware.info.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Total processor models: 925.

About
-----

The structure of the repository is the following:

    {VENDOR}/{MODEL PREFIX}/{MODEL NAME}/{FAMILY}-{MODEL}-{STEPPING}/{PROBE ID}

    ( e.g. Intel/Core/Core i7-3630QM/6-58-9/87A12F3AED )

CPU Models
----------

| MFG   | Model                          | Cores | L1d | L1i | L2    | L3   |
|-------|--------------------------------|-------|-----|-----|-------|------|
| Intel | Xeon Phi 7210                  | 256   | 32K | 32K | 1024K |      |
| AMD   | EPYC 7742 64-Core              | 128   | 32K | 32K | 512K  | 256M |
| AMD   | Ryzen Threadripper 3970X 32... | 64    | 32K | 32K | 512K  | 128M |
| AMD   | Ryzen Threadripper 3960X 24... | 48    | 32K | 32K | 512K  | 128M |
| Intel | Xeon Gold 5220R                | 48    | 32K | 32K | 1024K | 35M  |
| Intel | Xeon Platinum 8260L            | 48    | 32K | 32K | 1024K | 35M  |
| Intel | Xeon Gold 5220                 | 36    | 32K | 32K | 1024K | 24M  |
| AMD   | Ryzen 9 3950X 16-Core          | 32    | 32K | 32K | 512K  | 64M  |
| AMD   | Ryzen Threadripper 2950X 16... | 32    | 32K | 64K | 512K  | 32M  |
| AMD   | Ryzen 9 5950X 16-Core          | 32    | 32K | 32K | 512K  | 64M  |
| Intel | Xeon E5-2683 v4                | 32    | 32K | 32K | 256K  | 40M  |
| Intel | Xeon E5-2660 v4                | 28    | 32K | 32K | 256K  | 35M  |
| Intel | Xeon E5-2680 v4                | 28    | 32K | 32K | 256K  | 35M  |
| Intel | Xeon E5-2690 v4                | 28    | 32K | 32K | 256K  | 35M  |
| Intel | Core i9-7940X                  | 28    | 32K | 32K | 1024K | 19M  |
| AMD   | Ryzen 9 3900 12-Core           | 24    | 32K | 32K | 512K  | 64M  |
| AMD   | Ryzen 9 3900X 12-Core          | 24    | 32K | 32K | 512K  | 64M  |
| AMD   | Ryzen 9 3900XT 12-Core         | 24    | 32K | 32K | 512K  | 64M  |
| AMD   | Ryzen Threadripper 2920X 12... | 24    | 32K | 64K | 512K  | 32M  |
| AMD   | Ryzen 9 5900X 12-Core          | 24    | 32K | 32K | 512K  | 64M  |
| Intel | Xeon E5-2695 v2                | 24    | 32K | 32K | 256K  | 30M  |
| Intel | Xeon E5-2650L v3               | 24    | 32K | 32K | 256K  | 30M  |
| Intel | Xeon E5-2678 v3                | 24    | 32K | 32K | 256K  | 30M  |
| Intel | Xeon Silver 4116               | 24    | 32K | 32K | 1024K | 16M  |
| Intel | Xeon Silver 4214               | 24    | 32K | 32K | 1024K | 16M  |
| Intel | Xeon Silver 4214R              | 24    | 32K | 32K | 1024K | 16M  |
| Intel | Core i9-10850K                 | 20    | 32K | 32K | 256K  | 20M  |
| Intel | Core i9-10900                  | 20    | 32K | 32K | 256K  | 20M  |
| Intel | Core i9-10900T                 | 20    | 32K | 32K | 256K  | 20M  |
| Intel | Xeon W-1290                    | 20    | 32K | 32K | 256K  | 20M  |
| Intel | Xeon E5-2660 v2                | 20    | 32K | 32K | 256K  | 25M  |
| Intel | Xeon E5-2650 v3                | 20    | 32K | 32K | 256K  | 25M  |
| Intel | Core i9-9820X                  | 20    | 32K | 32K | 1024K | 16M  |
| Intel | Core i9-9900X                  | 20    | 32K | 32K | 1024K | 19M  |
| Intel | Xeon Silver 4114               | 20    | 32K | 32K | 1024K | 13M  |
| AMD   | Opteron 6284 SE                | 16    | 16K | 64K | 2048K | 12M  |
| AMD   | Ryzen 7 1700 Eight-Core        | 16    | 32K | 64K | 512K  | 16M  |
| AMD   | Ryzen 7 1700X Eight-Core       | 16    | 32K | 64K | 512K  | 16M  |
| AMD   | Ryzen 7 1800X Eight-Core       | 16    | 32K | 64K | 512K  | 16M  |
| AMD   | Ryzen Threadripper 1900X 8-... | 16    | 32K | 64K | 512K  | 16M  |
| AMD   | Ryzen 7 3700X 8-Core           | 16    | 32K | 32K | 512K  | 32M  |
| AMD   | Ryzen 7 3800X 8-Core           | 16    | 32K | 32K | 512K  | 32M  |
| AMD   | EPYC 7252 8-Core               | 16    | 32K | 32K | 512K  | 64M  |
| AMD   | Ryzen 7 2700 Eight-Core        | 16    | 32K | 64K | 512K  | 16M  |
| AMD   | Ryzen 7 2700X Eight-Core       | 16    | 32K | 64K | 512K  | 16M  |
| AMD   | Ryzen 7 4700G with Radeon G... | 16    | 32K | 32K | 512K  | 8M   |
| AMD   | Ryzen 7 4800H with Radeon G... | 16    | 32K | 32K | 512K  | 8M   |
| AMD   | Ryzen 7 PRO 4750G with Rade... | 16    | 32K | 32K | 512K  | 8M   |
| AMD   | Ryzen 7 PRO 4750U with Rade... | 16    | 32K | 32K | 512K  | 8M   |
| AMD   | Ryzen 7 5800X 8-Core           | 16    | 32K | 32K | 512K  | 32M  |
| Intel | Core i9-9900K                  | 16    | 32K | 32K | 256K  | 16M  |
| Intel | Core i9-9900K                  | 16    | 32K | 32K | 256K  | 16M  |
| Intel | Xeon E-2278G                   | 16    | 32K | 32K | 256K  | 16M  |
| Intel | Xeon E-2286M                   | 16    | 32K | 32K | 256K  | 16M  |
| Intel | Core i7-10875H                 | 16    | 32K | 32K | 256K  | 16M  |
| Intel | Xeon W-10885M                  | 16    | 32K | 32K | 256K  | 16M  |
| Intel | Core i7-10700                  | 16    | 32K | 32K | 256K  | 16M  |
| Intel | Core i7-10700                  | 16    | 32K | 32K | 256K  | 16M  |
| Intel | Xeon E5-2650L 0                | 16    | 32K | 32K | 256K  | 20M  |
| Intel | Xeon E5-2450L 0                | 16    | 32K | 32K | 256K  | 20M  |
| Intel | Xeon E5-2660 0                 | 16    | 32K | 32K | 256K  | 20M  |
| Intel | Xeon E5-2670 0                 | 16    | 32K | 32K | 256K  | 20M  |
| Intel | Xeon E5-2690 0                 | 16    | 32K | 32K | 256K  | 20M  |
| Intel | Xeon E5-2450 v2                | 16    | 32K | 32K | 256K  | 20M  |
| Intel | Xeon E5-2650 v2                | 16    | 32K | 32K | 256K  | 20M  |
| Intel | Xeon E5-2630 v3                | 16    | 32K | 32K | 256K  | 20M  |
| Intel | Xeon E5-2630L v3               | 16    | 32K | 32K | 256K  | 20M  |
| Intel | Xeon E5-2620 v4                | 16    | 32K | 32K | 256K  | 20M  |
| Intel | Xeon E5-2667 v4                | 16    | 32K | 32K | 256K  | 25M  |
| Intel | Xeon D-2146NT                  | 16    | 32K | 32K | 1024K | 11M  |
| Intel | Xeon Silver 4108               | 16    | 32K | 32K | 1024K | 11M  |
| Intel | Xeon Silver 4215R              | 16    | 32K | 32K | 1024K | 11M  |
| Intel | Xeon D-1540                    | 16    | 32K | 32K | 256K  | 12M  |
| Intel | Xeon D-1537                    | 16    | 32K | 32K | 256K  | 12M  |
| Intel | Xeon D-1541                    | 16    | 32K | 32K | 256K  | 12M  |
| AMD   | Opteron 6168                   | 12    | 64K | 64K | 512K  | 10M  |
| AMD   | Ryzen 5 1600 Six-Core          | 12    | 32K | 64K | 512K  | 16M  |
| AMD   | Ryzen 5 3600 6-Core            | 12    | 32K | 32K | 512K  | 32M  |
| AMD   | Ryzen 5 3600X 6-Core           | 12    | 32K | 32K | 512K  | 32M  |
| AMD   | Ryzen 5 3600XT 6-Core          | 12    | 32K | 32K | 512K  | 32M  |
| AMD   | Ryzen 5 1600 Six-Core          | 12    | 32K | 64K | 512K  | 16M  |
| AMD   | Ryzen 5 2600 Six-Core          | 12    | 32K | 64K | 512K  | 16M  |
| AMD   | Ryzen 5 2600X Six-Core         | 12    | 32K | 64K | 512K  | 16M  |
| AMD   | Ryzen 5 4600H with Radeon G... | 12    | 32K | 32K | 512K  | 8M   |
| AMD   | Ryzen 5 PRO 4650G with Rade... | 12    | 32K | 32K | 512K  | 8M   |
| Intel | Core i7-8700                   | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Core i7-8700K                  | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Core i7-8750H                  | 12    | 32K | 32K | 256K  | 9M   |
| Intel | Core i7-9750H                  | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Core i9-8950HK                 | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Xeon E-2236                    | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Xeon E-2276G                   | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Core i7-9750HF                 | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Core i7-9850H                  | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Core i7-10750H                 | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Core i5-10400                  | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Core i5-10400F                 | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Core i5-10500T                 | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Core i5-10400F                 | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Core i5-10600K                 | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Core i7-10710U                 | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Core i5-11400                  | 12    | 48K | 32K | 512K  | 12M  |
| Intel | Core i7 970                    | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Xeon E5645                     | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Xeon L5640                     | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Xeon W3680                     | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Xeon X5650                     | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Xeon X5660                     | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Xeon X5670                     | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Xeon X5675                     | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Xeon X5680                     | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Xeon X5690                     | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Core i7-3930K                  | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Xeon E5-1650 0                 | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Xeon E5-2430 0                 | 12    | 32K | 32K | 256K  | 15M  |
| Intel | Xeon E5-2620 0                 | 12    | 32K | 32K | 256K  | 15M  |
| Intel | Xeon E5-2630 0                 | 12    | 32K | 32K | 256K  | 15M  |
| Intel | Xeon E5-2640 0                 | 12    | 32K | 32K | 256K  | 15M  |
| Intel | Core i7-4930K                  | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Xeon E5-1650 v2                | 12    | 32K | 32K | 256K  | 12M  |
| Intel | Xeon E5-2430 v2                | 12    | 32K | 32K | 256K  | 15M  |
| Intel | Xeon E5-2430L v2               | 12    | 32K | 32K | 256K  | 15M  |
| Intel | Xeon E5-2620 v2                | 12    | 32K | 32K | 256K  | 15M  |
| Intel | Core i7-5820K                  | 12    | 32K | 32K | 256K  | 15M  |
| Intel | Xeon E5-1650 v3                | 12    | 32K | 32K | 256K  | 15M  |
| Intel | Xeon E5-2620 v3                | 12    | 32K | 32K | 256K  | 15M  |
| Intel | Xeon E5-2643 v3                | 12    | 32K | 32K | 256K  | 20M  |
| Intel | Core i7-6850K                  | 12    | 32K | 32K | 256K  | 15M  |
| Intel | Xeon E5-1650 v4                | 12    | 32K | 32K | 256K  | 15M  |
| Intel | Xeon D-1528                    | 12    | 32K | 32K | 256K  | 9M   |
| Intel | Atom C3858                     | 12    | 24K | 32K | 2048K |      |
| AMD   | FX-8300 Eight-Core             | 8     | 16K | 64K | 2048K | 8M   |
| AMD   | FX-8320 Eight-Core             | 8     | 16K | 64K | 2048K | 8M   |
| AMD   | FX-8320E Eight-Core            | 8     | 16K | 64K | 2048K | 8M   |
| AMD   | FX-8350 Eight-Core             | 8     | 16K | 64K | 2048K | 8M   |
| AMD   | FX-8370 Eight-Core             | 8     | 16K | 64K | 2048K | 8M   |
| AMD   | FX-9590 Eight-Core             | 8     | 16K | 64K | 2048K | 8M   |
| AMD   | Opteron 4386                   | 8     | 16K | 64K | 2048K | 6M   |
| AMD   | Ryzen 5 1500X Quad-Core        | 8     | 32K | 64K | 512K  | 16M  |
| AMD   | EPYC 3201 8-Core               | 8     | 32K | 64K | 512K  | 16M  |
| AMD   | Ryzen 3 3100 4-Core            | 8     | 32K | 32K | 512K  | 16M  |
| AMD   | Ryzen 5 2400G with Radeon V... | 8     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen 5 2500U with Radeon V... | 8     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen 5 PRO 2400GE w_ Radeo... | 8     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen 5 PRO 2500U w_ Radeon... | 8     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen 7 2700U with Radeon V... | 8     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen 7 PRO 2700U w_ Radeon... | 8     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen Embedded V1605B with ... | 8     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen 5 3400G with Radeon V... | 8     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen 5 3500U with Radeon V... | 8     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen 5 3550H with Radeon V... | 8     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen 5 PRO 3500U w_ Radeon... | 8     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen 7 3700U with Radeon V... | 8     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen 7 PRO 3700U w_ Radeon... | 8     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen 7 4700U with Radeon G... | 8     | 32K | 32K | 512K  | 8M   |
| Intel | Core i7-1065G7                 | 8     | 48K | 32K | 512K  | 8M   |
| Intel | Core i5-8250U                  | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-8259U                  | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-8350U                  | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-8550U                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-8650U                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i5-8265U                  | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-8565U                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i5-10210U                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-10310U                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-8265U                  | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-8365U                  | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-10510U                 | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-8565U                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-8665U                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E5345                     | 8     | 32K | 32K | 4M    | 4M   |
| Intel | Xeon E5345                     | 8     | 32K | 32K | 4M    | 4M   |
| Intel | Core i5-8400H                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i5-9300H                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E-2144G                   | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E-2274G                   | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i5-9300H                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-9700                   | 8     | 32K | 32K | 256K  | 12M  |
| Intel | Core i7-9700K                  | 8     | 32K | 32K | 256K  | 12M  |
| Intel | Core i7-7700                   | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-7700HQ                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-7700K                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-7700T                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-7820HQ                 | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1230 v6                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1245 v6                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1270 v6                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1275 v6                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1505M v6               | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i5-10300H                 | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i3-10100                  | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Xeon E5405                     | 8     | 32K | 32K | 6M    |      |
| Intel | Xeon L5410                     | 8     | 32K | 32K | 6M    |      |
| Intel | Xeon X5460                     | 8     | 32K | 32K | 6M    |      |
| Intel | Xeon E5410                     | 8     | 32K | 32K | 6M    |      |
| Intel | Xeon E5450                     | 8     | 32K | 32K | 6M    |      |
| Intel | Xeon X5482                     | 8     | 32K | 32K | 6M    |      |
| Intel | Core i7 920                    | 8     | 32K | 32K |       | 8M   |
| Intel | Core i7 920                    | 8     | 32K | 32K |       | 8M   |
| Intel | Core i7 930                    | 8     | 32K | 32K |       | 8M   |
| Intel | Core i7 950                    | 8     | 32K | 32K |       | 8M   |
| Intel | Xeon E5520                     | 8     | 32K | 32K |       | 8M   |
| Intel | Xeon E5530                     | 8     | 32K | 32K |       | 8M   |
| Intel | Xeon E5540                     | 8     | 32K | 32K |       | 8M   |
| Intel | Xeon W3520                     | 8     | 32K | 32K |       | 8M   |
| Intel | Xeon W3530                     | 8     | 32K | 32K |       | 8M   |
| Intel | Xeon W3570                     | 8     | 32K | 32K |       | 8M   |
| Intel | Xeon X5550                     | 8     | 32K | 32K |       | 8M   |
| Intel | Xeon X5560                     | 8     | 32K | 32K |       | 8M   |
| Intel | Core i7 860                    | 8     | 32K | 32K |       | 8M   |
| Intel | Core i7 870                    | 8     | 32K | 32K |       | 8M   |
| Intel | Core i7 Q 720                  | 8     | 32K | 32K |       | 6M   |
| Intel | Core i7 Q 740                  | 8     | 32K | 32K |       | 6M   |
| Intel | Xeon X3450                     | 8     | 32K | 32K |       | 8M   |
| Intel | Xeon X3470                     | 8     | 32K | 32K |       | 8M   |
| Intel | Core i7-2600                   | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-2600K                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-2630QM                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-2635QM                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-2670QM                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-2700K                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-2720QM                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-2760QM                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-2820QM                 | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-2860QM                 | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-2960XM                 | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E31230                    | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E31240                    | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E31245                    | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E31260L                   | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E31270                    | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E5620                     | 8     | 32K | 32K | 256K  | 12M  |
| Intel | Xeon E5630                     | 8     | 32K | 32K | 256K  | 12M  |
| Intel | Xeon E5640                     | 8     | 32K | 32K | 256K  | 12M  |
| Intel | Xeon L5630                     | 8     | 32K | 32K | 256K  | 12M  |
| Intel | Xeon X5677                     | 8     | 32K | 32K | 256K  | 12M  |
| Intel | Xeon X5687                     | 8     | 32K | 32K | 256K  | 12M  |
| Intel | Xeon E5-1620 0                 | 8     | 32K | 32K | 256K  | 10M  |
| Intel | Core i7-3610QE                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-3610QM                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-3615QM                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-3630QM                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-3632QM                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-3740QM                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-3770                   | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-3770K                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-3770S                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-3820QM                 | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1230 V2                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1240 V2                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1265L V2               | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1270 V2                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1275 V2                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1290 V2                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-4700HQ                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-4700MQ                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-4702MQ                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-4720HQ                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-4770                   | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-4770K                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-4770T                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-4790                   | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-4790K                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-4790S                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-4800MQ                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-4810MQ                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-4900MQ                 | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-4910MQ                 | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1230 v3                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1231 v3                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1240 v3                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1240L v3               | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1241 v3                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1245 v3                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1265L v3               | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1270 v3                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1271 v3                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E5-1620 v2                | 8     | 32K | 32K | 256K  | 10M  |
| Intel | Xeon E5-2623 v3                | 8     | 32K | 32K | 256K  | 10M  |
| Intel | Xeon E5-2637 v3                | 8     | 32K | 32K | 256K  | 15M  |
| Intel | Core i7-4770HQ                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-4770R                  | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-4850HQ                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-4870HQ                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Xeon E3-1285L v4               | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Atom C2750                     | 8     | 24K | 32K | 1024K |      |
| Intel | Atom C2758                     | 8     | 24K | 32K | 1024K |      |
| Intel | Xeon E5-1620 v4                | 8     | 32K | 32K | 256K  | 10M  |
| Intel | Xeon E5-2623 v4                | 8     | 32K | 32K | 256K  | 10M  |
| Intel | Xeon D-2123IT                  | 8     | 32K | 32K | 1024K | 8M   |
| Intel | Xeon D-1520                    | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Xeon D-1518                    | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Xeon D-1521                    | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-6700                   | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-6700HQ                 | 8     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-6700K                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-6700T                  | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Core i7-6820HQ                 | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1240 v5                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1240L v5               | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1245 v5                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1275 v5                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1280 v5                | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Unknown                        | 8     | 32K | 32K | 256K  | 8M   |
| Intel | Atom C3708                     | 8     | 24K | 32K | 2048K |      |
| Intel | Atom C3758                     | 8     | 24K | 32K | 2048K |      |
| AMD   | Phenom II X6 1055T             | 6     | 64K | 64K | 512K  | 6M   |
| AMD   | Phenom II X6 1090T             | 6     | 64K | 64K | 512K  | 6M   |
| AMD   | FX-6100 Six-Core               | 6     | 16K | 64K | 2048K | 8M   |
| AMD   | FX-6300 Six-Core               | 6     | 16K | 64K | 2048K | 8M   |
| AMD   | Ryzen 5 3500 6-Core            | 6     | 32K | 32K | 512K  | 16M  |
| Intel | Core i5-8400                   | 6     | 32K | 32K | 256K  | 9M   |
| Intel | Core i5-8400T                  | 6     | 32K | 32K | 256K  | 9M   |
| Intel | Core i5-8500                   | 6     | 32K | 32K | 256K  | 9M   |
| Intel | Core i5-8500T                  | 6     | 32K | 32K | 256K  | 9M   |
| Intel | Core i5-8600                   | 6     | 32K | 32K | 256K  | 9M   |
| Intel | Core i5-8600K                  | 6     | 32K | 32K | 256K  | 9M   |
| Intel | Core i5-9400                   | 6     | 32K | 32K | 256K  | 9M   |
| Intel | Core i5-9400F                  | 6     | 32K | 32K | 256K  | 9M   |
| Intel | Core i5-9400T                  | 6     | 32K | 32K | 256K  | 9M   |
| Intel | Core i5-9500                   | 6     | 32K | 32K | 256K  | 9M   |
| Intel | Core i5-9400                   | 6     | 32K | 32K | 256K  | 9M   |
| Intel | Core i5-9600K                  | 6     | 32K | 32K | 256K  | 9M   |
| Intel | Xeon Bronze 3104               | 6     | 32K | 32K | 1024K | 8M   |
| Intel | Xeon Bronze 3204               | 6     | 32K | 32K | 1024K | 8M   |
| AMD   | Phenom II X4 960T              | 4     | 64K | 64K | 512K  | 6M   |
| AMD   | Phenom 9150e Quad-Core         | 4     | 64K | 64K | 512K  | 2M   |
| AMD   | Phenom 9550 Quad-Core          | 4     | 64K | 64K | 512K  | 2M   |
| AMD   | Quad-Core Opteron 2346 HE      | 4     | 64K | 64K | 512K  | 2M   |
| AMD   | Phenom II X4 B50               | 4     | 64K | 64K | 512K  | 6M   |
| AMD   | Phenom II X4 945               | 4     | 64K | 64K | 512K  | 6M   |
| AMD   | Phenom II X4 955               | 4     | 64K | 64K | 512K  | 6M   |
| AMD   | Phenom II X4 965               | 4     | 64K | 64K | 512K  | 6M   |
| AMD   | A6-3400M APU with Radeon HD... | 4     | 64K | 64K | 1024K |      |
| AMD   | FX-4170 Quad-Core              | 4     | 16K | 64K | 2048K | 8M   |
| AMD   | A10-9700 RADEON R7, 10 COMP... | 4     | 32K | 96K | 1024K |      |
| AMD   | A8-9600 RADEON R7, 10 COMPU... | 4     | 32K | 96K | 1024K |      |
| AMD   | A8-4500M APU with Radeon HD... | 4     | 16K | 64K | 2048K |      |
| AMD   | A8-5600K APU with Radeon HD... | 4     | 16K | 64K | 2048K |      |
| AMD   | Athlon X4 750K Quad Core       | 4     | 16K | 64K | 2048K |      |
| AMD   | A10-6800K APU with Radeon H... | 4     | 16K | 64K | 2048K |      |
| AMD   | A8-6500 APU with Radeon HD ... | 4     | 16K | 64K | 2048K |      |
| AMD   | A8-6600K APU with Radeon HD... | 4     | 16K | 64K | 2048K |      |
| AMD   | Athlon X4 760K Quad Core       | 4     | 16K | 64K | 2048K |      |
| AMD   | FX-4300 Quad-Core              | 4     | 16K | 64K | 2048K | 4M   |
| AMD   | A10-7300 Radeon R6, 10 Comp... | 4     | 16K | 96K | 2048K |      |
| AMD   | A10-7850K Radeon R7, 12 Com... | 4     | 16K | 96K | 2048K |      |
| AMD   | RX-427BB with AMD Radeon R7... | 4     | 16K | 96K | 2048K |      |
| AMD   | A10-7860K Radeon R7, 12 Com... | 4     | 16K | 96K | 2048K |      |
| AMD   | PRO A8-8650B R7, 10 Compute... | 4     | 16K | 96K | 2048K |      |
| AMD   | Embedded G-Series GX-420GI ... | 4     | 32K | 96K | 1024K |      |
| AMD   | Opteron X3421 APU              | 4     | 32K | 96K | 1024K |      |
| AMD   | A4-5000 APU with Radeon HD ... | 4     | 32K | 32K | 2048K |      |
| AMD   | A6-1450 APU with Radeon HD ... | 4     | 32K | 32K | 2048K |      |
| AMD   | A6-5200 APU with Radeon HD ... | 4     | 32K | 32K | 2048K |      |
| AMD   | Athlon 5350 APU with Radeon... | 4     | 32K | 32K | 2048K |      |
| AMD   | GX-415GA SOC with Radeon HD... | 4     | 32K | 32K | 2048K |      |
| AMD   | GX-416RA SOC                   | 4     | 32K | 32K | 2048K |      |
| AMD   | GX-420CA SOC with Radeon HD... | 4     | 32K | 32K | 2048K |      |
| AMD   | A6-6310 APU with AMD Radeon... | 4     | 32K | 32K | 2048K |      |
| AMD   | A8-6410 APU with AMD Radeon... | 4     | 32K | 32K | 2048K |      |
| AMD   | E2-6110 APU with AMD Radeon... | 4     | 32K | 32K | 2048K |      |
| AMD   | GX-412TC SOC                   | 4     | 32K | 32K | 2048K |      |
| AMD   | GX-420MC SOC                   | 4     | 32K | 32K | 2048K |      |
| AMD   | GX-424CC SOC with Radeon R5... | 4     | 32K | 32K | 2048K |      |
| AMD   | Ryzen 3 1200 Quad-Core         | 4     | 32K | 64K | 512K  | 8M   |
| AMD   | EPYC 3101 4-Core               | 4     | 32K | 64K | 512K  | 8M   |
| AMD   | Ryzen 3 2200G with Radeon V... | 4     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen 5 2400GE with Radeon ... | 4     | 32K | 64K | 512K  | 4M   |
| AMD   | Athlon 3000G with Radeon Ve... | 4     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen 3 3200G with Radeon V... | 4     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen 3 3200U with Radeon V... | 4     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen 3 3250U with Radeon G... | 4     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen Embedded R1505G with ... | 4     | 32K | 64K | 512K  | 4M   |
| AMD   | Ryzen 3 4300U with Radeon G... | 4     | 32K | 32K | 512K  | 4M   |
| Intel | Xeon                           | 4     | 16K |     | 2M    |      |
| Intel | Xeon                           | 4     | 16K |     | 2M    |      |
| Intel | Celeron J4105                  | 4     | 24K | 32K | 4096K |      |
| Intel | Celeron J4115                  | 4     | 24K | 32K | 4096K |      |
| Intel | Celeron N4100                  | 4     | 24K | 32K | 4096K |      |
| Intel | Pentium Silver J5005           | 4     | 24K | 32K | 4096K |      |
| Intel | Celeron J4125                  | 4     | 24K | 32K | 4096K |      |
| Intel | Pentium Silver N5030           | 4     | 24K | 32K | 4096K |      |
| Intel | Core i3-1005G1                 | 4     | 48K | 32K | 512K  | 4M   |
| Intel | Core i3-8109U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i3-8130U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i3-8145U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Pentium 5405U                  | 4     | 32K | 32K | 256K  | 2M   |
| Intel | Core i3-7020U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-7100U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-7167U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-7200U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-7260U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i5-7267U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i5-7300U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i7-7500U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i7-7600U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core m3-7Y30                   | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core m3-8100Y                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core2 Quad Q6600               | 4     | 32K | 32K | 4M    | 4M   |
| Intel | Core2 Quad Q6700               | 4     | 32K | 32K | 4M    | 4M   |
| Intel | Xeon E5310                     | 4     | 32K | 32K | 4M    | 4M   |
| Intel | Xeon E5320                     | 4     | 32K | 32K | 4M    | 4M   |
| Intel | Xeon X3220                     | 4     | 32K | 32K | 4M    | 4M   |
| Intel | Xeon X3230                     | 4     | 32K | 32K | 4M    | 4M   |
| Intel | Xeon 5140                      | 4     | 32K | 32K | 4M    | 4M   |
| Intel | Core i3-9100F                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Pentium Gold G5400             | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Pentium Gold G5400T            | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Pentium Gold G5420             | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Xeon E-2124                    | 4     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E-2124G                   | 4     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E-2224                    | 4     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E-2224G                   | 4     | 32K | 32K | 256K  | 8M   |
| Intel | Core i3-8100                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i3-8350K                  | 4     | 32K | 32K | 256K  | 8M   |
| Intel | Core i3-9100                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i3-9100F                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i3-9100T                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i3-9350KF                 | 4     | 32K | 32K | 256K  | 8M   |
| Intel | Pentium Gold G5600             | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i3-7100                   | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-7300                   | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i5-7300HQ                 | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-7400                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-7500                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-7500T                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Pentium G4560                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Pentium G4600                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Xeon E3-1220 v6                | 4     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1225 v6                | 4     | 32K | 32K | 256K  | 8M   |
| Intel | Pentium Gold G6500             | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core2 Quad Q8300               | 4     | 32K | 32K | 2M    |      |
| Intel | Core2 Quad Q8400               | 4     | 32K | 32K | 2M    |      |
| Intel | Core2 Quad Q9400               | 4     | 32K | 32K | 3M    |      |
| Intel | Core2 Quad Q9550               | 4     | 32K | 32K | 6M    |      |
| Intel | Core2 Quad Q9650               | 4     | 32K | 32K | 6M    |      |
| Intel | Xeon E5410                     | 4     | 32K | 32K | 6M    |      |
| Intel | Xeon E5420                     | 4     | 32K | 32K | 6M    |      |
| Intel | Core2 Extreme X9650            | 4     | 32K | 32K | 6M    |      |
| Intel | Core2 Quad Q8200               | 4     | 32K | 32K | 2M    |      |
| Intel | Core2 Quad Q9300               | 4     | 32K | 32K | 3M    |      |
| Intel | Core2 Quad Q9450               | 4     | 32K | 32K | 6M    |      |
| Intel | Xeon X3360                     | 4     | 32K | 32K | 6M    |      |
| Intel | Xeon E5504                     | 4     | 32K | 32K |       | 4M   |
| Intel | Xeon E5506                     | 4     | 32K | 32K |       | 4M   |
| Intel | Atom D510                      | 4     |     | 32K |       |      |
| Intel | Atom D525                      | 4     |     | 32K |       |      |
| Intel | Atom N570                      | 4     |     | 32K |       |      |
| Intel | Atom 330                       | 4     |     | 32K |       |      |
| Intel | Core i5 750                    | 4     | 32K | 32K |       | 8M   |
| Intel | Core i5 760                    | 4     | 32K | 32K |       | 8M   |
| Intel | Xeon X3430                     | 4     | 32K | 32K |       | 8M   |
| Intel | Core i3 530                    | 4     | 32K | 32K |       | 4M   |
| Intel | Core i3 M 330                  | 4     | 32K | 32K |       | 3M   |
| Intel | Core i3 M 350                  | 4     | 32K | 32K |       | 3M   |
| Intel | Core i5 650                    | 4     | 32K | 32K |       | 4M   |
| Intel | Core i5 M 430                  | 4     | 32K | 32K |       | 3M   |
| Intel | Core i5 M 520                  | 4     | 32K | 32K |       | 3M   |
| Intel | Core i5 M 540                  | 4     | 32K | 32K |       | 3M   |
| Intel | Core i7 M 620                  | 4     | 32K | 32K |       | 4M   |
| Intel | Core i3 540                    | 4     | 32K | 32K |       | 4M   |
| Intel | Core i3 550                    | 4     | 32K | 32K |       | 4M   |
| Intel | Core i3 M 380                  | 4     | 32K | 32K |       | 3M   |
| Intel | Core i3 U 380                  | 4     | 32K | 32K |       | 3M   |
| Intel | Core i5 650                    | 4     | 32K | 32K |       | 4M   |
| Intel | Core i5 670                    | 4     | 32K | 32K |       | 4M   |
| Intel | Core i5 M 450                  | 4     | 32K | 32K |       | 3M   |
| Intel | Core i5 M 480                  | 4     | 32K | 32K |       | 3M   |
| Intel | Core i5 M 520                  | 4     | 32K | 32K |       | 3M   |
| Intel | Core i5 M 540                  | 4     | 32K | 32K |       | 3M   |
| Intel | Core i5 M 560                  | 4     | 32K | 32K |       | 3M   |
| Intel | Core i5 M 580                  | 4     | 32K | 32K |       | 3M   |
| Intel | Core i7 L 620                  | 4     | 32K | 32K |       | 4M   |
| Intel | Core i7 L 640                  | 4     | 32K | 32K |       | 4M   |
| Intel | Core i7 M 620                  | 4     | 32K | 32K |       | 4M   |
| Intel | Core i3-2100                   | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-2105                   | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-2120                   | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-2130                   | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-2310M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-2330M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-2350M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-2370M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-2300                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-2320                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-2390T                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-2400                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-2400S                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-2405S                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-2410M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-2415M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-2430M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-2435M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-2450M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-2500                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-2500K                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-2500S                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-2520M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-2537M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-2540M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i7-2620M                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i7-2640M                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i7-2677M                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Xeon E31220                    | 4     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E31225                    | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Xeon E5606                     | 4     | 32K | 32K |       | 8M   |
| Intel | Xeon E5-2403 0                 | 4     | 32K | 32K | 256K  | 10M  |
| Intel | Xeon E5-2407 0                 | 4     | 32K | 32K | 256K  | 10M  |
| Intel | Xeon E5-2609 0                 | 4     | 32K | 32K | 256K  | 10M  |
| Intel | Atom D2550                     | 4     |     | 32K |       |      |
| Intel | Atom D2700                     | 4     |     | 32K |       |      |
| Intel | Atom N2600                     | 4     |     | 32K |       |      |
| Intel | Atom N2800                     | 4     |     | 32K |       |      |
| Intel | Celeron J1900                  | 4     | 24K | 32K | 1024K |      |
| Intel | Pentium J2900                  | 4     | 24K | 32K | 1024K |      |
| Intel | Pentium N3520                  | 4     | 24K | 32K | 1024K |      |
| Intel | Celeron J1900                  | 4     | 24K | 32K | 1024K |      |
| Intel | Celeron N2930                  | 4     | 24K | 32K | 1024K |      |
| Intel | Celeron N2940                  | 4     | 24K | 32K | 1024K |      |
| Intel | Pentium N3540                  | 4     | 24K | 32K | 1024K |      |
| Intel | Atom E3845                     | 4     | 24K | 32K | 1024K |      |
| Intel | Celeron J1900                  | 4     | 24K | 32K | 1024K |      |
| Intel | Celeron N2930                  | 4     | 24K | 32K | 1024K |      |
| Intel | Core i3-3110M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-3120M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-3120ME                 | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-3130M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-3210                   | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-3217U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-3220                   | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-3220T                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-3225                   | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-3227U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-3240                   | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-3210M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-3230M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-3317U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-3320M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-3330                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-3337U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-3340                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-3340M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-3360M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-3380M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-3427U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-3450                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-3470                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-3470S                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-3470T                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-3475S                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-3570                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-3570K                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-3570S                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-3520M                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i7-3537U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i7-3540M                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i7-3667U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i7-3687U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Xeon E3-1220 V2                | 4     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1220L V2               | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Xeon E3-1225 V2                | 4     | 32K | 32K | 256K  | 8M   |
| Intel | Core i3-4130                   | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-4130T                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-4150                   | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-4160                   | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-4160T                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-4170                   | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-4330                   | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i3-4350                   | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i3-4360                   | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i5-4200M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-4210M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-4300M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-4310M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-4340M                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-4430                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-4440                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-4460                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-4460S                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-4460T                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-4570                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-4570S                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-4570T                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i5-4570TE                 | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i5-4590                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-4590S                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-4590T                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-4670                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-4670K                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-4690                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-4690K                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i7-4610M                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Xeon E3-1220 v3                | 4     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1220L v3               | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Xeon E3-1225 v3                | 4     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1226 v3                | 4     | 32K | 32K | 256K  | 8M   |
| Intel | Core i3-5005U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-5010U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-5020U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-5200U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-5250U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-5257U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-5300U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-5350U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i7-5500U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i7-5550U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i7-5600U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core M-5Y10c                   | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Xeon E5-2403 v2                | 4     | 32K | 32K | 256K  | 10M  |
| Intel | Xeon E5-2407 v2                | 4     | 32K | 32K | 256K  | 10M  |
| Intel | Core i3-4005U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-4010U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-4030U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-4200U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-4202Y                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-4210U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-4250U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-4260U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-4300U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-4300Y                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-4310U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i7-4500U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i7-4510U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i7-4600U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Celeron N3150                  | 4     | 24K | 32K | 1024K |      |
| Intel | Pentium N3700                  | 4     | 24K | 32K | 1024K |      |
| Intel | Atom x5-Z8350                  | 4     | 24K | 32K | 1024K |      |
| Intel | Celeron J3160                  | 4     | 24K | 32K | 1024K |      |
| Intel | Celeron N3160                  | 4     | 24K | 32K | 1024K |      |
| Intel | Pentium N3710                  | 4     | 24K | 32K | 1024K |      |
| Intel | Atom C2550                     | 4     | 24K | 32K | 1024K |      |
| Intel | Atom C2558                     | 4     | 24K | 32K | 1024K |      |
| Intel | Core i3-6006U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-6100U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-6157U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-6200U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i5-6260U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i5-6300U                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i7-6500U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i7-6560U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i7-6600U                  | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core m5-6Y57                   | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core m7-6Y75                   | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Xeon Silver 4110               | 4     | 32K | 32K | 1024K | 11M  |
| Intel | Pentium D1508                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Atom E3940                     | 4     | 24K | 32K | 1024K |      |
| Intel | Celeron J3455E                 | 4     | 24K | 32K | 1024K |      |
| Intel | Atom E3950                     | 4     | 24K | 32K | 1024K |      |
| Intel | Celeron J3455                  | 4     | 24K | 32K | 1024K |      |
| Intel | Celeron N3450                  | 4     | 24K | 32K | 1024K |      |
| Intel | Pentium J4205                  | 4     | 24K | 32K | 1024K |      |
| Intel | Pentium N4200                  | 4     | 24K | 32K | 1024K |      |
| Intel | Core i3-6100                   | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-6100T                  | 4     | 32K | 32K | 256K  | 3M   |
| Intel | Core i3-6300                   | 4     | 32K | 32K | 256K  | 4M   |
| Intel | Core i5-6300HQ                 | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-6400                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-6440HQ                 | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-6500                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-6500T                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-6600                   | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Core i5-6600K                  | 4     | 32K | 32K | 256K  | 6M   |
| Intel | Xeon E3-1220 v5                | 4     | 32K | 32K | 256K  | 8M   |
| Intel | Xeon E3-1225 v5                | 4     | 32K | 32K | 256K  | 8M   |
| Intel | Atom C3558                     | 4     | 24K | 32K | 2048K |      |
| AMD   | Phenom 8450 Triple-Core        | 3     | 64K | 64K | 512K  | 2M   |
| AMD   | Athlon II X3 455               | 3     | 64K | 64K | 512K  |      |
| AMD   | Turion 64 X2 Mobile Technol... | 2     | 64K | 64K | 512K  |      |
| AMD   | Athlon 64 X2 Dual Core 4000+   | 2     | 64K | 64K | 512K  |      |
| AMD   | Athlon 64 X2 Dual Core 5000+   | 2     | 64K | 64K | 512K  |      |
| AMD   | Athlon 64 X2 Dual Core 4200+   | 2     | 64K | 64K | 512K  |      |
| AMD   | Athlon 64 X2 Dual Core 5000+   | 2     | 64K | 64K | 512K  |      |
| AMD   | Athlon Dual Core 4850e         | 2     | 64K | 64K | 512K  |      |
| AMD   | Athlon Dual Core 5050e         | 2     | 64K | 64K | 512K  |      |
| AMD   | Dual-Core Opteron 2210         | 2     | 64K | 64K | 1024K |      |
| AMD   | Dual-Core Opteron 2218         | 2     | 64K | 64K | 1024K |      |
| AMD   | Dual-Core Opteron 2216         | 2     | 64K | 64K | 1024K |      |
| AMD   | Dual-Core Opteron 2218         | 2     | 64K | 64K | 1024K |      |
| AMD   | Athlon 64 X2 Dual Core 5600+   | 2     | 64K | 64K | 1024K |      |
| AMD   | Dual-Core Opteron 1214 HE      | 2     | 64K | 64K | 1024K |      |
| AMD   | Athlon 64 X2 Dual Core 4200+   | 2     | 64K | 64K | 512K  |      |
| AMD   | Athlon 64 X2 Dual Core 4600+   | 2     | 64K | 64K | 512K  |      |
| AMD   | Phenom II X2 545               | 2     | 64K | 64K | 512K  | 6M   |
| AMD   | Turion II Ultra Dual-Core M... | 2     | 64K | 64K | 1024K |      |
| AMD   | Athlon II X2 250               | 2     | 64K | 64K | 1024K |      |
| AMD   | Turion II Neo K625 Dual-Core   | 2     | 64K | 64K | 1024K |      |
| AMD   | Turion II Neo N40L Dual-Core   | 2     | 64K | 64K | 1024K |      |
| AMD   | Turion II Neo N54L Dual-Core   | 2     | 64K | 64K | 1024K |      |
| AMD   | Turion X2 Dual-Core Mobile ... | 2     | 64K | 64K | 512K  |      |
| AMD   | A4-3300 APU with Radeon HD ... | 2     | 64K | 64K | 512K  |      |
| AMD   | C-50                           | 2     | 32K | 32K | 512K  |      |
| AMD   | E-350                          | 2     | 32K | 32K | 512K  |      |
| AMD   | G-T56N                         | 2     | 32K | 32K | 512K  |      |
| AMD   | C-70 APU with Radeon HD Gra... | 2     | 32K | 32K | 512K  |      |
| AMD   | E-300 APU with Radeon HD Gr... | 2     | 32K | 32K | 512K  |      |
| AMD   | E-350D APU with Radeon HD G... | 2     | 32K | 32K | 512K  |      |
| AMD   | E-450 APU with Radeon HD Gr... | 2     | 32K | 32K | 512K  |      |
| AMD   | E1-1200 APU with Radeon HD ... | 2     | 32K | 32K | 512K  |      |
| AMD   | E2-1800 APU with Radeon HD ... | 2     | 32K | 32K | 512K  |      |
| AMD   | G-T40E                         | 2     | 32K | 32K | 512K  |      |
| AMD   | G-T40N                         | 2     | 32K | 32K | 512K  |      |
| AMD   | A4-9125 RADEON R3, 4 COMPUT... | 2     | 32K | 96K | 1024K |      |
| AMD   | A6-9225 RADEON R4, 5 COMPUT... | 2     | 32K | 96K | 1024K |      |
| AMD   | A9-9425 RADEON R5, 5 COMPUT... | 2     | 32K | 96K | 1024K |      |
| AMD   | A9-9430 RADEON R5, 5 COMPUT... | 2     | 32K | 96K | 1024K |      |
| AMD   | A4-6300 APU with Radeon HD ... | 2     | 16K | 64K | 1024K |      |
| AMD   | A6-6400K APU with Radeon HD... | 2     | 16K | 64K | 1024K |      |
| AMD   | Opteron X3216 APU              | 2     | 32K | 96K | 1024K |      |
| AMD   | A4-1200 APU with Radeon HD ... | 2     | 32K | 32K | 1024K |      |
| AMD   | E1-2500 APU with Radeon HD ... | 2     | 32K | 32K | 1024K |      |
| AMD   | GX-217GA SOC with Radeon HD... | 2     | 32K | 32K | 1024K |      |
| AMD   | E1-6010 APU with AMD Radeon... | 2     | 32K | 32K | 1024K |      |
| AMD   | GX-222GC SOC with Radeon R5... | 2     | 32K | 32K | 1024K |      |
| Intel | Pentium 4                      | 2     | 16K |     | 1M    |      |
| Intel | Pentium 4 3.20GHz ("Genuine... | 2     | 16K |     | 1M    |      |
| Intel | Xeon                           | 2     | 16K |     | 2M    |      |
| Intel | Pentium 4                      | 2     | 16K |     | 2M    |      |
| Intel | Pentium D                      | 2     | 16K |     | 1M    |      |
| Intel | Pentium D                      | 2     | 16K |     | 1M    |      |
| Intel | Pentium D                      | 2     | 16K |     | 2M    |      |
| Intel | Pentium D                      | 2     | 16K |     | 2M    |      |
| Intel | Pentium 4                      | 2     | 16K |     | 2M    |      |
| Intel | Pentium D                      | 2     | 16K |     | 2M    |      |
| Intel | Celeron J4005                  | 2     | 24K | 32K | 4096K |      |
| Intel | Celeron N4000                  | 2     | 24K | 32K | 4096K |      |
| Intel | Core Duo L2400                 | 2     | 32K | 32K | 2M    |      |
| Intel | T2250                          | 2     | 32K | 32K | 2M    |      |
| Intel | T2400                          | 2     | 32K | 32K | 2M    |      |
| Intel | Celeron 3865U                  | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Celeron 3965U                  | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Core2 Duo T7300                | 2     | 32K | 32K | 4M    | 4M   |
| Intel | Core2 Duo T7700                | 2     | 32K | 32K | 4M    | 4M   |
| Intel | Core2 Duo E6550                | 2     | 32K | 32K | 4M    | 4M   |
| Intel | Core2 Duo E6750                | 2     | 32K | 32K | 4M    | 4M   |
| Intel | Core2 Duo E6850                | 2     | 32K | 32K | 4M    | 4M   |
| Intel | Core2 Duo L7500                | 2     | 32K | 32K | 4M    | 4M   |
| Intel | Core2 Duo T7300                | 2     | 32K | 32K | 4M    | 4M   |
| Intel | Core2 Duo T7400                | 2     | 32K | 32K | 4M    | 4M   |
| Intel | Core2 Duo T7500                | 2     | 32K | 32K | 4M    | 4M   |
| Intel | Core2 Duo T7700                | 2     | 32K | 32K | 4M    | 4M   |
| Intel | Xeon 3065                      | 2     | 32K | 32K | 4M    | 4M   |
| Intel | Celeron E1500                  | 2     | 32K | 32K | 512K  |      |
| Intel | Core2 Duo E4500                | 2     | 32K | 32K | 2M    |      |
| Intel | Core2 Duo E4600                | 2     | 32K | 32K | 2M    |      |
| Intel | Core2 Duo T5850                | 2     | 32K | 32K | 2M    |      |
| Intel | Core2 Duo T5870                | 2     | 32K | 32K | 2M    |      |
| Intel | Core2 Duo T5900                | 2     | 32K | 32K | 2M    |      |
| Intel | Core2 Duo T7100                | 2     | 32K | 32K | 2M    |      |
| Intel | Core2 Duo T7250                | 2     | 32K | 32K | 2M    |      |
| Intel | Pentium Dual E2140             | 2     | 32K | 32K |       |      |
| Intel | Pentium Dual E2160             | 2     | 32K | 32K |       |      |
| Intel | Pentium Dual E2180             | 2     | 32K | 32K |       |      |
| Intel | Pentium Dual E2200             | 2     | 32K | 32K |       |      |
| Intel | Pentium Dual T2370             | 2     | 32K | 32K |       |      |
| Intel | Pentium Dual T2390             | 2     | 32K | 32K |       |      |
| Intel | Pentium Dual T3200             | 2     | 32K | 32K |       |      |
| Intel | Pentium Dual T3400             | 2     | 32K | 32K |       |      |
| Intel | Core2 4300                     | 2     | 32K | 32K | 2M    |      |
| Intel | Core2 6300                     | 2     | 32K | 32K | 2M    |      |
| Intel | Core2 T5500                    | 2     | 32K | 32K | 2M    |      |
| Intel | Core2 T5600                    | 2     | 32K | 32K | 2M    |      |
| Intel | Xeon 3040                      | 2     | 32K | 32K | 2M    |      |
| Intel | Core2 6320                     | 2     | 32K | 32K | 4M    | 4M   |
| Intel | Core2 6400                     | 2     | 32K | 32K | 2M    |      |
| Intel | Core2 T5500                    | 2     | 32K | 32K | 2M    |      |
| Intel | Core2 T5600                    | 2     | 32K | 32K | 2M    |      |
| Intel | Core2 T7200                    | 2     | 32K | 32K | 4M    | 4M   |
| Intel | Core2 T7400                    | 2     | 32K | 32K | 4M    | 4M   |
| Intel | Xeon 3070                      | 2     | 32K | 32K | 4M    | 4M   |
| Intel | Celeron G4900                  | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Celeron G3930                  | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Celeron E3400                  | 2     | 32K | 32K |       |      |
| Intel | Core2 Duo E7400                | 2     | 32K | 32K | 3M    |      |
| Intel | Core2 Duo E7500                | 2     | 32K | 32K | 3M    |      |
| Intel | Core2 Duo E8400                | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo E8500                | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo E8600                | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo L9300                | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo L9400                | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo P7450                | 2     | 32K | 32K | 3M    |      |
| Intel | Core2 Duo P7550                | 2     | 32K | 32K | 3M    |      |
| Intel | Core2 Duo P8400                | 2     | 32K | 32K | 3M    |      |
| Intel | Core2 Duo P8600                | 2     | 32K | 32K | 3M    |      |
| Intel | Core2 Duo P8700                | 2     | 32K | 32K | 3M    |      |
| Intel | Core2 Duo P9400                | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo P9600                | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo T6400                | 2     | 32K | 32K | 2M    |      |
| Intel | Core2 Duo T6570                | 2     | 32K | 32K | 2M    |      |
| Intel | Core2 Duo T6600                | 2     | 32K | 32K | 2M    |      |
| Intel | Core2 Duo T9400                | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo T9550                | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo T9600                | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo U9400                | 2     | 32K | 32K | 3M    |      |
| Intel | Pentium Dual-Core E5200        | 2     | 32K | 32K | 2M    |      |
| Intel | Pentium Dual-Core E5300        | 2     | 32K | 32K | 2M    |      |
| Intel | Pentium Dual-Core E5500        | 2     | 32K | 32K | 2M    |      |
| Intel | Pentium Dual-Core E5700        | 2     | 32K | 32K | 2M    |      |
| Intel | Pentium Dual-Core E5800        | 2     | 32K | 32K | 2M    |      |
| Intel | Pentium Dual-Core E6500        | 2     | 32K | 32K | 2M    |      |
| Intel | Pentium Dual-Core E6600        | 2     | 32K | 32K | 2M    |      |
| Intel | Pentium Dual-Core E6700        | 2     | 32K | 32K | 2M    |      |
| Intel | Pentium Dual-Core T4200        | 2     | 32K | 32K |       |      |
| Intel | Pentium Dual-Core T4300        | 2     | 32K | 32K |       |      |
| Intel | Pentium Dual-Core T4400        | 2     | 32K | 32K |       |      |
| Intel | Pentium Dual-Core T4500        | 2     | 32K | 32K |       |      |
| Intel | Xeon E3110                     | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo E7200                | 2     | 32K | 32K | 3M    |      |
| Intel | Core2 Duo E7300                | 2     | 32K | 32K | 3M    |      |
| Intel | Core2 Duo E8135                | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo E8300                | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo E8400                | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo E8500                | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo L9300                | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo L9400                | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo P7350                | 2     | 32K | 32K | 3M    |      |
| Intel | Core2 Duo T8100                | 2     | 32K | 32K | 3M    |      |
| Intel | Core2 Duo T8300                | 2     | 32K | 32K | 3M    |      |
| Intel | Core2 Duo T9300                | 2     | 32K | 32K | 6M    |      |
| Intel | Core2 Duo T9400                | 2     | 32K | 32K | 6M    |      |
| Intel | Xeon E5502                     | 2     | 32K | 32K |       | 4M   |
| Intel | Xeon E5503                     | 2     | 32K | 32K |       | 4M   |
| Intel | Atom D410                      | 2     |     | 32K |       |      |
| Intel | Atom N450                      | 2     |     | 32K |       |      |
| Intel | Atom N455                      | 2     |     | 32K |       |      |
| Intel | Atom N470                      | 2     |     | 32K |       |      |
| Intel | Atom 230                       | 2     |     | 32K |       |      |
| Intel | Atom N270                      | 2     |     | 32K |       |      |
| Intel | Atom N280                      | 2     |     | 32K |       |      |
| Intel | Atom Z550                      | 2     |     | 32K |       |      |
| Intel | Pentium G6950                  | 2     | 32K | 32K |       | 3M   |
| Intel | Pentium G6950                  | 2     | 32K | 32K |       | 3M   |
| Intel | Pentium P6100                  | 2     | 32K | 32K |       | 3M   |
| Intel | Pentium P6200                  | 2     | 32K | 32K |       | 3M   |
| Intel | Unknown                        | 2     |     | 32K |       |      |
| Intel | Celeron 847                    | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Celeron 867                    | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Celeron B815                   | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Celeron B830                   | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Celeron B840                   | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Celeron G550                   | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Pentium 967                    | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Pentium G620                   | 2     | 32K | 32K | 256K  | 3M   |
| Intel | Pentium G630T                  | 2     | 32K | 32K | 256K  | 3M   |
| Intel | Pentium G640                   | 2     | 32K | 32K | 256K  | 3M   |
| Intel | Pentium G645                   | 2     | 32K | 32K | 256K  | 3M   |
| Intel | Pentium G860                   | 2     | 32K | 32K | 256K  | 3M   |
| Intel | Pentium II_Pentium II Xeon_... | 2     | 16K | 16K | 512K  |      |
| Intel | Atom D2500                     | 2     |     | 32K |       |      |
| Intel | Celeron J1800                  | 2     | 24K | 32K | 1024K |      |
| Intel | Celeron N2820                  | 2     | 24K | 32K | 1024K |      |
| Intel | Celeron J1800                  | 2     | 24K | 32K | 1024K |      |
| Intel | Celeron N2807                  | 2     | 24K | 32K | 1024K |      |
| Intel | Celeron N2840                  | 2     | 24K | 32K | 1024K |      |
| Intel | Atom E3825                     | 2     | 24K | 32K | 512K  |      |
| Intel | Atom E3827                     | 2     | 24K | 32K | 512K  |      |
| Intel | Celeron J1800                  | 2     | 24K | 32K | 1024K |      |
| Intel | Celeron 1005M                  | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Celeron 1007U                  | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Celeron 1037U                  | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Celeron G1610T                 | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Pentium 2117U                  | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Pentium G2020                  | 2     | 32K | 32K | 256K  | 3M   |
| Intel | Pentium G2020T                 | 2     | 32K | 32K | 256K  | 3M   |
| Intel | Pentium G2030                  | 2     | 32K | 32K | 256K  | 3M   |
| Intel | Pentium G2120                  | 2     | 32K | 32K | 256K  | 3M   |
| Intel | Celeron G1820                  | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Celeron G1840                  | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Celeron G1850                  | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Pentium G3220                  | 2     | 32K | 32K | 256K  | 3M   |
| Intel | Pentium G3260                  | 2     | 32K | 32K | 256K  | 3M   |
| Intel | Pentium G3420                  | 2     | 32K | 32K | 256K  | 3M   |
| Intel | Celeron 3215U                  | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Pentium 3805U                  | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Celeron 2955U                  | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Celeron 2980U                  | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Pentium 3558U                  | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Celeron N3050                  | 2     | 24K | 32K | 1024K |      |
| Intel | Celeron J3060                  | 2     | 24K | 32K | 1024K |      |
| Intel | Celeron N3060                  | 2     | 24K | 32K | 1024K |      |
| Intel | Atom C2358                     | 2     | 24K | 32K | 1024K |      |
| Intel | Celeron 3855U                  | 2     | 32K | 32K | 256K  | 2M   |
| Intel | Atom E3930                     | 2     | 24K | 32K | 1024K |      |
| Intel | Celeron J3355                  | 2     | 24K | 32K | 1024K |      |
| Intel | Celeron N3350                  | 2     | 24K | 32K | 1024K |      |
| Intel | Pentium G4400                  | 2     | 32K | 32K | 256K  | 3M   |
| Intel | Pentium G4400T                 | 2     | 32K | 32K | 256K  | 3M   |
| Intel | Atom C3338                     | 2     | 24K | 32K | 2048K |      |
| AMD   | Sempron 210U                   | 1     | 64K | 64K | 256K  |      |
| AMD   | Athlon 2650e                   | 1     | 64K | 64K | 512K  |      |
| AMD   | Sempron 2600+                  | 1     | 64K | 64K | 128K  |      |
| AMD   | Athlon LE-1600                 | 1     | 64K | 64K | 1024K |      |
| AMD   | Athlon II X2 240               | 1     | 64K | 64K | 1024K |      |
| AMD   | Sempron 145                    | 1     | 64K | 64K | 1024K |      |
| AMD   | V120                           | 1     | 64K | 64K | 512K  |      |
| AMD   | G-T44R                         | 1     | 32K | 32K | 512K  |      |
| AMD   | Geode Integrated by PCS ("A... | 1     | 64K | 64K | 128K  |      |
| Intel | Pentium 4 Mobile               | 1     | 8K  |     | 512K  |      |
| Intel | Pentium 4                      | 1     | 8K  |     | 512K  |      |
| Intel | Celeron                        | 1     | 8K  |     | 128K  |      |
| Intel | Mobile Intel Celeron 2.20GH... | 1     | 8K  |     | 256K  |      |
| Intel | Mobile Intel Pentium 4 - M     | 1     | 8K  |     | 512K  |      |
| Intel | Pentium 4 2.66GHz ("Genuine... | 1     | 8K  |     | 512K  |      |
| Intel | Pentium 4 2.80GHz ("Genuine... | 1     | 16K |     | 1M    |      |
| Intel | Celeron                        | 1     | 16K |     | 256K  |      |
| Intel | Celeron                        | 1     | 16K |     | 256K  |      |
| Intel | Pentium III Mobile             | 1     | 16K | 16K | 512K  |      |
| Intel | Mobile Intel Pentium III - ... | 1     | 16K | 16K | 512K  |      |
| Intel | Mobile Intel Pentium III - ... | 1     | 16K | 16K | 512K  |      |
| Intel | Pentium M                      | 1     | 32K | 32K | 2M    |      |
| Intel | Pentium M 1.60GHz ("Genuine... | 1     | 32K | 32K | 2M    |      |
| Intel | Pentium M 1.70GHz ("Genuine... | 1     | 32K | 32K | 2M    |      |
| Intel | Celeron M                      | 1     | 32K | 32K |       |      |
| Intel | Pentium M                      | 1     | 32K | 32K | 2M    |      |
| Intel | Pentium M 1.60GHz ("Genuine... | 1     | 32K | 32K | 2M    |      |
| Intel | Core Solo U1400                | 1     | 32K | 32K | 2M    |      |
| Intel | Celeron 440                    | 1     | 32K | 32K | 512K  |      |
| Intel | Core2 Solo U3500               | 1     | 32K | 32K | 3M    |      |
| Intel | Celeron ("GenuineIntel" 686... | 1     | 16K | 16K | 256K  |      |
| Intel | Pentium III ("GenuineIntel"... | 1     | 16K | 16K | 512K  |      |
| Intel | Pentium III_Pentium III Xeo... | 1     | 16K | 16K | 512K  |      |
| Intel | Pentium III                    | 1     | 16K | 16K | 256K  |      |
| Intel | Pentium III                    | 1     | 16K | 16K | 256K  |      |
| Intel | Pentium M                      | 1     | 32K | 32K | 1M    |      |
| VIA   | Nano U3500                     | 1     |     |     |       |      |
