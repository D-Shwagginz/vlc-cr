# vlc-cr

TODO: Write a description here

## Installation

### Linux

1. Run
```sh
sudo sh ./rsrc/install.sh
```
2. Add `vlc-cr` to your `shard.yml` dependencies like so:
```yml
dependencies:
  libserialport-cr:
    github: D-Shwagginz/vlc-cr
```

### Windows

1. Follow the instructions at https://github.com/neatorobito/scoop-crystal to add the crystal-preview bucket to scoop
2. Install crystal with `scoop install crystal`
3. Run `.\rsrc\install.ps1` in powershell
4. Run in powershell
```powershell
$env:LIB="${env:LIB};C:\libvlc"
$env:PATH="${env:PATH};C:\libvlc"
```

OR

Run in cmd
```cmd
set PATH=%PATH%;C:\libvlc
set LIB=%LIB%;C:\libvlc
```

## Usage

TODO: Write usage instructions here

## Development

TODO: Write development instructions here

## Contributing

1. Fork it (<https://github.com/your-github-user/vlc-cr/fork>)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## Contributors

- [D. Shwagginz](https://github.com/your-github-user) - creator and maintainer
