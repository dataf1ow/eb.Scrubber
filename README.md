# eb.Scrubber


This device allows you to control the playhead on any clip playing in the selected tracks, right from your Launchpad, Launchpad Pro or Push. Download the .zip to check it out. 

The Device:

- Choose your Control Surface. 

- Re initialize the device if you unplugged your Control Surface, or didn't have it plugged in on startup. 

- You select tracks with the 'Track' boxes. You can define the length that you want to have control over. One to Four bars, or set it to dynamic to always sync to loop braces. 

- Choose the length of the pattern recorder sequence in multiples of the sequence length. 

- Choose the color of each row. 

The Control Surface:

- If using a Push or Push2, hold the Select Button, then hit the User Button. If using an LP, hit the USER 2 Button. The pads do the triggering. You should see the playheads scrolling. If not, make sure you have the proper length selected in the device. If using a QuNeo, be sure to be on the proper preset.  

- The Undo button will switch to golbal mode. On an LP, the UP arrow will switch to global mode. On QuNeo the Play button enters Global Mode  

- The upper Scene Button will trigger pattern recording. Depending on the Control Surface you are using, the LEDs will be different. Generally red = record, and green = play. You CAN overdub when it's playing. Another press will erase the sequence and get ready to record again. 

- The lower Scene Button will put that track into stutter mode. As long as you hold down a pad, it will continue to trigger at the rate specified by the Clip Quantize parameter. 

- On the LP you can change the clip Quantization setting with the other three arrow buttons.

LP PRO:

- If you're using a Luanchpad pro, you need to set the MIDI input and output of the track to the LP Pro's Live port. Set the tracks monitoring to IN, and make sure you are sending on the proper channel. I believe the LP Pro defaults to channel 6. This can be changed in the setup. 

QUNEO: 

- If using a QuNeo, upload the QuNeo_Scrubber preset to your device. Set the MIDI input to QuNeo on Ch. 15, and the output to QuNeo on Ch. 15. Due to M4L not being able to deal with multiple channels, or sysex data, you have to hit the Rhombus button to initialize the interface in some cases. 


