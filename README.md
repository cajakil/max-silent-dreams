# max-silent-dreams
`SilentDreams` Max patch for "in silent dreams" and "in stillness darkening"

## options:
1. .dmg or .app.zip = Max/MSP standalone (if you don't have Max/MSP) – 1GB – MacOS only
2. .mxf = Max/MSP collective (if you do have Max/MSP)) – 20MB – MacOS or Windows. Minimum Max/MSP version 8.5.5
3. source code - editable - see below

## Tips for easier downloading
* wait a few seconds for the download to begin
* it may take several seconds for the files to open
* if you have issues, you can [file a bug report on GitHub](https://github.com/cajakil/max-silent-dreams/issues) or [contact me](https://jackcampbell.uk/contact)

I'm unable to generate a stand-alone version for Windows. If you're on Windows, you can [install the free trial of Max/MSP](https://cycling74.com/downloads) and then use the Max/MSP collective. You don't need to pay for Max/MSP to use the patch for playback, even after the end of the trial.

## Documentation is [here](https://www.playbook.com/s/jack-campbell/8dqWmYCDWaF3URK1WUDxQAa6)

## Source code

You can download the source code as a ZIP which is editable in Max. However, you need to install:

Dependencies from [cajakil/max-library](https://github.com/cajakil/max-library) - place these into your Max Library (usually `USER/Documents/Max 8/Library`)
* Abstraction    CompressorSimple.maxpat 
* Abstraction    GraphicalEQ.maxpat
* Abstraction    HiLoPass.maxpat
* Abstraction    Recorder.maxpat
* Abstraction    Reverb.maxpat
* Abstraction    drunkpitch.maxpat
* Abstraction    gainRemap.maxpat

Dependencies - install via the Max Package manager:
* LowKeyNW

Dependencies from project folder - included in Zip, no action should be needed
* SD_delayLaneTapOutComponent
* SD_single-delay-lane
