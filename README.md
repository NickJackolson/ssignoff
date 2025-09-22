# ssignoff
ssignoff is a sign-off generator which utilizes rofi and git configurations.

## Prequisites
```
* rofi
```

## Installation
```bash
mkdir -p $HOME/.config/ssignoff/
cp templates $HOME/.config/ssignoff
chmod +x ssignoff
sudo cp ssignoff /usr/bin/ # or add it anywhere else in your path
```

## Usage
```bash
$ ssignoff
# select from rofi menu
Signed-off-by: Mete Durlu <meted@linux.ibm.com>
# select from rofi menu
Reviewed-by: Mete Durlu <meted@linux.ibm.com>
```

