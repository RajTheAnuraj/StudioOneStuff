# Serum Preset mapping
Open `C:\Users\anura\AppData\Roaming\Xfer\Serum\SerumPrefs.json`
Modify the following
```
"CCForRocker Preset +": 102,
"CCForRocker Preset -": 103,
```
The numbers are CC numbers from midi

```"Enable CCForRockers": 1,```

# StudioOne Manual Control Link

Go to the folder `C:\Users\anura\AppData\Roaming\PreSonus\Studio One 5\User Devices`
There will be subfolders based on manufacturers.
Create the surfaces.xml file for corresponding *.device file
The contents of the file is in `Arturia Control Surface.surface.xml` file in this repo
This is for the mackie protocol
