DEPRECATED 

A neofetch wrapper that scraps a image from gelbooru

![I use Arch BTW](https://user-images.githubusercontent.com/30930688/218849072-12a7a017-2da2-4be3-8da0-b149a911549b.png)
### How it started
```
Well, this is not the first project. I remade what was discontinued for fun.
```

### How it works
* Scraps all image links and picks one randomly
* Visits that site and installs the main image
* Image is saved on a temporary file that gets purged after neofetch is executed

### How to use 
```py 
$ python3 -m pip install -r requirements.txt
```

```
$ python3 boorufetch.py 

$ python3 boorufetch.py --help 

$ python3 boorufetch.py --backend kitty 

$ python3 boorufetch.py --tag X 

$ python3 boorufetch.py --tags X,Y

$ python3 boorufetch.py --nsfw on

$ python3 boorufetch.py --nsfw off

You can also use - instead of --
```

### Note
```
1. I don't take any responsibility if used incorrectly

2. nsfw is "off" by default, blame the artist if the art does not look safe enough

3. --backend may not be required unless your terminal has issues
```
