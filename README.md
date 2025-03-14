# 3ds-webcam

Use your 3DS as a networked webcam with this homebrew (and a nifty python script)  
  
Uses the `sounddevice`, `qoi`, and `pyvirtualcam` pip packages, which require you to have OBS and VoiceMeeter installed.  
On Windows, at least. If you use any flavour of *nix, you should know enough to make it work.

To run, you must have OBS studio with virtual cam and run this in a command prompt:

```pip install sounddevice, qoi, pyvirtualcam```

# JUST REALIZED MY ERROR WAS ON MY END ONLY.
This fork will now be used for uploading builds due to the original repo not having releases.


## Usage

Launch the 3DSX from the Homebrew Menu on your console, set it up how you want (microphone/camera/both)  
Start the connection  
Run the script with your console's IP address as the only command-line argument  
When you want to stop, stop the connection on your console or exit directly.
