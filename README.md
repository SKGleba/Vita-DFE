# Vita-DFE
DFE - Debug Features Enabler ( or Dex/Devkit Features Extender if you have a dex/tool unit ) for Playstation Vita, Playstation Vita TV and Playstation TV.
- Current state: Open Beta, no ETA.
# Basic Usage:
- Enable/Disable debug features
   - Installs/Uninstalls a ITU lv3 Project Deepload
- Install/Uninstall MultiHen Framework
   - Installs/Uninstalls MultiHen framework along with bighooker and vshpatcher.
- Current Status
   - Displays some info about system status (gathered by this app).
- Exit
# Features:
- Only ITU lv3 Project DeepLoad:
    - Spoof the device to a internal test unit 
    - QA flags stuff (More info soonTM)
    - Allow loading all module types ( CEX/DEX/TOOL )
    - Set activation type to prototype/qa (3222+ days)
    - Spoof CP Data
    - Allow debugging via USB
    - More minor patches
- ITU lv3 Project DeepLoad + MultiHen framework:
    - Spoof the device to a internal test unit 
    - QA flags stuff (More info soonTM)
    - Allow loading all module types ( CEX/DEX/TOOL )
    - Set activation type to prototype/qa (3222+ days)
    - Spoof CP Data
    - Allow debugging via USB
    - Spoof DevMode
    - Allow all debug/qa menu display, all debug/qa nsk features
    - + like 90 other QA & Debug related spoofs/patches
    - Allow loading sd2vita as sa0/sd0/os0/vs0 (Hold X + UP/DOWN/LEFT/RIGHT)
    - Allow usage of TaiHen API on lower level, by adding modules to either enso bootconfig or to configs located in ur0:mhen/ (lowp.txt for lowest level plugins/patches and vshp.txt for vsh patches). Configs loading can be skipped - SQUARE + UP for vshp.txt and SQUARE + DOWN for lowp.txt, TRIANGLE for both.
# WARNING
- Enso logo has been replaced by PS logo
- Install MultiHen framework AFTER enabling debug features, if you forget to do so - hold TRIANGLE at boot and then enable debug features.
- The Enable/Disable debug features option flashes Project Deepload into MBR, remember that every flash brings risk of a PERMAMENT, UNRECOVERABLE BRICK, so I recommend doing it on a clean os (freshly after boot and without bigger plugins).
Hold L on boot to boot with plugins disabled, if you dont you may brick
- boot_config.txt now loads from ur0:tai/boot_config.txt, if you load from ux0: you will have to switch to using ur0:
- boot_config.txt is also replaced, you can find your old config at ur0:mhen/origbcfg
you can manually add your plugins back to the new boot_config.txt
# CREDITS
Big thanks to Samilop Iter, Castelo, Princess-Of-Sleeping, Yifan Lu, Team Molecule, and all alpha testers.
