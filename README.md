### how to install android sdk like a nerd

1. install [homebrew](https://brew.sh/)

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

2. install [openjdk](https://formulae.brew.sh/formula/openjdk)

`brew install openjdk`

3. add jdk to path
`echo 'export PATH="$PATH":"/opt/homebrew/opt/openjdk/bin"'>> ~/.zshrc`