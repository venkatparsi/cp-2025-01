Color System Values:

| Feature     | RGB                  | RGBA                       | Hex             |
| ----------- | -------------------- | -------------------------- | --------------- |
| Syntax      | `rgb(255, 255, 255)` | `rgba(255, 255, 255, 0.5)` | `#FFFFFF`       |
| Opacity     | ❌ No                 | ✅ Yes (0–1)                | ❌ No            |
| Readability | ✅ Easier numerically | ✅ Same                     | ❌ Less readable |
| File size   | ❌ Verbose            | ❌ Verbose                  | ✅ Compact       |
| Shorthand   | ❌ No                 | ❌ No                       | ✅ Yes: `#FFF`   |


/* Red background */
background-color: #FF0000;
background-color: rgb(255, 0, 0);
background-color: rgba(255, 0, 0, 1);  /* fully opaque */
background-color: rgba(255, 0, 0, 0.5); /* semi-transparent */
