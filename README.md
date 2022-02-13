## My st compilation

All the diff files for the patches I have used are available in this repo.

### Patches used

- **ligatures-alpha-scrollback** - Helps in getting font ligatures
- **font2** - Allows st to use multiple fonts and hence allows the use of emoji fonts like JoyPixels
- **scrollback** - Allows scrolling back using keyboard as well as using mouse
- **blinking-cursor** - Makes the cursor blink. I have used this patch because I feel blinking cursors are aesthetically pleasing while coding
- **anysize** - Ensures the st terminal does not leave gaps in tiling window managers
- **alpha** - Needed to enable transparency. Also needs a compositor like `picom`

### `scroll` utility

I have used the `scroll` utility from suckless tools. This helps the st-terminal to redraw itself in order to prevent the contents being cut out when the window is resized.

You can download the `scroll` utility here:
![https://tools.suckless.org/scroll/](https://tools.suckless.org/scroll/)
