# Terminal Ping
Just add this in your `.bashrc`, '.zshrc' or '.bash_profile' file.

```bash
export PROMPT_COMMAND+=$''"aplay /path/to/sound > /dev/null 2>&1 &disown"
```