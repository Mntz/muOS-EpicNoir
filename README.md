# muOS Epic Noir skin

This is mainly a port of the Epic Noir theme, [originally by c64-dev & Chicuelo](https://github.com/c64-dev/es-theme-epicnoir).

All images are fully recreated to fit muOS and it contains a nice suitable home screen.\
Epic White is a brand new version of Noir with brighter colours.

Installation steps below.

![homeloop](https://github.com/user-attachments/assets/f0141a34-09ad-4781-94fc-c0eabe3b99fc)

![Epic-White-for-34XX640](https://github.com/user-attachments/assets/ab46d90a-a3dd-47e5-b1d0-e353cff26594)

![gba](https://github.com/user-attachments/assets/f3a3f21a-b351-4dcb-80a8-fbbaed7b5bcf)

![megadrive](https://github.com/user-attachments/assets/3208bff0-fdd9-40b9-8d48-bed8583b7b05)


## Theme installation

1. Download Epic.Noir.muxthm (or White) from Releases
2. Store the muxthm file on your muOS SD card under the ARCHIVE folder
3. Install the theme using Archive Manager (under Applications)
4. Go to **Settings/Configuration > Customisation**. Set Content Box Art to **Fullscreen + Front**
5. Open **Theme Picker** under Settings/Configuration and select Epic Noir or Epic White

## Additional system art

**A. Automated installation**
1. Download the System.Images.Install.Pack.muxupd
2. Store the muxupd file on your muOS SD card under the ARCHIVE folder
3. Install the console art using Archive Manager (under Applications)

**B. Manual installation**
1. Download Epic.Noir.-.System.Images.zip (or White)
2. Extract and store the image files under MUOS/info/catalogue/Folder/box (This can be on SD1 or SD2, depending on your setup)
3. Make sure the filenames match your rom folder names

**C. Uninstalling system art**
1. If you switch themes, the installed folder art will still be displayed.
2. Uninstalling is a manual process. Delete the images files under MUOS/info/catalogue/Folder/box

## Art scraping

The following steps use Scrappy to get rom art but you can use any other application like Skraper that supports custom xml's.

1. Download and install ![Scrappy](https://github.com/gabrielfvale/scrappy/releases) in muOS
2. Download epic.gradient.scraper.zip from releases
3. Add the xml file to /SD1/MUOS/application/.scrappy/templates
4. Add the png file to Scrappy's mask folder under the resources folder
5. You can now select epic-gradient as artwork option in Scrappy

![muOS_20241110_1328_0](https://github.com/user-attachments/assets/a5da05a1-e14c-45aa-aca5-e67e0433d43f)
![muOS_20241110_1338_0](https://github.com/user-attachments/assets/e9fcfff4-5c9d-4cf7-aff0-9a130302e337)

