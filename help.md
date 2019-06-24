## H1. Helpful And Configurable
### Гибкая настройка под любой процесс
- `git help` — список команд
- `git <command> -h` — помощь по команде в терминале
- `git <command> --help` — документация по команде в браузере
- `git config -e --system` — редактировать настройки системы
- `git config -e --global` — редактировать настройки пользователя
- `git config -e` — редактировать настройки репозитория
- `git config --global user.name "<name>"` — задать имя пользователя
- `git config --global user.email "<email>"` — задать почту пользователя

### Aliases
- `git config --global alias.ci "!gitex commit"`
- `git config --global alias.st "git status -sb"`
- `git config --global alias.graph "git log --oneline --graph --all"`
- `git config --global alias.co "git checkout"`
- `git config --global alias.pushup "push -u origin HEAD"`
- `git config --global alias.puff "pull --ff-only"`
- `git config --global alias.pure "pull --rebase"`
- `git config --global alias.undo "reset --hard HEAD~1"`
