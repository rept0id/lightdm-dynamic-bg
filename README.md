# lightdm-dynamic
Dynamic background switcher for LightDM

After installation, you can run "LightDM Dynamic Configuration" from "applications" menu, if you wish to change background's topic (keywords) and source.

However, I daresay you may not wish to alter topic, as the default tends to give one goosebumps. 😁

Default topic is cockpits and source is "Unsplash".

```
.
├── DEBIAN
│   ├── control --> .deb package's conf file
│   ├── postinst --> -//- after install script
│   └── prerm --> -//- uninstall script
├── etc
│   └── lightdm-dynamic
│       └── lightdm-dynamic.conf --> conf
├── LICENSE
├── README.md
└── usr
    ├── bin
    │   ├── lightdm-dynamic --> main script
    │   └── lightdm-dynamic-conf --> "LightDm Dynamic Configuration" script (Zenity)
    └── share
        └── applications
            └── lightdm-dynamic-conf.desktop --> "LightDm Dynamic Configuration" desktop entry (for "applications" menu)
```
