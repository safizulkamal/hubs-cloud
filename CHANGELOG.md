2022-02-07
---------
Hubs Cloud Release Highlights
- [Hubs] Audio zones - https://github.com/mozilla/hubs/pull/4399 
- [Hubs] Audio debugging view - https://github.com/mozilla/hubs/pull/4249 
- [Hubs] Enable server API - https://github.com/mozilla/hubs/pull/4753 
- Documentation: https://github.com/mozilla/reticulum/blob/master/guides/api.md 
- Enable /tokens endpoint to enable API tokens for your HC instance API requests - https://github.com/mozilla/hubs/pull/4425
- [Hubs] Fast room switching - https://github.com/mozilla/hubs/pull/4347 
- [Hubs] Upload both logos for light and dark themes - https://github.com/mozilla/hubs/pull/4786 
- [Hubs] Fix bugs on touchscreens that made buttons unclickable and flung objects - https://github.com/mozilla/hubs/pull/4740 / https://github.com/mozilla/hubs/pull/4737 
- [Hubs] Better audio room defaults - https://github.com/mozilla/hubs/pull/4817\
- [Hubs] Search for scenes and avatars in admin panel - https://github.com/mozilla/hubs/pull/4463
  - HDR lightmaps & environment settings system - https://github.co/mozilla/hubs/pull/4538 
    - [Community submitted!] [rawnsley] Scene with sample assets to check out this feature - https://github.com/LearnHub/HubHenge

Hubs
- Upgrade Three.js to r128 - https://github.com/mozilla/hubs/pull/4321  
- Device detection: iPad now detected as iOS - https://github.com/mozilla/hubs/pull/4700 and Android tablet detected as tablet or mobile device - https://github.com/mozilla/hubs/pull/4724 
- Twitter changes: Twitter popup window closes itself - https://github.com/mozilla/hubs/pull/4824 / Twitter no longer links the room invite - https://github.com/mozilla/hubs/pull/4812 
- Fixed transparency with personal space bubble (when you walk into an avatar) https://github.com/mozilla/hubs/pull/4808
- Fix billboard Y rotation https://github.com/mozilla/hubs/pull/4781 
- Fix dark/light mode sprites https://github.com/mozilla/hubs/pull/4778 
- [Community submitted!] [gfodor] Stop adding session id with every call to getMicrophonePresences https://github.com/mozilla/hubs/pull/4798
- Fix sign in prompt flow issues - https://github.com/mozilla/hubs/pull/4745
- Lazy media load on scene entry - https://github.com/mozilla/hubs/pull/4135
- Fixes audio issues for Safari
  - Fix audio files and choppy video audio - https://github.com/mozilla/hubs/pull/4576 
  - Disable positional audio on safari to resolve distorted audio - https://github.com/mozilla/hubs/pull/4594 
  - Temporary fix for audio distortion in Safari - https://github.com/mozilla/hubs/pull/4441 
- Fix wrong transparency of hover menus - https://github.com/mozilla/hubs/pull/4470 
- Expose client version to HC users - https://github.com/mozilla/hubs/pull/4606
- Fix audio-only elements not playing - https://github.com/mozilla/hubs/pull/4683 
- Misc UI fixes
  - https://github.com/mozilla/hubs/pull/4413
  - https://github.com/mozilla/hubs/pull/4650
  - https://github.com/mozilla/hubs/pull/4544
- Landing page updates
  - https://github.com/mozilla/hubs/pull/4479
  - https://github.com/mozilla/hubs/pull/4585
  - https://github.com/mozilla/hubs/pull/4602
  - https://github.com/mozilla/hubs/pull/4624
- Dark mode/theme fixes
  - https://github.com/mozilla/hubs/pull/4629
  - https://github.com/mozilla/hubs/pull/4649
  - https://github.com/mozilla/hubs/pull/4666
  - https://github.com/mozilla/hubs/pull/4692
  - https://github.com/mozilla/hubs/pull/4727
  - https://github.com/mozilla/hubs/pull/4747
- [Community submitted!] [wmurphyrd] Fix cannot activate mic if last used mic no longer available - https://github.com/mozilla/hubs/pull/4699 
- Fix pinning state changes - https://github.com/mozilla/hubs/pull/4721 
- [Community submitted!] [rawnsley] Scene must be reset when fast switching - https://github.com/mozilla/hubs/pull/4596 
- [Community submitted!] [rawnsley] Fix for URL waypoint fragments when using fast switching - https://github.com/mozilla/hubs/pull/4597
- Fixes for environment-settings system https://github.com/mozilla/hubs/pull/4660
- Fix material components using __mhc_link_type (video texture target in latest Blender exporter) - https://github.com/mozilla/hubs/pull/4733
- [Community submitted!] [rawnsley] Added missing space to match PeopleSidebar - https://github.com/mozilla/hubs/pull/4333
- [Community submitted!] [rawnsley] Fix forward and backward motion when using on-screen touch joysticks. - https://github.com/mozilla/hubs/pull/4334 
- [Community submitted!] [StevenGastroSophy] isSignedIn should be a boolean, not credentials token(string) - https://github.com/mozilla/hubs/pull/4349
- [Community submitted!] [yakyouk] fix mobile touch coordinates - https://github.com/mozilla/hubs/pull/4397 
- [Community submitted!] [yakyouk] fix permission token update, use dialog adapter token for kick - https://github.com/mozilla/hubs/pull/4418 
- [Community submitted!] [rawnsley] Added more console logging to track progress during loading - https://github.com/mozilla/hubs/pull/4569
- [Community submitted!] [rawnsley] Keyboard.getLayoutMap() throws an exception in iFrame on Chrome - https://github.com/mozilla/hubs/pull/4570 by 
- [Community submitted!] [yakyouk] fix name tags not updating - https://github.com/mozilla/hubs/pull/4654 
- [Community submitted!] [rawnsley] HubHenge scene to use to test lightmaps - https://github.com/LearnHub/HubHenge
- [Community submitted!] [wmurphyrd] Fix cannot activate mic if last used mic no longer available - https://github.com/mozilla/hubs/pull/4699
- Reticulum
- Restrict uploads - https://github.com/mozilla/reticulum/pull/506
- Upload domain restriction - https://github.com/mozilla/reticulum/pull/508 
- Entry code redirect fixes - https://github.com/mozilla/reticulum/pull/511 / https://github.com/mozilla/reticulum/pull/515 / https://github.com/mozilla/reticulum/pull/527 

Spoke
- Add support for __mhc_link_type node references in components - https://github.com/mozilla/Spoke/pull/1177 
- Support overriding individual audio parameters - https://github.com/mozilla/Spoke/pull/1175
- Support for optional properties allow for properties to be fully optional and not be exported if they are not enabled - https://github.com/mozilla/Spoke/pull/1185

Thank you for the community contributions from: 
- rawnsley
- yakyouk
- wmurphyrd
- StevenGastroSophy
- Gfodor

| Package versions                                           |
|------------------------------------------------------------|
| mozillareality/ita/0.0.1/20211117212826                    |
| mozillareality/reticulum/1.0.1/20220225005345              |
| mozillareality/hubs/1.0.0/20220225014625                   |
| mozillareality/pgbouncer/1.12.0/20191106234457             |
| mozillareality/spoke/1.0.0/20211125101704                  |
| mozillareality/certbot/1.0.0/20191224043510                |
| mozillareality/youtube-dl-api-server/0.4/20220217230007    |
| mozillareality/janus-gateway/2.0.1/20211220195030          |
| mozillareality/postgrest/5.2.0/20190130035107              |
| mozillareality/polycosm-static-assets/1.0.0/20200320162152 |
| mozillareality/coturn/4.5.3.0/20200422002445               |


2021-10-15
---------
AMI and Template changes
- Removes reliance on port 80 - allowing networks with 80 blocked, to access HC
- Fixes an ALB template issue
- Adds a cron job to clean up DNS hanging records
- Adds an additional stack output used in the next release

NOTE: Hubs Cloud template changes need to be [manually updated via this guide for existing stacks](https://hubs.mozilla.com/docs/hubs-cloud-aws-updating-the-stack.html#-upgrade-your-hubs-cloud-template-to-the-latest)

2021-08-24
----------
New Features
- Live Screens (beta) enabled in room via Blender add-on!- Add an in-room camera feed to a texture on an object so you can enable mirrors or large screens - https://github.com/mozilla/hubs/pull/4126
    - Full video https://www.youtube.com/watch?v=oEc8ML2Q-z8
    - How to use https://www.youtube.com/watch?v=qMWjdxy2wrY
- Community submitted! Better labels, text, and signs via GLTF rendered text elements - https://github.com/mozilla/hubs/pull/4227 
   - Complementary with the Blender exporter add on - https://github.com/MozillaReality/hubs-blender-exporter/pull/31
- In world speakers and in world microphones! (only moderators and owners can use the mics) - https://github.com/mozilla/hubs/pull/4237
    - Blender add-on rlease notes: https://github.com/MozillaReality/hubs-blender-exporter/releases/tag/v0_0_10
- French translations - Community submitted! https://github.com/mozilla/hubs/pull/3897
- Removes support for Google Poly, Google Poly is shutting down June 30th, exposes Google Poly assets as a webpage so folks can download and upload them directly - https://github.com/mozilla/hubs/pull/4306

Performance Improvements
- Improved video performance in Firefox - https://github.com/mozilla/hubs/pull/4210
- Added audio workaround to increase audio quality and re-enable specialized audio in Chrome - will remove when chromium feature lands and the workaround is no longer needed - https://github.com/mozilla/hubs/pull/4227
- Better loading of fonts - Community submitted! Courtesy of Rawnsley https://github.com/rawnsley https://github.com/mozilla/hubs/pull/4184/files
- Updated Three.js glTF loader to the latest - https://github.com/mozilla/hubs/pull/4198
- Improved rendering for multisampled FBs in Chromium browser - https://github.com/mozilla/hubs/pull/4255
- Audio zone improvements, mods can now modify audio zone sources- https://github.com/mozilla/hubs/pull/4278
- Improved Chrome audio quality issues and got stereo working again! - https://github.com/mozilla/hubs/pull/4275
- Community submitted! Waypoint links no longer refresh the page when the current room is the same and fixes back button sending to last waypoint - https://github.com/mozilla/hubs/pull/4272
- Optimized SQL queries in the session_stats table - https://github.com/mozilla/reticulum/pull/493

Bug Fixes
- Fixes fake joining a room without joining not failing to join room with invalid credentials and smooths out webrtc and networked aframe rejoining - https://github.com/mozilla/hubs/pull/3935
- Shows mic selection on every join - Fixes joining a room with a saved mic that is no longer connected. - https://github.com/mozilla/hubs/pull/4151
- Fixes exiting VR mode in Oculus browser to exit correctly and manages disconnects from controllers correctly https://github.com/mozilla/hubs/pull/4206
- Remove error in mobile devices looking for KeyQ - Community submitted! rawnsley - https://github.com/rawnsley - https://github.com/mozilla/hubs/pull/4177
- Adds count to People menu button - Community submitted! MegaMotion = https://github.com/MegaMotion - https://github.com/mozilla/hubs/pull/4199
- Cloned lights point in the correct direction - https://github.com/mozilla/hubs/pull/4253
- Nested media frames place media in correct places - https://github.com/mozilla/hubs/pull/4279
- Community submitted! Remove create room "more menu" when it should be disabled - https://github.com/mozilla/hubs/pull/4285
- Community submitted! Allow spectate when the room is full - https://github.com/mozilla/hubs/pull/4248
- Community submitted! "Change scene" button shows after setting the scene from a GLB, previously button was hidden - https://github.com/mozilla/hubs/pull/4235
- Community submitted! Removed console error when setLocal is called - https://github.com/mozilla/hubs/pull/4178
- Community submitted! Renamed "copy avatar" to "save avatar" - https://github.com/mozilla/hubs/pull/3942
- Discord bot would attempt to connect to null or an invalid room url, catch and handle this error gracefully - https://github.com/mozilla/reticulum/pull/494
- Don't return null for deleted projectless scenes - https://github.com/mozilla/reticulum/pull/498

2021-04-19
----------
Reticulum:
  - [experimental] The beginnings of a graphql API for managing rooms has been added behind a feature flag. There is no UI for generating credentials.
  - mozillareality/reticulum/1.0.1/20210408151304
  - https://github.com/mozilla/reticulum/pull/492
    
Hubs:
  - New UI
  - Multiple custom themes can be configured in the admin panel
  - Webcam avatars and video target components
  - Enable WebXR support for Windows Mixed Reality headsets in Google Chrome and Microsoft Edge
  - mozillareality/hubs/1.0.0/20210408153100
  - https://github.com/mozilla/hubs/pull/4158

Spoke:
  - Add support for manually setting attributions on media.
  - Disable elements to prevent them from being exported or being involved in nav-mesh calculation.
  - Elements now collapse in the hierarchy to declutter your scene.
  - Add billboard support to media
  - Add support for custom nav meshes
  - Add link behaviour to images/videos
  - Add support for creating scenes directly from GLB
  - mozillareality/spoke/1.0.0/20210315144242
  - https://github.com/mozilla/Spoke/pull/1132

2021-02-02
----------
Reticulum:
  - Added the ability to customize magic link email text in Admin Panel "Auth" tab
  - 1.0.1/20210115134515 https://github.com/mozilla/reticulum/pull/463

Hubs:
  - Type room name to confirm close room
  - WebRTC Debugging panel
  - Added the ability to customize magic link email text in Admin Panel "Auth" tab
  - Brazilian Portuguese language support
  - Spanish language support
  - Japanese language improvements
  - Russian language support
  - Experimental dynamic audio normalization
  - Increased the room occupant threshold where we stop reporting user entries and leaves from 12 to 30.
  - Add preference to toggle gyroscope control
  - Set quality setting with query string parameters
  - Fallback to default local model when there is an avatar load error
  - Fix missing avatar head on inspect bug
  - Various fixes
  - 1.0.0/20210115142723 https://github.com/mozilla/hubs/pull/3851

Spoke:
  - Support multiple animations on a single model
  - Allow toggling floating on objects from spawners
  - Various fixes
  - 1.0.0/20210115140717 https://github.com/mozilla/Spoke/pull/1095


2020-10-13
----------
Reticulum:
  - Admin panel now redirects you to the homepage if you are not logged in as an admin
  - Fix for CSP issue with Google Analytics
  - 1.0.20201012230301 https://github.com/mozilla/reticulum/pull/422

Hubs:
  - Add media frames
  - Redirect non-admin users away from the admin panel
  - Add Japanese language support
  - Inspect avatars
  - 1.0.0.20201002202739 https://github.com/mozilla/hubs/pull/3165

Spoke:
  - Add media frames
  - 1.0.0.20200930005646 https://github.com/mozilla/Spoke/pull/1042


2020-09-11
----------
Reticulum:
  - Fixed backwards compatibility with older clients. This was an update to reticulum to fix compatibility for older custom clients.
  - mozillareality/reticulum/1.0.1/20200911183406 https://github.com/mozilla/reticulum/pull/414


2020-09-08
----------
Reticulum:
  - Hub Invites: Added Hub Invites, which allows us to restrict access to rooms when they are in the :invite entry<sub>mode</sub>
  - Clearer error messages for streaming failures: Sharing media from popular streaming sites often fails for reasons beyond our control. We've added clearer messaging for when this happens.
  - mozillareality/reticulum/1.0.1/20200817225751 https://github.com/mozilla/reticulum/pull/411

Hubs:
  - Hub Invite Links: A room can now be set to "Invite only", which then generates an invite link that allows room access. The invite link can be revoked, or the room can be put back into "Private" mode. If a user attempts to enter a room without an invite id, they are denied access and shown our typical black room entry denial screen.
  - Waypoint Improvements: You can now use links to teleport between waypoints in the scene.
  - Medium quality mode: The medium quality mode is targeted at improving performance and graphics quality on budget desktops/laptops and mobile devices.
  - Improved Accessibility for main UI: ARIA roles and labels have been added to several buttons and elements in the room UI. Tested with NVDA screen reader.
  - Basic non-English language support: There is now a user preference for setting language and instructions for how to submit translation files to be reviewed and added to the app.
  - mozillareality/hubs/1.0.0/20200908210500 https://github.com/mozilla/hubs/pull/2990

Spoke:
  - Scene Preview Camera Node: The Scene Preview Camera Node can be placed in your scene and will be used to position the camera when generating thumbnails or previewing the scene in Hubs.
  - mozillareality/spoke/1.0.0/20200803233608 https://github.com/mozilla/Spoke/pull/1022


2020-07-21
----------
Reticulum:
  - Do not show favorite rooms that have been closed
  - 1.0.1/20200715190503

Hubs:
  - Fix avatar previews on iOS
  - Remove delete buttons from admin panel
  - Add preference for preferred camera
  - 1.0.0/20200722000012

Spoke:
  - Fixes for models exported by the Blender exporter
  - Add "alpha mode" setting for images
  - 1.0.0/20200707224342


2020-06-12
----------
Reticulum:
  - Fix issues with default room feature
  - Add dropbox support
  
Hubs:
  - Performance improvements in physics
  - Support for new Mediasoup-based SFU, dialog
  - Preferences dialog reorganized
  - Added gltF UV-scrolling


2020-05-26
----------
Hubs:
  - New NAF Janus adapter changes to support retries
  - New mobile UI for object list
  - Fix shrink command
  - Enabled desktop audio mixing through avatar


2020-05-18
----------
Hubs: 
  - WebXR Support (!)
  - Fix admin console styling and add sandbox warning
  - Add UI to add accounts in admin console
  - New npm workflows for development
  - Optimized webrtc connection handling for increase lobby viewing
  - Improved mobile object list styling
  - Preferences for auto-exit, noice cancellation, disable sfx
  - Fix crash in audio feedback component
  - Fix noise cancellation in Chrome
  - (Critical) Fix duck floatation behavior
  - Add support for dash videos and x-mpegurl
  - Fix menu z-fighting
  - Fix networked scaling
  - Fix skybox flicker when shrinking avatar
  - Add "force_tcp" TURN override
  - Fix avatar preview for minecraft avatars


2020-04-22
----------
Reticulum:
  - Pre-TURN maintenence release
  - Fix error when changing scenes due to ecto issue: https://github.com/elixir-ecto/ecto/issues/3246#issuecomment-616080541 https://github.com/mozilla/reticulum/pull/367


2020-04-16
----------
Reticulum:
  - Prevent database pausing when users are connected
  - Added `user_data` column to rooms
  - Removed various bottlenecks to increase message throughput in load testing
  - Properly deal with offline twitch streams
  - Added rate limiting + better caching to video/3d model resolution
  - Added CRUD API to update room information
  - Fix issue with CORS proxying not dealing with HEAD requests properly
  - Database is now properly migrated before server starts
  - Added server TURN secret management

Hubs:
  - Added better identity and account management in admin console
  - Added account disabling to deny access
  - Fix pagination in admin console
  - Added emoji permissions, flying permissions
  - Added owner configurable room cap
  - Bugfixes to hubs cloud deploy tooling
  - Allow locomotion from lobby view if enabled
  - Enable echo cancellation in Chrome
  - Add /audiomode experimental option to disable positional audio
  - Fix fade in/out transition borders
  - Move WASM physics into a worker
  - Add morph target animation support
  - Add basis texture support
  - Add MOZ_lightmap support
  - Add video stream refresh
  - Add positional audio, speed modifier preferences
  - Fix bug causing rooms to load slowly if no VR headset plugged in
  - Upgrade three.js to r111/aframe 1.0.3
  - Accessibility improvements

Spoke:
  - Enable controls on images
  - Added performance information helper
  - Lots of bugfixes and performance improvements
