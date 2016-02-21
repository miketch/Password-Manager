# Password-Manager
Easily manage yours passwords in the console.

Commands:

node app.js create
node app.js get


Options For Create:
  --name, -n            Account name (eg: Twitter, Facebook)
                                                             [string] [required]
  --username, -u        Account username or email            [string] [required]
  --password, -p        Account password                     [string] [required]
  --masterPassword, -m  Master Password                      [string] [required]
  --help                Show help                                      [boolean]


Options For Get:
  --name, -n            Account name (eg: Twitter, Facebook)
                                                             [string] [required]
  --masterPassword, -m  Master Password                      [string] [required]
  --help                Show help                                      [boolean]

