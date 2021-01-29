Read Me
Importer/Exporter for the R:TW CAS 3d file format
By Vercingetorix (pauldls@hotmail.com)
Current Version: 0.69b
Last updated 1/18/05

Legal disclaimer: I do not work for CA or Activision and this tool is strictly unofficial. Use at you own risk, neither I or any party but you the user can be held accountable to any damage caused be use of this tool.

Please do not distribute this file without permission of me the author and/or Strategic Command Center. 

For any support questions and/or feedback, visit our main page for where to go and more updates. 



How to run:
	To run the script save it to your 3dsmax\scripts folder. In max go to the utilities tab and hit run script, open the script. Select from the utilities drop down R:TW import/export.

Some things you should be aware of:

There are two types of meshes static and dynamic. Static is weapons shields etc. Dynamic is the unit or animal, that is to say dynamic meshes have a skin modifier and have different bones affecting it. A static object simply has a bone as a parent. Dynamic meshes don't have any parent.

For all dynamic meshes you must have the skin modifier at the top of the stack. Vertex weighting is not supported in RTW, so a vertex may not have more then one bone influencing it.

If you change the UV's and then when you export in the game and the texture is messed up it is because in max one vertex may have more then one texture vertex while in RTW a vertex may only have one texture vertex. To fix this, break vertices that have more then one texture vertex assigned to them. If you do this you will have to skin the new vertices with the skin modifier (that is if the mesh is dynamic).

Every CAS file specifies the texture it uses. The exporter will put as the path of the texture "\texture\theTexture.tga". Where "theTexture.tga" is the filename of the diffuse map, which the model uses. Currently the exporter does not support multiple textures.

Item files now supported!


This project is proudly sponsored and hosted by Strategic Command Center. Enjoy!




Warning: Changing this file and/or any other file in this download is a strict violation of its copyright and immediate actions will be taken.
