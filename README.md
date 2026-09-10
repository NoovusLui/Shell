# Shell
#---
## Fastfetch
{
  "$schema": "https://github.com/fastfetch-cli/fastfetch/raw/dev/doc/json_schema.json",
  "logo": {
    "type": "kitty-direct",
    "source": "~/Pictures/ryodecors/katana.png",
    "width": 28,
    "height": 14,
    "padding": {
      "left": 3,
      "right": 5,
      "top": 5
    }
  },
  "display": {
    "color": {
      "keys": "38;2;61;219;217"
    },
    "key": {
      "width": 9
    },
    "percent": {
      "color": {
        "green": "38;2;127;191;106",
        "red": "38;2;226;52;42",
        "yellow": "38;2;217;164;65"
      },
      "type": 9
    },
    "separator": "  "
  },
  "modules": [
    "break",
    {
      "type": "title",
      "format": "\u001b[1;38;2;243;237;225m{user-name}\u001b[0m\u001b[38;2;143;135;112m @ \u001b[0m\u001b[1;38;2;243;237;225m{host-name}\u001b[0m"
    },
    {
      "format": "\u001b[38;2;61;219;217m■\u001b[0m \u001b[38;2;143;135;112mRYOKU · 力 · nier desktop\u001b[0m",
      "type": "custom"
    },
    "break",
    {
      "format": "\u001b[38;2;61;219;217m──\u001b[0m \u001b[1;38;2;243;237;225mHARDWARE\u001b[0m \u001b[38;2;58;46;36m────────────────────────\u001b[0m",
      "type": "custom"
    },
    {
      "key": "CPU",
      "type": "cpu"
    },
    {
      "detectionMethod": "pci",
      "key": "GPU",
      "type": "gpu"
    },
    {
      "key": "MEMORY",
      "type": "memory"
    },
    {
      "key": "DISK",
      "type": "disk"
    },
    "break",
    {
      "format": "\u001b[38;2;61;219;217m──\u001b[0m \u001b[1;38;2;243;237;225mSYSTEM\u001b[0m \u001b[38;2;58;46;36m──────────────────────────\u001b[0m",
      "type": "custom"
    },
    {
      "key": "OS",
      "text": "echo \"Ryoku $(ryoku version 2\u003e/dev/null || echo dev)\"",
      "type": "command"
    },
    {
      "key": "KERNEL",
      "type": "kernel"
    },
    {
      "key": "WM",
      "text": "echo \"${XDG_CURRENT_DESKTOP:-Hyprland}\"",
      "type": "command"
    },
    {
      "key": "SHELL",
      "type": "shell"
    },
    {
      "key": "PKGS",
      "type": "packages"
    },
    "break",
    {
      "format": "\u001b[38;2;61;219;217m──\u001b[0m \u001b[1;38;2;243;237;225mSESSION\u001b[0m \u001b[38;2;58;46;36m─────────────────────────\u001b[0m",
      "type": "custom"
    },
    {
      "key": "UPTIME",
      "type": "uptime"
    },
    {
      "key": "AGE",
      "text": "echo $(( ($(date +%s) - $(stat -c %W /)) / 86400 )) days",
      "type": "command"
    },
    {
      "key": "TERM",
      "type": "terminal"
    },
    "break",
    {
      "type": "colors",
      "symbol": "circle",
      "paddingLeft": 2
    },
    "break",
    {
      "format": "\u001b[38;2;61;219;217m──\u001b[0m \u001b[1;38;2;243;237;225mSECTION\u001b[0m \u001b[38;2;58;46;36m─────────────────────────\u001b[0m",
      "type": "custom"
    },
    "break",
    {
      "type": "colors",
      "symbol": "circle"
    },
    {
      "key": "CPU",
      "type": "cpu"
    },
    {
      "key": "GPU",
      "type": "gpu"
    },
    {
      "key": "MEMORY",
      "type": "memory"
    },
    {
      "key": "DISK",
      "type": "disk"
    },
    {
      "key": "KERNEL",
      "type": "kernel"
    },
    {
      "key": "OS",
      "type": "os"
    },
    {
      "key": "HOST",
      "type": "host"
    },
    {
      "key": "UPTIME",
      "type": "uptime"
    },
    {
      "key": "PACKAGES",
      "type": "packages"
    },
    {
      "key": "SHELL",
      "type": "shell"
    },
    {
      "key": "TERMINAL",
      "type": "terminal"
    },
    {
      "key": "WM",
      "type": "wm"
    },
    {
      "key": "DESKTOP",
      "type": "de"
    },
    {
      "key": "BATTERY",
      "type": "battery"
    },
    {
      "key": "LOCAL IP",
      "type": "localip"
    },
    {
      "key": "BOARD",
      "type": "board"
    },
    {
      "key": "BOARD",
      "type": "board"
    }
  ]
}
