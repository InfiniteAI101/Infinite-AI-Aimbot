# Infinite-AI-Aimbot
This is a paid AI Aimbot for any game with humanoid characters
Infinite AI Aimbot sharpshoots targets in any game with humanoid characters, harnessing the power of YOLOv5. Currently, it's a ninja against anti-cheat systems, as it's visual-only. Still, watch out for manual player reports
## version 
- Fast  - `main.py` ✅ Easy to set up, Works on any computer 💻

##  Requirements
- Nvidia RTX 980 🆙, higher or equivalent
- And one of the following:
  - Nvidia CUDA Toolkit 11.8 [DOWNLOAD HERE](https://developer.nvidia.com/cuda-11-8-0-download-archive)

## Pre-setup Steps
1. Download and Unzip the AI Aimbot and stash the folder somewhere handy 🗂️.
2. Ensure you've got Python installed (like a pet python 🐍) – grab version 3.11 [HERE](https://www.python.org/downloads/release/python-3116/).
   - 🛑 Facing a `python is not recognized...` error? [WATCH THIS!](https://youtu.be/E2HvWhhAW0g)
   - 🛑 Is it a `pip is not recognized...` error? [WATCH THIS!](https://youtu.be/zWYvRS7DtOg)
3. Fire up `PowerShell` or `Command Prompt` on Windows 🔍.
4. To install `PyTorch`, select the appropriate command based on your GPU.
    - Nvidia `pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118`
    - AMD or CPU `pip install torch torchvision torchaudio`
5.  Run the command below to install the required Open Source packages:
```
pip install -r requirements.txt
```

##  How to Run (Fast Version)
Follow these steps **after** Python and all packages have been installed:

1. Open `PowerShell` or `Command Prompt`.
2. Input `cd `, then drag & drop the folder containing the bot code into the terminal.
3. Hit Enter.
4. Type `python main.py` and press Enter.
5. Use **CAPS_LOCK** to toggle the aimbot. It begins in the *off* state.
6. Pressing `q` at **ANY TIME** will shut down the program.

## Configurable Settings

*Default settings are generally great for most scenarios. Check out the comments in the code for more insights. 🔍 The configuration settings are now located in the `config.py` file!<br>
**CAPS_LOCK is the default for flipping the switch on the autoaim superpower! ⚙️ 🎯**

`aaRightShift` - Might need a tweak in 3rd person games like Fortnite and New World. 🎮 Typically, a setting of `100` or `150` should hit the mark. 🎯👌

`aaQuitKey` - The go-to key is `q`, but if it clashes with your game style, swap it out! 

`headshot_mode` - Set to `False` if you're aiming to keep things less head-on and more centered. 

`cpsDisplay` - Toggle off with `False` if you prefer not to display the CPS in your command station. 

`visuals` - Flip to `True` to witness the AI's vision! Great for sleuthing out any hiccups. 

`aaMovementAmp` - The preset should be on point for 99% of players. Lower the digits for smoother targeting. Recommended doses: `0.5` - `2`. 

`confidence` - Stick with the script here unless you're the expert. 

`screenShotHeight` - Same as above, no need for changes unless you've got a specific vision. 

`screenShotWidth` - Keep it constant as is, unless you've got reasons to adjust. 

`aaDetectionBox` - Default's your best bet, change only if you've got the know-how. 

`onnxChoice` - Gear up for the right graphics card—Nvidia, AMD, or CPU power! 

`centerOfScreen` - Keep this switched on to stay in the game's heart. 

## Current Stats

The bot's efficiency depends on your setup. We achieved 100-150 CPS with our test specs below.

    - AMD Ryzen 7 2700
    - 64 GB DDR4
    - Nvidia RTX 3080

 Tip: Machine Learning can be tricky, so reboot if you keep hitting CUDA walls.

##  Known Cheat-Detectable Games

Splitgate (reported by a Discord user 🕵️‍♂️), EQU8 detects win32 mouse movement library.

##  Custom Aimbots and Models

Show off your work or new models via Pull Requests in `customScripts` or `customModels` directories, respectively. Check out the `example-user` folder for guidance.


Happy Coding and Aiming! 🎉👾
