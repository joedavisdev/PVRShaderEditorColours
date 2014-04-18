pvr-plists
==========

A collection of preconfigured *.plist files for PowerVR Graphics SDK Utilities

Solarized (Dark) Colour Scheme
--------------
This modification will set the colour scheme of the shader editor module (used by PVRShaderEditor, PVRShaman & PVRTrace) to <a href="http://ethanschoonover.com/solarized">Solarized (Dark).</a>
<br><b>Known issue:</b> The *.plist's temporary directory (used for storing the output of the CLI shader profiling compilers) is '/tmp/' which will work on OS X & Linux, but may cause problems on Windows. The directory can be altered through PVRShaderEditorGUI's "Preferences"-->"Compiler Settings" tab, or by editing the *.plist directly.

<ol>
<li>Rename the file</li>
  <ul>
  <li><b>Windows:</b> PVRShaderEditor_solarized-dark.plist --> PVRShaderEditor.plist</li>
  <li><b>OS X & Linux:</b> PVRShaderEditor_solarized-dark.plist --> com.powervr.PVRShaderEditor.plist</li>
  </ul>
<li>Move the renamed file to the Imagination *.plist directory</li>
  <ul>
  <li><b>Windows:</b> C:\Users\[your_name_here]\AppData\Roaming\Imagination Technologies\</li>
  <li><b>OS X & Linux:</b> ~/.pvrconfig/Imagination\ Technologies/</li>
  </ul>
</ol>
