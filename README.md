# PS2PNG

PS2PNG is a bash utility for converting [xfoil](https://web.mit.edu/drela/Public/web/xfoil/) postscript hardcopy images into .png images.
If more than one page is found in the postscript file one .png file will be created for each page.

## Installation

ImageMagick and Ghostscript are required under the hood which can be installed with the below commands.

```bash
sudo apt install ghostscript
sudo apt install imagemagick
```

## Usage

```bash
./ps2png
```
Best to use with Color postscript output enabled under plop menu. At the end of execution, a .png image similar to below will appear.
![alt text](https://github.com/kjayawar/ps2png/blob/main/1.png?raw=true)

## Contributing
Pull requests or any suggestions for improvements are welcome.

## License
[MIT](https://choosealicense.com/licenses/mit/)
