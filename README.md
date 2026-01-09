# wifi-pass

Show saved wifi passwords on macOS.

```
$ wifi-pass
Found 5 networks:

HomeWifi: mypassword123
Starbucks: xK9#guest
Office-5G: hunter2

$ wifi-pass HomeWifi
HomeWifi: mypassword123
```

## Install

```bash
git clone https://github.com/yksanjo/wifi-pass.git
chmod +x wifi-pass/wifi-pass
cp wifi-pass/wifi-pass /usr/local/bin/
```

## Usage

```bash
wifi-pass          # show all saved networks
wifi-pass <name>   # show specific network
```

Note: macOS will prompt for your password to access keychain.

## License

MIT
