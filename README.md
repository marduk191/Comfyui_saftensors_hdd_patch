An update to utils.py for speeding up reading of safetensor files from spinning HDD or NAS. This should not be needed for SSD. Expected average unpatched speed is 30-35 MB/S, and 199+ MB/S (as fast as the drive will go) after patching.
