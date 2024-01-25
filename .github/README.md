# Config files for IL-2 1946

These configs are valid for Version 4.12.2m, HSFX 7.03, and possibly others.

Drop these files in the root folder of IL-2 1946.

Contents:
- `conf.ini`: Updated config for the game. Read and retouch if needed.
- `Users/`: Pilot config. Contains bindings, campaigns.
- `dsound.dll`, `dsoal-aldrv.dll`, `alsoft.ini`: DLLs for OpenAL Soft, a
  software-based reimplementation of EAX (see https://github.com/kcat/openal-soft).
  * `dsound.dll`: Wrapper that calls `dsoal-aldrv.dll`
  * `dsoal-aldrv.dll`: Software implementation of EAX driver
  * `alsoft.ini`: Config for OpenAL soft. Contains a fix for current OpenAL soft
    and reverb problems.
- `icons.rcu`, `rcu/`: Workaround for further plane dot icons in singleplayer.

# FAQ

#### Can I use the files here with any version or mod?

Yes, you can. You may need to configure more things for the specific mod. Read
their docs.

#### Why IL-2 doesn't recognize all my joysticks/buttons?

IL-2 supports up until 4 USB HID devices (joysticks), and for them up until 8
axis and 32 buttons.
If you are missing some joystick, make sure you don't have other USB HID
joystick devices connected (e.g: an unused button panel).
If your joystick has more than 32 buttons, you can try splitting it into virtual
joysticks in its firmware (for example, in Virpil, VKB devices) or by using a
utility such as controllerbuddy.org or joystick gremlin.
