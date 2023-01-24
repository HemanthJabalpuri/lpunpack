```
~/lpunpack/test $ python3 ../lpunpack.py super-metadata.img -d
Slot 0:
Metadata version: 10.2
Metadata size: 1000 bytes
Metadata max size: 65536 bytes
Metadata slot count: 3
Block device table:
------------------------
  Partition name: super
  First sector: 2048
  Size: 7583301632 bytes
------------------------
Group table:
------------------------
  Name: default
  Maximum size: 0 bytes
------------------------
  Name: mot_dp_group_a
  Maximum size: 7579107328 bytes
------------------------
  Name: mot_dp_group_b
  Maximum size: 7579107328 bytes
------------------------
Partition table:
------------------------
  Name: product_a
  Group: mot_dp_group_a
  Extents:
    0 .. 5895927 linear super 2048
offset at 1048576 byte, size is 3018715136 bytes
------------------------
  Name: product_b
  Group: mot_dp_group_b
  Extents:
empty partition
------------------------
  Name: system_a
  Group: mot_dp_group_a
  Extents:
    0 .. 1746159 linear super 5898240
offset at 3019898880 byte, size is 894033920 bytes
------------------------
  Name: system_b
  Group: mot_dp_group_b
  Extents:
    0 .. 76175 linear super 7645184
offset at 3914334208 byte, size is 39002112 bytes
------------------------
  Name: system_ext_a
  Group: mot_dp_group_a
  Extents:
    0 .. 1858519 linear super 7723008
offset at 3954180096 byte, size is 951562240 bytes
------------------------
  Name: system_ext_b
  Group: mot_dp_group_b
  Extents:
empty partition
------------------------
  Name: vendor_a
  Group: mot_dp_group_a
  Extents:
    0 .. 1513143 linear super 9582592
offset at 4906287104 byte, size is 774729728 bytes
------------------------
  Name: vendor_b
  Group: mot_dp_group_b
  Extents:
empty partition
------------------------
```
