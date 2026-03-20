# Table of content

- [Device Encryption Suspended](#device-encryption-suspended)
- [Turn on auto unlock drive](#turn-on-auto-unlock-drive)

---
# Device Encryption Suspended

![Device Encryption Suspended](./Media_Files/D1.png)
## Solution :book:

- **Step 1:** Turn off encryption by following command prompt
```c
manage-bde D: -off
```

> `D:` is drive name. Replace my drive letter with yours.

- **Step 2:** Turn on encryption by following command prompt
```c
manage-bde D: -on
```
![](./Media_Files/D2.png)

---

![D3](./Media_Files/D3.png)
