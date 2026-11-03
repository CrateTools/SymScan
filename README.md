# SymScan Lite

**Find every link on your Windows computer. Free.**

SymScan Lite lists the links on your disks (symbolic links, junctions, mounted volumes and subst drives, plus hardlinks with a deep scan), shows where each one points, and tells you whether the target is still there. Scanning only reads your disks: it never changes, moves or deletes anything.

## Features

- Scans the whole computer, or only the folders you choose
- Lists symbolic links, junctions, mounted volumes and subst drives, and hardlinks with a deep scan
- Shows each link's location, what it points to, and the volume it is on
- Checks whether each target still exists, and checks again on demand (**Check now**)
- Search by path, target or volume
- Saves or downloads the results as a plain-text report
- **Restart as administrator** to scan folders that need higher access
- Works offline, keeps everything in its own folder, and sends nothing anywhere

## Download

1. Go to **[Releases](../../releases)** and download **SymScan-Lite.zip**.
2. Before you extract it, right-click the zip, choose **Properties**, tick **Unblock**, and press **OK**. This avoids most Windows warnings.
3. Extract it into a folder your user account can write to, such as `C:\SymScan`. Do not use Program Files, and avoid folders that OneDrive syncs.
4. Double-click **SymScan-Lite.exe**.

Windows may say **"Windows protected your PC"** the first time. Click **More info**, then **Run anyway**. This happens because SymScan is not code-signed yet.

This repository holds the app only. The source code is not published.

## Using it

1. Double-click **SymScan-Lite.exe**. A SymScan console window opens, and your browser shows SymScan. Keep the console open while you work: closing it stops SymScan.
2. Click **New Link Scan**. Tick the disks or folders you want (expand a disk to pick a folder inside it), then click **Scan selected**. Leave everything unticked to scan the whole computer; on large disks that can take a long time.
3. When the scan finishes, the **Links** page lists every link. Click a link to see its details.
4. Click **Save results** to keep a report as a text file.

If the top bar says **Limited access**, some folders were skipped. Click **Restart as administrator** and choose **Yes** on the Windows prompt.

SymScan Lite does not keep a history of scans. Save the report if you want to keep a result.

## Requirements

- Windows 10 or Windows 11 (not Windows in S mode)
- No installation, no internet connection, no extra software
- SymScan is not code-signed yet: security software may flag it the first time, and Windows 11's **Smart App Control** blocks it while turned on. If your antivirus quarantines it, restore it and allow it.

SymScan Lite v1.0 · by CrateTools

---

# Also available: SymScan Technician

## Create links and drives. Manage them on every PC you look after.

**Links, Folder Disks and Network Disks: made in a few clicks, tracked on every machine, run from one screen.**

SymScan Lite shows you the links. **SymScan Technician puts you in control of them.** Create junctions and symbolic links, turn folders into drive letters, and map network shares for one user or every user. Do it on this PC, or on any PC you have paired on your network. SymScan keeps track of everything it made, on every machine, so you always know what is set up where.

When something breaks, SymScan tells you, and you can fix it on the spot.

**[Get SymScan Technician on Gumroad (soon)](GUMROAD_LINK_TECHNICIAN)**

### Create and manage: the big three

**1. Links, made and tracked.** Two side-by-side folder panes: pick the folder, drop it where the link should go, see a preview of exactly what will run, and confirm. Junctions and symbolic links. Every link you make goes into your **Link List**, kept after a restart, so you can check it, open it or remove it later.

**2. Folder Disk: any folder as a drive letter.** Make a folder show up in Explorer as its own disk, for you, for one named person, or for every user of the PC. It comes back at every sign-in.

**3. Network Disk: shares mapped the way you need them.** Map network shares to drive letters for you, for one named person, or for every user of the PC, restored at sign-in. When something stops it, SymScan says whether the server, the share or the sign-in is the reason.

### Everything above, on every machine

**Site Manager** pairs your other Windows PCs through a small agent. Then create links, set up Folder Disks and map Network Disks on them as if you were sitting there. Every machine's Link List and history stays in one place, and you can still look at them while that machine is offline.

A server, a client's PC, a virtual machine in the next room: one screen for all of them. Works with Windows 10 and 11 on the same network, on physical PCs and virtual machines.

### Find what broke, and fix it

**Find every link, every time.** Scan the whole computer or only the folders you pick. See each link's location, its target, the volume it sits on, and whether the target is still there. Check again any time with one click.

**Fix the ones that break.** Spot a link whose target is gone, open its folder or its target with one click, then remove the link or make it again with Link Tools.

**Real problems, not false alarms.** SymScan tells real problems apart from things that are only waiting, such as a drive that connects when someone signs in, or a disk that is unplugged. You fix what needs fixing and leave the rest alone.

**Find what you did not make.** The **Not SymScan** tag marks links and drive letters that SymScan did not create, so the unexpected ones stand out.

**A history you can trust.** Every scan is saved, for every machine. Reopen any scan and search it. Deleting a saved scan is safe: SymScan first shows which of its links still exist on disk, and asks twice.

**Private and offline.** SymScan Technician keeps everything in its own folder, works without an internet connection, and sends nothing anywhere. Nothing phones home.

Built for technicians who set up and maintain PCs, inherit messy disks, clean up after migrations, and need to prove what is and is not linked.

## Lite vs Technician

| Feature | Lite (free, GitHub) | Technician |
|---|:---:|:---:|
| **Create and remove links (Link Tools, side-by-side Pick and Drop)** | ✗ | ✔ |
| **Link List: every link you made, kept after a restart** | ✗ | ✔ |
| **Folder Disk: give a folder its own drive letter, for one or every user** | ✗ | ✔ |
| **Network Disk: map network shares, for one or every user** | ✗ | ✔ |
| **Site Manager: create, manage and scan on other PCs, through the SymScan Agent** | ✗ | ✔ |
| **Link List and history kept for each machine, also while it is offline** | ✗ | ✔ |
| Clear "things to check" vs "waiting, nothing to fix" | ✗ | ✔ |
| "Not SymScan" tag on links and letters SymScan did not create | ✗ | ✔ |
| Saved scan history, with search and safe two-step delete | ✗ | ✔ |
| Open location / target folder | ✗ | ✔ |
| Settings: background tasks and uninstall clean-up check | ✗ | ✔ |
| Scan the whole computer or chosen folders | ✔ | ✔ |
| Link list, details and search | ✔ | ✔ |
| Check now | ✔ | ✔ |
| Save / download report | ✔ | ✔ |
| Restart as administrator | ✔ | ✔ |

**[Get SymScan Technician on Gumroad (soon)](GUMROAD_LINK_TECHNICIAN)**

### Technician requirements

- Windows 10 or Windows 11 (not Windows in S mode), mixed networks of both supported
- No installation, no internet connection
- Some actions need administrator rights, such as symbolic links and drives for every user
- Site Manager needs the SymScan Agent running on the other PC and Windows file sharing working between your PCs. Setting up your own network, accounts and permissions is your responsibility; the included manual covers the common setups.

---

## License

SymScan Lite is free to use, at home or at work. It may not be sold, redistributed, changed or reverse engineered. No support is provided. See [LICENSE.txt](LICENSE.txt) for the full terms.

Copyright (c) 2026 CrateTools. All rights reserved.
