# today

today is a simple and customizable tool for creating daily notes in your terminal, using your preferred text editor.

### Installation

```
curl -o ~/.today.conf https://raw.githubusercontent.com/alabhyajindal/today/main/.today.conf
curl -o /usr/local/bin/today https://raw.githubusercontent.com/alabhyajindal/today/main/today
chmod +x /usr/local/bin/today
```

By default `today` will create and use the directory `~/Documents/Journal/` for your daily notes, but you could use or create another directory and specify it in `~/.today.conf`.

### Usage

To create and open today's daily note in your terminal, use the command `today`. Your default text editor, as indicated by the environment variable `$EDITOR`, will be used. If `$EDITOR` is unset, `vim` will be used. Your note will be stored in a directory named after the current month and year (e.g., 'November 2023'). Simply run `today` again to reopen your daily note.
