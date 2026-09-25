This directory is loaded each mount point change for custom content above the main mount point content
You may place VPKs directly in custom such as:
	tf2_medallium/custom/my_customcontent.vpk

Or loose files in sub-directories such as:
	tf2_medallium/custom/my_content/materials
	tf2_medallium/custom/my_content/models
	tf2_medallium/custom/my_content/sound

Note that the following directory structure is NOT correct:
	tf2_medallium/custom/models/my_model.mdl

That will add the directory tf2_medallium/custom/models as a search path, in which case the
file my_model.mdl actually exists at the root of the game's virtual filesystem.
