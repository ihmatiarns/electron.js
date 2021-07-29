# Electron.js
Build Cross Platform Desktop with Electronjs &amp; Nativefier

Required Instalation :
- Install Node.js (https://nodejs.org/en/download/)
  or use CLI <code>apt-get install -y nodejs</code>
- Install Nativefier <code>npm install nativefier -g</code>
- Install Wixtooll in (https://github.com/wixtoolset/wix3/releases)<br>[Click on install and wait until the setup finishes, when it's done you will find the files of the installation at C:\Program Files (x86)\WiX Toolset v3.11\. After installing WiX you will need to expose the binaries path of the WiX Toolset to the PATH environment variable of Windows]

IT'S A BEAUTIFUL MAGIC :)
1. For a simple create desktop app :<br>
  - <code>nativefier "http://domain.com"</code><br>or<br>
  <code>nativefier --single-instance -i "<u>icon directory</u>" --name "<u>Name App</u>" "http://domain.com/"</code>
2. Create .exe installer
  - Open and setup file "build_installer.js"
  - run a file with command
  <code>#node build_installer</code>
