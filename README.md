# Bystander

The boat, as delivered, has PBR and Blinn-Phong textures.

With the advent of PBR, we are using less Ambient Occlusion (AO) layers in the textures, as the graphics system is providing shadows. Also, many of the PBR textures are tiled textures that don't work with a single non-tiled AO map. In some cases you can use a tiled material and a non tiled Base Colour. This gives an AO map under the tiled texture. So before you change the textures, just look at the default PBR materials and the tiling as well as the default Blinn-Phong textures and their tiling.

The Awning is scripted. So texture information has to be used by the script. Texture UUID, tile repeats, offsets and transparency. To get this information into the script, if you are wanting to change the awning texture, we have included an online Awning texture editor. Sit on the boat, and type Awning Edit in localchat. You will be given a URL in localchat. This URL is hosted on Second Life servers, and does not store any of your personal information. No IP address is saved. You can edit the Awning texture UUID, Alpha, Offset, Repeats, Rotation (in Radians) and Tint here. To see the updates, show the awning if it is not already set up (by saying Awning Setup in localchat) and then unfold or fold the awning (by saying Awning in local chat).

Please see the manual of the boat for more information. Click the book onthe boat dashboard.