# BEST-MODULES

### SHADOW Module Suite — 146 modules in one ZIP
**Target: Poco M2 Pro (beryllium) · Snapdragon 660 · Adreno 512 · KernelSU · custom ROMs**

| | |
|---|---|
| 📦 **Download** | [`dist/SHADOW_AllInOne_v1.0.0.zip`](dist/SHADOW_AllInOne_v1.0.0.zip) |
| 📖 **Full manual** | [`READ.ME`](READ.ME) |
| 🔢 **Modules** | 146 |
| 🧩 **Groups** | 13 (Gaming, Touch, Charge, Battery, Performance, GPU, Thermal, Network, Display, Audio, System, Privacy, Tools) |
| 🧠 **Root** | KernelSU (also works with Magisk) |
| 🧱 **Metamodule** | not required |
| 📱 **Device** | Poco M2 Pro (beryllium) and other SDM660 phones |

---

## Install

1. Download `SHADOW_AllInOne_v1.0.0.zip` to the phone.
2. **KernelSU** app → *Modules* → *Install from storage* → pick the zip.
   *(Magisk app → Modules → Install from storage → pick the zip)*
3. Reboot.
4. Every `SHADOW_*` module now shows up on its own in the Modules tab.

## What you get

- **Gaming** — CPU/GPU boost, frame-drop removal, FPS unlock, latency and network tuning.
- **Touch enhancer** — higher sampling rate, palm rejection, ghost-touch fix, edge protection.
- **Fast charging** — charge current and voltage ceiling raised, smart tapering, overnight guard.
- **Ultra battery backup** — every app taken out of Doze, app standby and background restriction, refreshed every 10 minutes so nothing of yours is ever killed.
- Plus CPU, GPU, thermal, storage, network, display, audio, UI, debloat/privacy and tooling modules.

## Profiles

One command moves the entire suite between profiles:

```sh
sh /data/adb/shadow/control.sh profile gaming        # 130 modules
sh /data/adb/shadow/control.sh profile performance   # 130 modules
sh /data/adb/shadow/control.sh profile balanced      # 116 modules
sh /data/adb/shadow/control.sh profile battery        #  98 modules
```

The battery backup, the doze killer, the background release and the control
centre stay on in every profile.

## Safety

- Every module is an ordinary KernelSU module — switch it off or remove it at any time.
- `SHADOW_BootLoopGuard` disables the risky modules by itself if the phone fails to boot three times in a row.
- Modules only write to sysfs/proc nodes that really exist; anything your ROM does not expose is logged as `skip` and ignored.

---

<sub>Built by ShadowDarkXd00 · v1.0.0</sub>
