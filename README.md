# git

resource files'n'stuff

## Testing GitHub-Flavored Markdown

Which syntax highlighting language identifier looks the best with triple-backtick code blocks of console commands and output?

Per GitHub's languageId list, "[linguist](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml)"

```yaml
# aliases - An Array of additional aliases
#           (implicitly includes name.downcase)
```

*(see list)*

### `console`

```console
foo@bar:~$ whoami
foo

me@home:~$ curl 'https://icanhazdadjoke.com' > dadjoke.txt
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100    65  100    65    0     0    336      0 --:--:-- --:--:-- --:--:--   355
me@home:~>  cat dadjoke.txt
What do Alexander the Great and Winnie the Pooh have in common? Same middle name.
me@home:~>% ls -l swift
total 8
-rw-r--r--  1 mixelpix  staff  140 Nov  8  2018 first.swift

$ pwd
/Users/mixelpix

> curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

$ curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

% curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

> curl https://api.mainnet-beta.solana.com \
-H "Content-Type: application/json" \
-d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

me@home:~$ ls -l swift
total 8
-rw-r--r--  1 mixelpix  staff  140 Nov  8  2018 first.swift

me@home:~$ pwd
/Users/mixelpix

me@home:~> curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

me@home:~$ curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

me@home:~% curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

me@home:~> curl https://api.mainnet-beta.solana.com \
-H "Content-Type: application/json" \
-d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'
```

### `sh`

```sh
foo@bar:~$ whoami
foo

me@home:~$ curl 'https://icanhazdadjoke.com' > dadjoke.txt
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100    65  100    65    0     0    336      0 --:--:-- --:--:-- --:--:--   355

$ ls -l swift
total 8
-rw-r--r--  1 mixelpix  staff  140 Nov  8  2018 first.swift

$ pwd
/Users/mixelpix

> curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

$ curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

% curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

> curl https://api.mainnet-beta.solana.com \
-H "Content-Type: application/json" \
-d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'
```

### `gfm`

```gfm
foo@bar:~$ whoami
foo

me@home:~$ curl 'https://icanhazdadjoke.com' > dadjoke.txt
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100    65  100    65    0     0    336      0 --:--:-- --:--:-- --:--:--   355

$ ls -l swift
total 8
-rw-r--r--  1 mixelpix  staff  140 Nov  8  2018 first.swift

$ pwd
/Users/mixelpix

> curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

$ curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

% curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

> curl https://api.mainnet-beta.solana.com \
-H "Content-Type: application/json" \
-d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'
```

### `markdown`

```markdown
foo@bar:~$ whoami
foo

me@home:~$ curl 'https://icanhazdadjoke.com' > dadjoke.txt
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100    65  100    65    0     0    336      0 --:--:-- --:--:-- --:--:--   355

$ ls -l swift
total 8
-rw-r--r--  1 mixelpix  staff  140 Nov  8  2018 first.swift

$ pwd
/Users/mixelpix

> curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

$ curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

% curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

> curl https://api.mainnet-beta.solana.com \
-H "Content-Type: application/json" \
-d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'
```

### `ps1`

```ps1
foo@bar:~$ whoami
foo

me@home:~$ curl 'https://icanhazdadjoke.com' > dadjoke.txt
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100    65  100    65    0     0    336      0 --:--:-- --:--:-- --:--:--   355

$ ls -l swift
total 8
-rw-r--r--  1 mixelpix  staff  140 Nov  8  2018 first.swift

$ pwd
/Users/mixelpix

> curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

$ curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

% curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

> curl https://api.mainnet-beta.solana.com \
-H "Content-Type: application/json" \
-d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'
```


### `bat`

```bat
foo@bar:~$ whoami
foo

me@home:~$ curl 'https://icanhazdadjoke.com' > dadjoke.txt
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100    65  100    65    0     0    336      0 --:--:-- --:--:-- --:--:--   355

$ ls -l swift
total 8
-rw-r--r--  1 mixelpix  staff  140 Nov  8  2018 first.swift

$ pwd
/Users/mixelpix

> curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

$ curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

% curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

> curl https://api.mainnet-beta.solana.com \
-H "Content-Type: application/json" \
-d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'
```

### `asciidoc`

```asciidoc
foo@bar:~$ whoami
foo

me@home:~$ curl 'https://icanhazdadjoke.com' > dadjoke.txt
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100    65  100    65    0     0    336      0 --:--:-- --:--:-- --:--:--   355

$ ls -l swift
total 8
-rw-r--r--  1 mixelpix  staff  140 Nov  8  2018 first.swift

$ pwd
/Users/mixelpix

> curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

$ curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

% curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

> curl https://api.mainnet-beta.solana.com \
-H "Content-Type: application/json" \
-d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'
```

### `yaml`

```yaml
foo@bar:~$ whoami
foo

me@home:~$ curl 'https://icanhazdadjoke.com' > dadjoke.txt
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100    65  100    65    0     0    336      0 --:--:-- --:--:-- --:--:--   355

$ ls -l swift
total 8
-rw-r--r--  1 mixelpix  staff  140 Nov  8  2018 first.swift

$ pwd
/Users/mixelpix

> curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

$ curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

% curl https://api.mainnet-beta.solana.com -H "Content-Type: application/json" -d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'

> curl https://api.mainnet-beta.solana.com \
-H "Content-Type: application/json" \
-d '{"jsonrpc":"2.0","id":"1","method":"getBalance","params":["6MoX4kcNrC75Rihp6xfB36Zv5ePp4xKg7Lr3ka6TfefX", {"commitment":"confirmed"}]}'
```

---
