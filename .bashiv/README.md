# .bashiv

Here lies the constituents of the `~/.bashiv/bin` directory.
These are mostly `bash` scripts that I want to be callable from any directory without specifying their full path.

They are usually meant to make my life easier, mostly to be used as shorcuts.

1. `audioconnectioncheck`: runs an infite loop that _mutes_ and _pauses_ whatever it is that is playing when I unplug headphones for the jack port or when I disconnect my bluetooth headsets or buds. It also _unmutes_ and _replays_ when they're connected again.

2. `bluetoothtoggle`: one line script that toggles bluetooth on or off when called.

3. `python`: instead of running python files like this bash`python3 main.py`, I do it like this bash`python main.py`. Subtle, but worth it.
