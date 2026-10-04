NULLSPACE Theme Studio
A PS5 theme editor I've been working on for jailbroken consoles. I made it so you can find and preview wallpapers and other UI files without digging through folders and guessing what you're replacing.
Current build: v8
Made with: PS5 firmware 13.42 and etaHEN in mind. Other setups aren't confirmed yet.
Features
- Scans wallpaper and theme assets, including files under /system_ex/vsh_asset.
- Previews supported images and MP4 videos.
- Imports images from USB and saves them on the PS5.
- Converts PNGs to a compatible target's DDS format, including .dds.zst when supported, and uses the correct target filename.
- Prepares and replaces supported files when the destination is writable.
- Backs up original files and lets you restore them.
- Shows headers, hex data and readable strings for files that can't be fully previewed. Supported UTF-8 text files can be edited with backups.
How to use it
1. Jailbreak your PS5 and load the payloads you normally use.
2. Send NULLSPACE-Theme-Studio-v8.elf to your PS5 with your ELF loader.
3. If the app registers, open NULLSPACE from the PS5 Media section.
4. Scan the assets, choose a file and check its preview.
5. Import your replacement and use the available backup, prepare or replace option.
6. Rescan to refresh the list. Use Restore Original if you need to undo a change.
Important
This doesn't unlock protected system folders. If a destination is read-only, the app keeps the backup or prepared file rather than forcing a write. Some file types are inspection-only, so seeing readable strings or hex doesn't mean they've been decrypted. DDS conversion also depends on the original texture format.
Be careful when changing system files, and always keep your backups. I haven't confirmed this build on every firmware or jailbreak setup.
