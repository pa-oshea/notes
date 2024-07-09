# Session Management

## Tmux Sessions

Tmux sessions are the core containers that manage your terminal windows and panes. Each Tmux session is independent and can have its own set of windows, panes, and configurations.

### Commands

| Command                             | Description                                   |
| ----------------------------------- | --------------------------------------------- |
| tmux new -s <session_name>          | Create a new Tmux session with the given name |
| tmux attach -t <session_name>       | Attach to an existing Tmux session            |
| tmux ls                             | List all running Tmux sessions                |
| tmux kill-session -t <session_name> | Terminate the specified Tmux session          |
| tmux switch-client / switchc -t <session_name> | Terminate the specified Tmux session          |
| tmus ls / list-session                            | List all the Tmux sessions currently running  |
| Ctrl+space d                            | Detach from the current Tmux session          |

