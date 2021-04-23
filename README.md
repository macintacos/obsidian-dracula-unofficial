# Dracula, Unofficially 🦇

The unofficial Dracula theme for Obsidian. Mostly made this for myself, but figured others might like it too. There's already [an official Dracula theme](https://github.com/dracula/obsidian) that you can use if that's your jam! I kinda wanted to make different color choices, which is why this theme exists.


## Contributing

To get setup properly (assuming you have `node`/`npm` installed), just run `npm run dev`.

Files to edit are in `src/`, and `dracula-unofficial.scss` gets compiled to `obsidian.css`, which is then copied over to Obsidian's `.obsidian/snippets/` folder of the first vault that it can find. You can then preview the theme (with live updates!) if you go to Settings > Appearance > CSS snippets, and make sure "dracula-unofficial" is checked. You may need to refresh the view or make some small edits so that a new file is compiled and thrown in there.