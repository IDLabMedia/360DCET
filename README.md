# Unity Demo of 360DCET

This page contains information about the Unity demo presented in the paper __"360DCET: 360&deg; Video Plus Depth for Cue-Exposure Therapy in VR"__. The paper is not published, it is currently under review.

<img src="https://github.com/IDLabMedia/360DCET/blob/main/docs/demo.gif"/> 

During the demo, the viewer can switch between 3 scenarios. The goal is to compare the level of realism and immersion. Each scenario has its own strengths and weaknesses. There is audio, so be sure to turn on the VR headset speakers.

Note that a correct perception of depth is defined by multiple factors. In this demo, [stereopsis](https://en.wikipedia.org/wiki/Stereopsis) and [motion parallax](https://en.wikipedia.org/wiki/Parallax) are mentioned.

1. A monoscopic 360 degree video is played. There is no correct stereopsis or motion parallax.
2. A stereoscopic 360 degree video is played. There is no correct motion parallax, but the stereopsis already improves the perception of depth significantly.
3. A 3D triangle mesh made from the monoscopic 360 degree video (plus a depth map) is shown. There is both stereopsis and motion parallax. However, as the viewer moves around, areas that were not captured bu the 360 degree camera becomes exposed.

# Download the demo

The demo called "360DCET_demo.zip" (564MB) can be downloaded under [Releases](https://github.com/IDLabMedia/360DCET/releases).

Currently, **only the SteamVR platform on Windows** is supported, so use a VR headset that works in SteamVR. The demo was tested on a Windows 10 PC with an HTC Vive Pro headset. 

# Navigation in the demo

Only the PC keyboard is used in the application, not the hand-held VR controllers. The following user input is accepted:

- Press **Q** to play the 1st scenario
- Press **W** to play the 2nd scenario
- Press **E** to play the 3rd scenario
- Press **spacebar** to recenter the camera (only useful in the 3rd scenario)
- Press **Esc** to quit the application

Demo and paper by [IDLab MEDIA](https://media.idlab.ugent.be/).
