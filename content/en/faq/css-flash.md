

![cssflash](/flash_css.gif)

This is because the CSS is in the JavaScript build in **development mode** to allow hot-reloading via webpack. This flash is called [FOUC](https://en.wikipedia.org/wiki/Flash_of_unstyled_content).

No need to worry though, in **production mode** the CSS is separated and put in the header so this flash of unstyled content will not occur.
