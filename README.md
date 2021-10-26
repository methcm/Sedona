# Git:

- Чтобы создать ветку для задачи, нужно следовать следующему стилю именования:
  1. `feature/TASK-NUMBER-Task-description` (в случае создания нового функционала)
  2. `bugfix/TASK-NUMBER-Task-description` (в случае исправления бага)

**Примеры:**
  1. `feature/SEDONA-15-Update-config-file`
  2. `bugfix/SEDONA-24-Fix-border-on-left-sidebar`

- Чтобы коммиты были правильными, первый коммит должен копировать название задачи и ее номер: `[SEDONA-15] Update config file`

# Дополнительно:

В репозитории есть шаблон для создания пулов.
Чтобы пул был правильно оформлен, нужно:
  1. Добавить себя в `assigners`
  2. Запросить ревью в `reviewers`
  3. Добавить нужные лейблы (описание ниже)
  4. Добавить описание по шаблону (Заполнить нужные блоки шаблона и удалить лишние)

В репозитории присутствуют лейблы:
  1. При создании фичи нужно испольлзовать лейбл `feature`, при исправлении бага - `bugfix`.
  2. Так же нужно добавлять лейблы `html`, `css`, `scss`, `js`, `md` в соответствии с расширением файлов, с которыми ты работал.
