# max-silent-dreams
`SilentDreams` Max patch for "in silent dreams" and "in stillness darkening"

## What download do I choose?

| Item         | Extension     | Platform | Requires Max | Editable | Size | Tip | 
|--------------|-----------|------------|-----------|------------| -----------| -----------|
| Application      | .dmg  | MacOS       | no | no | 400MB (1GB extracted) | Download this if you don't have Max/MSP
| Collective | .mxf      | Windows or MacOS        | v.8.5.5 or higher | no | 20MB | Download this if you have Max/MSP
| Source code | .zip | Windows or MacOS | v.8.5.5 or higher | yes | less than 20MB | Download this if you have Max/MSP, want to edit and can follow instructions to include dependencies

I'm unable to generate a stand-alone version for Windows. If you're on Windows, you can [install the free trial of Max/MSP](https://cycling74.com/downloads) and then use the Max/MSP collective. You don't need to pay for Max/MSP to use the patch for playback, even after the end of the trial.

## Important

* Feedback warning: do not use the "mic" mode with a laptop's built in mic and built in speakers. Use headphones at least.
* Set the output volume low to start with

## Documentation is [here](https://www.playbook.com/s/jack-campbell/8dqWmYCDWaF3URK1WUDxQAa6)

**Tips for easier downloading**
* wait a few seconds for the download to begin
* it may take several seconds for the files to open
* if you have issues, you can [file a bug report on GitHub](https://github.com/cajakil/max-silent-dreams/issues) or [contact me](https://jackcampbell.uk/contact)

**Using the MacOS Application**

When first opening the application, you may need to allow the app access to the folder where it's stored, and the microphone.

The application may not open if you rename the file

## Source code

You can download the source code as a ZIP which is editable in Max. However, you need to install:

Dependencies from [cajakil/max-library](https://github.com/cajakil/max-library) - place these into the expanded Zip folder, or your Max Library (usually `USER/Documents/Max 8/Library`)
* CompressorSimple.maxpat 
* GraphicalEQ.maxpat
* HiLoPass.maxpat
* Recorder.maxpat
* Reverb.maxpat
* drunkpitch.maxpat
* gainRemap.maxpat

Dependencies - install via the Max Package manager:
* LowKeyNW

Dependencies from project folder - included in Zip, no action should be needed
* SD_delayLaneTapOutComponent.maxpat
* SD_single-delay-lane.maxpat
* SD_double-delay-lane.maxpat
