# READ.MD

The full documentation of this project lives in **[READ.ME](READ.ME)**.

## Short version

**SHADOW Module Suite v1.0.0** — 146 modules in one flashable ZIP.

| | |
|---|---|
| 📦 **Download** | [`dist/SHADOW_AllInOne_v1.0.0.zip`](dist/SHADOW_AllInOne_v1.0.0.zip) (1.7 MB) |
| 📖 **Full manual** | [`READ.ME`](READ.ME) — every module explained |
| 🔢 **Modules** | 146, all named `SHADOW_<Module>` |
| 🧠 **Root** | KernelSU (also works with Magisk) |
| 📱 **Device** | Poco M2 Pro (beryllium), Snapdragon 660, Adreno 512 |
| 🧱 **Metamodule** | not required |

### Install
1. Copy `SHADOW_AllInOne_v1.0.0.zip` to the phone.
2. KernelSU app → *Modules* → *Install from storage* → pick the zip.
3. Reboot.

### What it does
- **Gaming** — CPU/GPU boost, frame-drop removal, FPS unlock, latency tuning.
- **Touch enhancer** — higher sampling rate, palm rejection, ghost-touch fix, edge protection.
- **Fast charging** — charge current + voltage ceiling raised, smart tapering, overnight guard.
- **Ultra battery backup** — no app is ever killed by Doze, app standby or background restriction.
- **Plus** CPU, GPU, thermal, storage, network, display, audio, UI, privacy and tooling modules.

### Switch profile
```sh
sh /data/adb/shadow/control.sh profile gaming        # 130 modules
sh /data/adb/shadow/control.sh profile performance   # 130 modules
sh /data/adb/shadow/control.sh profile balanced      # 116 modules
sh /data/adb/shadow/control.sh profile battery        #  98 modules
```

See **[READ.ME](READ.ME)** for the complete module list, the log locations and the recovery steps.

<sub>Built by ShadowDarkXd00</sub>
