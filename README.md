# grab

Monitor log files as they grow, directly from your terminal.

`grab` is a minimal Bash utility built for developers who need a simple, efficient way to watch live logs. Whether you're compiling a large codebase, debugging an application, or tracking a background process, `grab` prints existing content and continuously follows new output without repeatedly clearing the terminal.

### Features

- **Live log streaming** : Follow new lines as they are written.
- **Existing log output** : Display the file's current contents before monitoring new entries.
- **Optional time limit** : Automatically stop monitoring after a specified duration.
- **Minimal dependencies** : Uses standard Linux command-line utilities.
- **Simple syntax** : Start monitoring with a single command.
- **Terminal-friendly output** : Preserve scrolling history without constant screen redraws.

### Installation

```bash
curl https://raw.githubusercontent.com/Pratech1015/grab/refs/heads/main/install.sh | bash
```

Installs one file at /usr/bin/grab cleanly.

### Quick start

```bash
grab build.log
```

Monitor for 60 seconds:

```bash
grab build.log -t 60
```

Press `Ctrl+C` to stop monitoring at any time.

### Uninstallation

```bash
curl https://raw.githubusercontent.com/Pratech1015/grab/refs/heads/main/uninstall.sh | bash
```

Removes grab from your system cleanly.
