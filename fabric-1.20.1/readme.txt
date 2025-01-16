Installation: 

Steps 1 through 3 can be done before the server updates.
Step 4 should only be done after the server updates.

1. Run: fabric-installer-1.0.1.exe. 

	1a. Choose minecraft version 1.20.1 and the default loader version (0.16.10) (see figure "doc/1a fabric installer settings.png"), and press 'install'.
	
2. Find/make a fabric installation 

	2a. If the "Installations" dropdown contains "fabric-loader-1.20.1" or similar, you can skip to step 3.
	
	2b. If a fabric 1.20.1 installation doesn't exist yet, go to the "Installations" tab and click "new installation"
	
	2c. Under the "version" dropdown select "release fabric-loader-1.16.10-1.20.1". If you want to change any other settings like a clever name for the installation, you can; then press OK. This is the installation you'll select to access the server once it updates. (see figure "doc/2c create installation inside launcher.png")

3. Run (once per computer): ZeroTier One.msi.

	You can skip this step if ZeroTier has already been installed on your machine.

	3a. Go to discord or your text messages and get the 'network id' of our server.

	3b. Zerotier will put a new icon in your taskbar. 

	3c. Right click the icon, select 'join network', and paste in the 'network id'.

    3d. When the 'Friendly Idiots' network is visible in the right click menu, you're connected.

4. Copy the folders 'mods' and 'resourcepacks'.

	4a. Go to: C:\Users\%username%\AppData\Roaming\.minecraft

	4b. Delete/archive the previous 'mods' and 'resourcepacks' folders and paste the new 'mods' and 'resourcepacks' folders from the zip file in their place into the '.minecraft' folder. 

5. Launch minecraft and enable resource packs

	5a. Select the new installation option for 'fabric 1.20.1' from the homepage dropdown or from the Installations tab (see figure "doc/5a  select installation inside launcher.png"). Launch that.

	5b. At the Multiplayer vs Singleplayer selection window, choose 'options' -> 'resource packs'. 

	5c. Select the resource pack 'OliverRemund'. ('RenaissanceAndBaroque' has not been updated.)

6. Connect to the server and goof off.