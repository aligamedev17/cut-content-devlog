# Cut Content: the work, commit by commit

Every commit of the (private) project repository, in order: local time (Tashkent, UTC+5) and what was done.
The jam ran from 12 November 05:00 to 16 November 01:59 UTC. Commits before it are tool setup only (declared in the
submission). 102 commits.


## 2026-11-11

- `09:38` Initial JamProject setup before MegaJam start
- `09:56` Notes: MSVC 14.50 installed, MCP startup order
- `10:09` OBS control for devlog recording
- `10:24` Notes: audio sources without WeLoveIndies

## 2026-11-12

- `00:24` Notes: NVIDIA RTX Award conditions and risks
- `00:35` Notes: theme Director's Cut, idea candidates, jam start proof plan
- `00:48` Notes: official theme brief and what it means for us
- `01:05` Notes: theme explanation from kickoff stream transcript
- `01:13` Notes: gnome house concept draft
- `01:19` Notes: drop gnome concept, Cut Content draft, downloaded Fab assets
- `01:25` Notes: key Official Rules points (sourced assets not scored, English only, VCS proof)
- `01:35` Notes: vault asset sizes
- `01:43` Notes: core feature set decided (flush, CUT freeze, TAKE 2 rewind)
- `01:47` Fab library export and shortlist for Cut Content; editor on second monitor
- `01:50` Notes: museum heist setting, route draft, asset sourcing steps
- `02:04` Notes: source projects downloaded, plugin check for 5.9
- `02:05` Notes: source content sizes
- `02:08` Notes: hero via custom MetaHuman, props via Tripo
- `02:13` Notes: skills and lessons from past projects (Roach Riot, character pipeline)
- `02:16` Notes: jam rules confirmed (key screenshots only, AI voices, commits)
- `02:25` Notes: private GitHub repo and push routine
- `10:58` Day 1: CutContent C++ module (director subsystem, CUT freeze, TAKE 2 rewind, guards, lasers, shutters, toilet flush, deleted scenes, HUD), merged config, sourced assets list
- `11:24` Level L_Museum: gameplay layout builder, guards on navmesh, walk speeds, alarm chase, debug console commands, self-test in PIE
- `11:31` Night lighting pass, laser material, screenshot tour tools, CCGhost
- `11:49` Props made in Blender by script (toilet, film reel, film canister), procedural SFX, voice line generator, pipe ride, guard uniform, reel display light
- `11:56` AI voice lines (Chatterbox director, Kokoro producer) checked with Whisper, event logs, CCStatus, laser hum, start-inside trigger fix, scripted playthrough test (6/6)
- `11:58` Docs: GDD, day 1 status
- `12:08` Set dressing props and cinema exhibits (Blender scripts), AI paintings and posters, procedural music, tiles material, dressing scripts, music system in the director subsystem
- `12:14` Docs: how to resume, devlog draft, lessons
- `12:23` Level dressing applied (corridor, restroom, Museum of Cinema gallery), BGR colour fix for lights, window helpers
- `12:30` Title card, pause and wrap screens, film fonts (Bebas Neue OFL, Special Elite Apache), retake counter, debug keys of the sample blocked, music under menus
- `12:32` Spotted/caught/rewind test in PIE
- `12:43` Hero and guards wear a MetaHuman visual with our tinted cloth material (thief black, guard uniform), usage flags fix
- `13:17` Playtest fixes: walk by default and run on Shift, guards walk and face their path, level seams (divider off the door line, annex flush with the hall, tiles), doorway unblocked, triggers kept inside rooms, line of sight for use, objective line and world marker, hero rim light on its own channel, pinned MetaHuman LOD
- `13:28` Game feel pass (code): slower walk, softer mouse, any key on the title, hero lights ride the camera, toilet exit in front of the bowl, alarm bell that settles; alley props and materials (scripts)
- `13:50` Guard cap, alley dressed and tuned, FPS in the self-test, build trimmed (editor-only MetaHuman tools, unused sample characters never cooked)
- `13:55` WIP: game feel pass 2 in source (NOT built or tested yet): suspicion bars, hearing, pickup slow motion, scene card. Itch page draft, cover image, stop-point notes
- `16:28` Feel pass 2 built and tested (flow 6/6, spotted 4/4): spotted test stands in a clear spot in the beam, MetaHuman Animator plugin editor-only
- `17:00` Vault approach puzzles: laser corridor that needs CUT!, the producer's sensor door that ignores CUT! and needs TAKE 2, sweeping security camera over the CUT canister, guard 2 circles the centre wall, grace period after a retake, slam sound and two new voice lines, puzzle test (9 checks), tests start PIE themselves, editor no longer throttles in the background
- `17:08` Guards talk (six barks, third AI voice), camera warning beep, corridor panels with floor guide strips, lit sign over the producer's door, shot script for puzzle states
- `17:09` Docs: evening of day 1 state, puzzle design in the GDD, five new lessons
- `17:23` Bot playtest: CCWalk walks the hero through the whole film with real input (23 checks), modelled CCTV camera and steel vault shutter, two more commentary beats (past the lasers, door beaten), laser curtains closer so walking fits one CUT!, tracker data kept out of the cook, project name
- `17:32` Paintings hang the right way up (canvas master with swap and flip, orientation read from the mesh), two wide paintings for the sideways canvases, camera above the paintings, devlog shots
- `17:45` Playtest 3 fixes: film cans carry a label (deleted scene number and name) and the marker shows what it points at, toilet lid stands up on the tank, van cargo area is an open box with crates instead of a solid block, hints and lines say where CUT! and TAKE 2 are needed
- `17:46` Notes: playtest 3
- `17:56` Packaging: always cook /Game/CutContent (voices, music, fonts and outfits are loaded by path and were missing from the package), never cook only the MetaHuman tracker subfolders (build 978 MB)
- `20:04` Our own people: the thief and three security guards made with MetaHuman Creator in the jam (different faces, skin tones and builds), uniforms and the thief's clothes cut from each body in Blender, collar from the face's neck, caps fitted per head, beanie; 4th deleted scene STUNT DOUBLE (cardboard standee, guards walk over to check it), alley finale with security at the van, police lights and siren, alley checkpoint; end credits with your outtakes, the producer's verdict and five lost-footage reels; playtest 4: subtitles no longer squeeze, slower run, toilet lid against the tank; packaging cooks all of CutContent, MetaHuman tracker data left out; bot playtest 31 checks
- `20:16` Packaging: always cook only the runtime folders (MetaHuman Creator sources are editor only), Day2a 1172 MB self-test 12/12; notes

## 2026-11-13

- `00:01` Characters done properly: MetaHuman Creator presets in Epic's parametric garments, no more twitching
- `00:42` Package 1427 -> 1163 MB, packaged camera switch, cast cleanup
- `00:43` tools/run_game.sh: the only way to start the packaged game (refuses while an editor or another game runs, waits for a real exit)
- `03:02` Act 6 THE FILM ARCHIVE with JUMP CUT; the flush as a gag; guards no longer hop; gags on set
- `04:32` The getaway grows: police drone over the alley, save and continue, a dressed corridor, more comedy
- `04:57` Flickering tubes, in-game director's notes, continue hides what was taken
- `05:35` Title card over a slow arc round the reel in the vault; no more hood-cam in tight aisles
- `06:05` Three more gags, JUMP CUT on the gamepad d-pad, beauty stills for the page
- `06:34` The director's notes on a scene after three failed takes; every spoken line in the log
- `06:38` Dev log: night 2 summary; notes: Day3e and the morning checklist
- `06:55` Calmer flickering tubes, later idle remarks (never during a retake)
- `07:00` Notes: Day3f is the build for the morning playtest
- `08:05` Act 7, SOUND STAGE B, and the sixth deleted scene: MONTAGE
- `09:04` The van guard takes smoke breaks; donuts on set; montage plays safe with the other tricks
- `09:10` Notes: Day3h for the next playtest
- `10:50` Room tone by place, stage lights in the grid, no sliding into a scene after being caught
- `10:51` Notes: leave OBS off when the director has stopped it
- `11:05` Guards feel a montage too; a commit script that respects OBS being off
- `11:09` Signs with jokes around the building; continue tested from the sound stage
- `11:53` Gamepad key names, the extended edition, two cross-floor bugs
- `11:59` Dev log: day 3, the sound stage and MONTAGE; notes: Day3j
- `12:56` Banter in long silences, a pause card with the mouse setting and a fresh take
- `14:04` Playtest fixes: the way out of a toilet, a camera that stays out of walls, puddles without a grid
- `14:34` Restroom tiles with grey grout, road cases at the stage door
- `16:29` Scene 8 THE BACKLOT (sandbox act) and Niagara effects
- `18:31` Scenes 9-11: Picture Palace, Foley Stage, Stunt Hangar
- `18:45` Action animations for stunts and the flush; the somersault no longer spins the camera
- `19:33` Zip line trolley in his hands; crash mats are solid
- `19:48` Our own hang and tuck animations; legs no longer splay in the air
- `20:12` Scenes 12-13: the Scene Dock (push a flat) and the Creature Shop (the monster)
- `20:49` Spare dinosaur head on the bench is decoration (no collision), walk test tolerant of the van guard
- `23:14` Cap the 8K baked body textures and 4K groom masks at 2048 (build size)
- `23:48` Trailer, dev log, brighter theatre/foley/dock, trailer mode
- `23:56` Final build Day4a, submission bundle notes, dev log stills

## 2026-11-14

- `00:29` Trailer preview, 720p (for viewing on a phone)
- `00:56` Trailer take two: whole situations from the player camera, the game's own sound
- `01:39` Air ram: a wind-up on the plate, a stunt camera, a real landing
- `03:51` Sound mix, guards on a behaviour tree, a real air ram, a true mirror, five new scenes
- `04:54` Voices for scenes 14 to 18, a guard on an errand keeps his eyes on it, opened shadows
- `05:35` The stunt double holds a guard's attention; the build's self-test checks the new systems
- `05:49` Effects and our own animations always cook; the build's self-test checks them (build Day5b)
- `12:08` Scenes 19 to 22, a filmed playthrough and its fixes, screen tests for the guards
- `12:16` Build Day6a: twenty-three scenes, self-test clean at 59 to 74 fps; trailer card and dev log

## 2026-11-15

- `03:03` Build Day7a: the last night's polish, scene selection for a fresh install, the making-of film
- `03:12` Docs: the itch dev log post and the submission checklist kept with the sources
- `03:22` Handoff notes: where the project stands, what is in flight, what to do next
- `03:34` The picture chooses itself on a first launch; a readable objective line; scene selection named first
- `03:41` The creature shop's monster and its masks, second casting
- `03:42` Handoff notes: the probe and the creature are in, Day7b is on its way
- `04:38` Build Day7b: all 21 playtests green, self-test clean; dev log and checklist for it
- `04:57` Handoff notes: the other-storey sleep rule is in flight
- `05:01` Guards on another storey sleep: the museum was slow because of people nobody could see
- `05:01` Handoff notes: Day7c is on its way
- `05:44` Build Day7c: all 21 playtests green, self-test clean; the sleep rule's real result written down
