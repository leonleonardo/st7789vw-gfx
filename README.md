# st7789vw-gfx

Modified ST7789VW driver that adds features to print text based on a bitmap.

## Setup

Add the files under the library directory to your project, a bitmap is already setup with the Emulogic font at size 8. From my testing this is the best configuration to use for the ST7789.

## Usage

After adding the files library to you project. The function ST7789_DrawText can be used.

### Examples

```
char *text = "Hello World"
ST7789_DrawText(FontStyle_Emulogic, (const char *)text, X_MAX/2 , Y_MAX/2, ST7789_WHITE, ST7789_BLACK);
```

## Custom fonts

Reference the generator directory. Updated instructions comming soon.

## Credits

https://larsee.com/blog/2014/05/converting-fonts-to-c-source-using-bmfont2c/


