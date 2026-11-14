# Sourced assets (not made by us, not scored)

Listed for the submission ("may include sourced assets, but they must be noted"). These folders are not tracked in git; they come from the original packs.

| Pack | Source | License | Folders in JamProject/Content | Used for |
|---|---|---|---|---|
| Game Animation Sample (UE 5.8 version) | Epic Games, Fab | Fab (Epic sample) | Blueprints, Characters/*, Input (IA_*, IMC_Sandbox), Audio, MetaHumans, Misc, Widgets, Levels, IsolatedExamples, Movies | Player and guard locomotion (motion matching), base character; the source poses our own action animations are assembled from (`tools/ue_scripts/make_poses.py`: A_CC_Hang, A_CC_Tuck, A_CC_PushWalk, A_CC_Dummy); the mannequins in the prop store (SKM_Manny_Simple and SKM_Quinn_Simple from Characters/UE5_Mannequins, in our own plastic) |
| Museum and Gallery - Archinteriors Vol 10 Scene 1 | Evermotion, Fab | Fab Professional | AIUE5_vol10_01, Splash | Museum interior meshes and materials |
| UE First Person template | Epic Games | UE EULA | FirstPerson, Characters/Mannequins, Input/Actions, LevelPrototyping | Project base (not used in the game) |
| MetaHuman Creator presets: Mateo, Jorge, Isaiah, Dominic, Aoi, Walter (faces, bodies, hair, brows, beards) | Epic Games, MetaHuman Creator plugin (UE 5.9) | UE EULA (MetaHuman) | CutContent/Characters/Thief, GuardA, GuardB, GuardC, Common (built output); CutContent/Characters/Sources/MHC_* (editor only) | The thief and the five security guards |
| Fonts Ink Free and Segoe Print (handwriting on the corridor whiteboard, rendered into a texture only; the font files are not in the project) | Microsoft, Windows 11 | Windows font license | CutContent/Textures/T_Art_CutList (made by `tools/make_cutlist.py`) | The producer's cut list |
| MetaHuman parametric garments: Hoodie, Slim Jeans Variants, Hightops, Tucked T Shirt Variants, Cargo Pants, Boots | Epic Games, Fab (free) | Fab Standard | CutContent/Characters/Sources/Wardrobe (materials and textures are used by the built characters; outfit sources are editor only) | Clothes of the thief and the guards |
| Interface Sounds 1.0 and RPG Sounds (short recordings: latch, door, book, cloth, knife, switch, click) | Kenney (kenney.nl), downloaded from OpenGameArt | CC0 | Art/Source/Kenney (source files, with the licenses); mixed into CutContent/Audio/SFX_Clapper, Denied, Pickup, CamBeep, Standee, Splice, Pop, Interact by `tools/gen_sfx.py` | Sound effects that were pure synthesis at first and sounded like beeps |
| Niagara template system FountainLightweight | Epic Games, Niagara plugin (engine content) | UE EULA | CutContent/FX (14 systems duplicated from it and set up by `tools/ue_scripts/make_fx.py`) | All particle effects |

Everything else under `Content/CutContent` and all code in `Source/CutContent` is made during the jam. For the characters our own work is the casting, the colours of the clothes, the SECURITY lettering (painted into the shirt's print layer, font Bebas Neue, OFL), the guard cap (our mesh) and the scripts that assemble it all (`tools/ue_scripts/make_people.py`, `dress_people.py`, `finish_people.py`, `tools/make_security_print.py`).

Removed from the project copy to keep the build small (not used by the game): Game Animation Sample demo characters `Characters/Paragon`, `Characters/Echo`, `Characters/UE4_Mannequin` and their blueprints in `Blueprints/RetargetedCharacters`.
