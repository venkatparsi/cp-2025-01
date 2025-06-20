Color System Values:

| Feature     | RGB                  | RGBA                       | Hex             |
| ----------- | -------------------- | -------------------------- | --------------- |
| Syntax      | `rgb(255, 255, 255)` | `rgba(255, 255, 255, 0.5)` | `#FFFFFF`       |
| Opacity     | ❌ No                 | ✅ Yes (0–1)                | ❌ No            |
| Readability | ✅ Easier numerically | ✅ Same                     | ❌ Less readable |
| File size   | ❌ Verbose            | ❌ Verbose                  | ✅ Compact       |
| Shorthand   | ❌ No                 | ❌ No                       | ✅ Yes: `#FFF`   |


### Example : /* Red background */

background-color: #FF0000;

background-color: rgb(255, 0, 0);

background-color: rgba(255, 0, 0, 1);  /* fully opaque */

background-color: rgba(255, 0, 0, 0.5); /* semi-transparent */

✅ Which to use when
### Hex: For static design and theme color codes (cleaner and shorter).

RGB: When working with JS or CSS that dynamically changes color.

RGBA: When you need to control transparency (e.g., overlays, effects).

### ✅ Interactive Learning Tools
Use these to make it hands-on:

https://colorpicker.me/

https://hslpicker.com/

https://www.colorhexa.com/

Your own HTML/JS demo (like the one we just made!)
