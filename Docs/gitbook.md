# Gitbook
W celu atomatyzacji publikacji wykorzystuję gitbook

## Dokumentacja
https://toolchain.gitbook.com/pages.html


## Instalacja i generowanie książki

update current version
        
    npm install -g npm@latest

install gitbook

    npm install gitbook-cli -g

Prepare project

    gitbook init
or
    \Users\*\AppData\Roaming\npm\gitbook init


Execute

    gitbook serve 
or
    \Users\*\AppData\Roaming\npm\gitbook serve


Build static content

    gitbook build    

or

    \Users\*\AppData\Roaming\npm\gitbook build    


# A basic GitBook usually looks something like this:
    .
    ├── book.json
    ├── README.md
    ├── SUMMARY.md
    ├── chapter-1/
    |   ├── README.md
    |   └── something.md
    └── chapter-2/
        ├── README.md
        └── something.md    