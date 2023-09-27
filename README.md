# General

This templates fixes the one shipped with the duplex plugins.

Works w/ renoise 3.4.3 and latest touchOSC

# Changes

  - fixed mutes/track selector behavior, they now reflects correctly the session state
  - fixed DSP selector line
  - remove next/prev in navigator (crashed the extension)
  - refined cosmetics, resize page bar
  - Couldn't fix reliably the looper features : disable them in settings
    - Matrix / pattern trigger : position only
    - Navigator > Operating mode : control position only
  - add a second page with solos, mutes, and volume faders (and page next/prev)

# installation

- open tosc file in TouchOSC

- `TouchOSC_iPad.lua` goes in : `AppData/Roaming/Renoise/v3.whatever/Scripts/Tools/com.renoise.Duplex.xrnx/Duplex/Controller/TouchOSC/Configurations`

- `TouchOSC_iPad.xml` goes in : `AppData/Roaming/Renoise/v3.whatever/Scripts/Tools/com.renoise.Duplex.xrnx/Duplex/Controller/TouchOSC/Controlmaps`
