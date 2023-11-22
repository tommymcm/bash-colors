# 🌈 bash-colors
This is a single reference for bash color/styling because I'm tired of googling it.


# Format
Format.
`"\e[<CODE>(;<CODE>)*m"`

Reset.
`"\e[0m"`


# Styles
| Style      | Code | Reset Code |
| ---------- | ---- | ---------- |
| Bold       | 1    | 21         |
| Faint      | 2    | 22         |
| Italics    | 3    | 23         |
| Underlined | 4    | 24         |
| Blink      | 5    | 25         |
| Reverse    | 7    | 27         |
| Hidden     | 8    | 28         |
| Reset all  |      | 0          |


# Colors
## 8/16 Colors
Most terminals have support for the 8/16 colors:
| Color         | Foreground Code | Background Code |
| ------------- | --------------- | --------------- |
| Default       | 39              | 49              |
| Black         | 30 	            | 40              |
| Red 	        | 31              | 41              |
| Green         | 32              | 42              |
| Yellow        | 33              | 43              |
| Blue 	        | 34              | 44              |
| Magenta       |	35              | 45              |
| Cyan          | 36              | 46              |
| Light Gray    | 37              | 47              |
| Gray 	        | 90              | 100             |
| Light Red     | 91              | 101             |
| Light Green   | 92              | 102             |
| Light Yellow  | 93              | 103             |
| Light Blue    | 94              | 104             |
| Light Magenta | 95              | 105             |
| Light Cyan    | 96              | 106             |
| White         | 97              | 107             |

## 88/256 Colors
Some terminals have support for the 88/256 colors.

Foreground:
`"\e[38;5;<CODE>m"`

Background:
`"\e[48;5;<CODE>m"`

![88/256 Color Chart](https://misc.flogisoft.com/_media/bash/colors_format/256_colors_bg.png)
