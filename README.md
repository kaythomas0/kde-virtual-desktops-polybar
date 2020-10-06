# kwin-polybar-script

## Example Polybar Configuration

```
[module/kde-desktops]
type = custom/script
exec = ~/.config/polybar/scripts/kwin-polybar-script
interval = 0.1
label = %output%
```

## Module Configuration
Configuration of the module is done inside the script:
```
### Configuration
accentColor="#ff79c6"
separator="|"
useDesktopNames=false
###
```

## Example Screenshots

### Desktop Numbers
![Example Screenshot 1](screenshot-1.png)

### Desktop Names
![Example Screenshot 2](screenshot-2.png)
