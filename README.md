# ServerMods


!WINDOWS ONLY!                                                                                                                                                           
!Important!                                                                                                                                                               
To install the mods press on the green "<> code" button and press "download zip"                                                                                         
next open your .minecraft folder by doing -> win+r then entering "%appdata%"                                                                                             
Navigate to .minecraft\mods (Note > If you do not have this folder you will need to create one)                                                                           

Texturepack:                                                                                                                                                             
If you want the texture pack to work and be auto updated do this:                                                                                                         
Load up Minecraft                                                                                                                                                         
Open your .minecraft folder by doing -> win+r then entering "%appdata%"                                                                                                   
Navigate to this directory .minecraft\config\resclone                                                                                                                     
open up "config.json"                                                                                                                                                     
paste this code into the file and select save:                                                                                                                           

{

  // The packs to be loaded by resclone
  packs: [
      {
        "fetcher": "github",
        "source": "PhantomFaze/empirePack",
        "name": "empire"
        "forceDownload": true
      }
    ],
  // Whether to prune unused packs from the cache
  pruneUnused: true
}
