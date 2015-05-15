PVRShaderEditorColours
==========

Colour schemes for PVRShaderEditor & PVRShaderEditComponent (used in PVRTrace and PVRShaman).

Installation
--------------
PVRShaderEditor_solarized-dark.plist example below:
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
Known issues
--------------
The *.plist's temporary directory (used for storing the output of the CLI shader profiling compilers) is '/tmp/' which will work on OS X & Linux, but may cause problems on Windows. The directory can be altered through PVRShaderEditorGUI's "Preferences"-->"Compiler Settings" tab, or by editing the *.plist directly.

Colour schemes
==========
<a href="https://github.com/joemdavis/PVRShaderEditorColours/blob/master/PVRShaderEditor_solarized-dark.plist">Solarized (Dark)</a>
--------------

Based on Ethan Schoonover's <a href="http://ethanschoonover.com/solarized">Solarized (Dark).</a>
