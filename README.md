# Lapce Emacs Keymaps

In this repository I am define file `keymaps.toml` which is consists defnitions of kebindings in the Emacs-like style for the editor [lapce](https://github.com/lapce/lapce "a modern, super fast, non-extensible, non-documentated text editor written in Rust")

If you want to use it, then you should copy content of the file with name `keymaps.toml` and paste it into your keymaps file (you can open it using the command from the lapce pallet "Open Keyboard Shortcuts File")

## Features list

Note that lapce isn't an extensible editor as Emacs and at this moment I can't write own functions, so most of emacs functions isn't provided.  Below placed the list of the {un}supported functions.  Here placed only most imported commands in my opinion, you can do PRs adding your ones

| *Emacs command name*         | *supported?* |
|------------------------------|--------------|
| `next-line`                  | +            |
| `previous-line`              | +            |
| `forward-char`               | +            |
| `backward-char`              | -            |
| `forward-sexp`               | -            |
| `backward-sexp`              | +            |
| `forward-word`               | +            |
| `backward-word`              | +            |
| `end-of-buffer`              | +            |
| `beginning-of-buffer`        | +            |
| `find-file`                  | +            |
| `isearch`                    | +            |
| `isearch-forward`            | +            |
| `isearch-backward`           | +            |
| `isearch-cancel`             | +            |
| `save-buffer`                | +            |
| `save-some-buffers`          | +            |
| `save-buffers-kill-terminal` | +            |
| `M-x`                        | +            |
| `yank`                       | +            |
| `yank-pop`                   | -            |
| `copy-region-as-kill`        | +            |
| `kill-region`                | +            |
| `kill-forward-char`          | +            |
| `kill-backward-char`         | +            |
| `kill-forward-word`          | +            |
| `kill-backward-word`         | +            |
| `kill-sexp`                  | -            |
| `transpose-lines`            | +            |
| `transpose-words`            | -            |
| `transpose-sexps`            | -            |
| `goto-line`                  | +            |
| `comment-dwim`               | +            |
| `er/expand-region`           | +            |
| `mc/next-like-this`          | +            |
| `mc/all-like-this`           | +            |
| `mc/previous-like-this`      | +            |
| `mc/edit-lines`              | -            |
| `kill-line`                  | -            |
| `set-mark-command`           | -            |
| `deactivate-mark`            | -            |
| `mark-whole-buffer`          | +            |
| `mark-sexp`                  | -            |
| `mark-word`                  | -            |
| `mark-paragraph`             | -            |
| `forward-paragraph`          | -            |
| `backward-paragraph`         | -            |
| `exchange-point-and-mark`    | -            |
| `open-line`                  | -            |
| `delete-other-windows`       | -            |
| `split-window-vertically`    | +            |
| `split-window-horizontally`  | -            |
| `kmacro-start`               | -            |
| `upcase-word`                | -            |
| `upcase-char`                | -            |
| `upcase-region`              | -            |
| `undo`                       | -            |
| `toggle-input-method`        | -            |
| `recentf-open-files`         | -            |
| `repeat`                     | -            |
| `outline-cycle-buffer`       | -            |
| `xref-find-defnitions`       | +            |
