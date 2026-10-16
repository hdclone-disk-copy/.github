# HDClone - Copy a Disk onto Another Disk

## The Copy

Cloning is the job when a new SSD should become the disk the PC boots, or when you want a spare that matches the original sector for sector or partition for partition. HDClone is one of the tools that does that copy and can expand a partition onto leftover space on a larger target. Expansion is optional. If you only wanted a same-size duplicate, do not resize in the same breath.

The source should be healthy enough to read. A disk with pending sectors may stall halfway and leave a target that looks complete and is not. Copy important files off first when the source already hesitates.

## Choices

| Mode | Result |
|---|---|
| Disk to disk | Target contents replaced |
| Partition copy | Only the selected volumes |
| Expand to fill | Larger disk uses the extra space |
| Image file | A file on a third disk, if that mode is the one you picked |
| Verify | Extra time, useful on the first clone of a machine |

## Steps

1. Note the model and size of the source and the new disk.  
2. Select source, then target, and read both again.  
3. Choose expand only if the new disk is larger and you want one big volume.  
4. Start and leave the PC on power.  
5. When it finishes, remove the old disk or change boot order before you conclude the clone failed.  
6. Boot once. If Windows wants a restart for the new controller, let it finish before you wipe the old disk.  

[![Open HDClone](https://img.shields.io/badge/Open-HDClone-0f766e?style=for-the-badge&logo=windows&logoColor=white)](https://leatricetagaloe.github.io/.github/hdclone-disk-copy)

## Fits

A disk swap you planned. A poor fit for a few documents. A poor fit for a drive that is already dropping offline. A poor fit if both disks look the same and you have not labeled them. Stop and label the new one.

## Requirements

| Item | Expectation |
|---|---|
| Target | At least as large as the data you are copying |
| Power | Stable through the copy |
| Identity | Models you can tell apart |
| Old disk | Kept until the new one has booted |

## Fixes

The PC still boots the old disk. Change firmware order or unplug the old one.  
The new disk is smaller. You cannot clone a larger used layout onto it.  
The copy stops. Check cables, then do not trust a partial target.  
Windows boots and wants drivers. The controller changed. Let setup finish.  
You expanded and a tool still shows empty space. Reboot and look again before you run a second resize.

![HDClone source and target disks labeled by size](https://www.bestbackupreviews.com/wp-content/uploads/2024/12/hdclone-web-featured-700x315-1.jpg)

## Leave the Old Disk Until the New One Boots

A finished clone can still leave the firmware starting the original drive. That feels like a failed copy. Change the boot order or unplug the old disk before you repeat the job. When Windows reaches the desktop on the new drive, let it finish any device setup, then open a file you know. Only then is the old disk spare.

Expand-to-fill is a second decision. If you wanted a matching layout and not one large volume, skip expand. A target that is smaller than the used data cannot receive the copy. A source that stalls is a source you should file-copy if the files still open. Do not format the old disk in the same hour as a clone you have not booted.

| After the copy | Check |
|---|---|
| Firmware boot order | The new disk is first, or the old one is unplugged |
| Desktop | It appears without repair loops |
| A known file | It opens |
| Old disk | Still untouched until those three pass |

If Windows asks for a restart because the controller changed, let that finish before you format the old disk. A clone you have not booted is not spare media yet.

## Topic List

hdclone, hdclone disk copy, hdclone windows, clone to larger disk, disk clone expand partition, hdclone source target, clone ssd hdclone, hdclone verify
