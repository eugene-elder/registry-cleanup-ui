# registry-cleanup-ui (public Pages)

Installed-apps checklist for uninstall selection on Eugene7.

Live: https://eugene-elder.github.io/registry-cleanup-ui/

Loads/saves `inventory.xml` from the private repo `eugene-elder/registry-cleanup` via GitHub Contents API.

1. Create a fine-grained PAT with **Contents: Read and write** on `eugene-elder/registry-cleanup` only.
2. Open the Pages site, paste PAT → Remember on this device → Load from Git → check apps to uninstall → Save.
3. Registry orphan sweep comes **after** uninstalls — this inventory is ARP apps only.
4. Never put the PAT in this repo.
