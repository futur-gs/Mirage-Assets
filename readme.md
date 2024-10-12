# Readme

## Instruction

Windows has a default limitation of 128 for the some gamma adjustments. This can be overridden by creating the following registry key:

```registry
[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ICM]
"GdiIcmGammaRange"=dword:00000100
```

You can simply download the `ICM.reg` and run it to create the key. Then restart Windows to take effect.
