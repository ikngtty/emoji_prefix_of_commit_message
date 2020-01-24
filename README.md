# Emoji Prefix of Commit Message

|     Emoji      |   Emoji String   | Meaning                                            |      Subject of Commit      | Counterpart in Conventional Commits |
|:--------------:|:----------------:|:-------------------------------------------------- |:---------------------------:|:-----------------------------------:|
|    :notes:     |    `:notes:`     | improve behavior or API                            |      Major update (*1)      |         `BREAKING CHANGE:`          |
|   :sparkles:   |   `:sparkles:`   | implement a new function or the first commit       |      Minor update (*1)      |               `feat:`               |
|     :bug:      |     `:bug:`      | fix a bug                                          |      Patch update (*1)      |               `fix:`                |
|    :horse:     |    `:horse:`     | improve performance                                | Non-functional feature (*2) |               `perf:`               |
|     :lock:     |     `:lock:`     | improve security                                   | Non-functional feature (*2) |             `feat:`(?)              |
|     :mag:      |     `:mag:`      | about test codes                                   |       Maintenability        |               `test:`               |
|     :memo:     |     `:memo:`     | about documentation (*3)                           |       Maintenability        |               `docs:`               |
| :green_heart:  | `:green_heart:`  | refactor                                           |       Maintenability        |       `refactor:` or `style:`       |
|   :arrow_up:   |   `:arrow_up:`   | update dependencies (includes code changes for it) |       Maintenability        |              `chore:`               |
|    :wrench:    |    `:wrench:`    | configure for development or CI tools              |       Maintenability        |              `chore:`               |
|   :bookmark:   |   `:bookmark:`   | about a release                                    |           Release           |              `chore:`               |
|    :rocket:    |    `:rocket:`    | about a deploy                                     |           Deploy            |              `chore:`               |
| :construction: | `:construction:` | WIP (work in progress)                             |          Temporary          |                none                 |

(\*1) By the semantic versioning\
(\*2) These may belong to minor update.\
(\*3) Including comments in source code. Their role is just a document,
and they may be used by document generators.

## Why do you use a GitHub repository, not Gist?
Because I want to record commit messages, descriptions of reason for change.
