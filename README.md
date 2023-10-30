# today

today is a simple and customizable tool for creating daily notes in your terminal, using your preferred text editor.

### Installation

```
curl -o ~/.today.conf https://raw.githubusercontent.com/alabhyajindal/today/main/.today.conf
curl -o /usr/local/bin/today https://raw.githubusercontent.com/alabhyajindal/today/main/today
chmod +x /usr/local/bin/today
```

Create a directory for your daily notes:

```
mkdir -p ~/Documents/Journal
```

Or, create a directory elsewhere and specify it in `~/.today.conf`


### Usage

To create and open today's daily note in your terminal, use the command `today`. The default editor is `vim`. Your note will be stored in a directory named after the current month and year (e.g., 'November 2023'). Simply run `today` again to reopen your daily note.
