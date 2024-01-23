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