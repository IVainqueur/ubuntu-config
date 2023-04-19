# Fix Buzzing Audio Output
Note: I found this solution [here](https://unix.stackexchange.com/questions/697337/fix-audio-crackling-linux)

try:
- editing the `/etc/pulse/daemon.conf`  file. Find the line that says `default-sample-rate` and change it from

    ```ini
    ; default-sample-rate = 44100 # or some other number
    ```
    to 

    ```ini
    ; default-sample-rate = 48000
    ```

- Create `~/.config/pulse/daemon.conf` and add:

    ```ini
    default-sample-rate = 48000
    ```

- then run
    ```
    $ pulseaudio -k
    ```