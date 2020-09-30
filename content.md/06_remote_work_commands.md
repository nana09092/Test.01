### Команды для работы с удаленным репозиторием

_git remote add [repository name] [address]_ - используется для добавления связанных удаленных репозиториев.

'git remote add origin https://github.com/nana09092/Test.01.git'

При работе с удаленными репозиториями при выполненияя разных задач используются такие команды, как:

  _git fetch_ - получение изменений с удаленного репозитория. При этом список изменений не вносится в код локального репозитория.

  _git merge_ - слияние полученных изменений и локального репозитория

  _git pull_ - выполняет последовательно две вышеуказанные команды _git fetch_ и _git merge_

_git push_ - отправляет изменения в репозиторий. 

_git status_ - отображает состояние репозитория

_git log_ - показывает список последних коммитов, начиная с последнего

_git show [hash]_ - показывает информацию по определенному коммиту