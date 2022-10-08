![heisenberg](https://user-images.githubusercontent.com/70972101/194722007-48d509de-bc89-4b43-b750-b1ffbfbd73e5.jpeg)

# heisenberg-helix-theme
heisenberg theme for helix 

## Configuration

### Add heisenberg.toml to ~/.config/helix/themes

```bash 
cd ~/.config/helix/themes
wget https://raw.githubusercontent.com/IrishMaestro/heisenberg-helix-theme/master/heisenberg.toml
```

### Note:  if you created a symbolic link from your helix installation to the ~/.config/helix/themes directory, change directory to helix/runtime/themes then run the following command

```bash 
wget https://raw.githubusercontent.com/IrishMaestro/heisenberg-helix-theme/master/heisenberg.toml
```

## Utilization

```bash
hx <file>
```

### Implement the theme for the current session

```vim
:theme heisenberg
```

### Set the heisenberg theme as default for helix

```vim
:config-open
```
#### Change the theme variable to `theme = "heisenberg"`

```vim
:x
```
