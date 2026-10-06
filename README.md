<p align="center">
    <img src="https://github.com/rose-pine/rose-pine-theme/raw/main/assets/icon.png" width="80" />
    <h2 align="center">Rosé Pine for <a href="https://github.com/dandavison/delta">delta</a></h2>
</p>

<p align="center">All natural pine, faux fur and a bit of soho vibes for the classy minimalist</p>

## Usage

1. Move `dist/rose-pine.gitconfig` to `~/.config/git/themes/rose-pine.gitconfig`
2. Include the theme in your global git config:
   ```ini
   # ~/.config/git/config
   [include]
       path = ./themes/rose-pine.gitconfig
   ```
3. Optionally, use with [lazygit](https://github.com/jesseduffield/lazygit/blob/master/docs/Custom_DiffRenderers.md#delta):
   ```yaml
   # ~/.config/lazygit/config.yml
   git:
     diffRenderers:
       - command: delta --paging=never --{{colorScheme}} --features={{colorScheme}} --syntax-theme=none"
   ```

## Gallery

### Rosé Pine

<img width="1454" height="907" alt="Rosé Pine with delta" src="https://github.com/user-attachments/assets/c22ed2de-9bae-412d-a1a5-0c2af8eaeed9" />

### Rosé Pine Moon

<img width="1454" height="907" alt="Rosé Pine Moon with delta" src="https://github.com/user-attachments/assets/e089b6f7-e5c0-4802-adb1-3907dac37e25" />

### Rosé Pine Dawn

<img width="1454" height="907" alt="Rosé Pine Dawn with delta" src="https://github.com/user-attachments/assets/0b331cf2-fce2-4aa1-8f04-d6e9d28c7043" />

## Thanks to

- [mvllow](https://github.com/mvllow)

## Contributing


<!-- BLOOM_BUILD_START -->
This theme was built using [bloom](https://github.com/rose-pine/rose-pine-bloom):

```sh
bloom build template.gitconfig --output dist --prefix '$' --format hex --single --blend
```
<!-- BLOOM_BUILD_END -->
