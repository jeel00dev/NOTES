# Tmux Keybindings & Commands (Vim-style)

> **Note:** `mod` = `Ctrl + b`

---

### Session Commands

| Action         | Command                               |
| -------------- | ------------------------------------- |
| Start default  | `tmux`                                |
| Start named    | `tmux new -s <session-name>`          |
| Attach default | `tmux a`                              |
| Attach named   | `tmux a -t <session-name>`            |
| Kill named     | `tmux kill-session -t <session-name>` |

---

### Session Keybinds

| Action         | Keybind   |
| -------------- | --------- |
| Rename session | `mod + $` |
| Detach session | `mod + D` |

---

### Window Keybinds

| Action                 | Keybind       |
| ---------------------- | ------------- |
| Create new window      | `mod + c`     |
| Next / Previous window | `mod + n / p` |
| List all windows       | `mod + w`     |
| Change window number   | `mod + .`     |
| Rename window          | `mod + ,`     |
| Kill current window    | `mod + &`     |
| Select window 0–9      | `mod + 0-9`   |

---

### Pane Keybinds

| Action            | Keybind   |
| ----------------- | --------- |
| Vertical split    | `mod + V` |
| Horizontal split  | `mod + H` |
| Kill current pane | `mod + x` |

---

### Copy Mode

| Action          | Keybind                            |
| --------------- | ---------------------------------- |
| Enter copy mode | `mod + [`                          |
| Move & copy     | Use `hjkl` (vim keys) then `Enter` |
