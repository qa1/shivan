# shivan
python download manager
  
<p>&nbsp;</p>

## usage :

### config:

to config , enter :
```
$   python3 main.py --config
```
then to set path as default to save file after download finish :

note : if hit enter and leave it blank , it set default path
```
/User/exmaple/desktop
```
then to specify split number ( not work yet !):

note : if hit enter and leave it blank , it set 8 part as a default 
```
8
```

### download :

1- install requirements :

```
$   pip install -r requirements.txt
```

2- download file :

```
$   python3 main.py <url>
```

3- enjoy !


### contribute :
i appricate any PR .
<p>&nbsp;</p>

## TODO:
**Done :**

~~- fix final file name~~

~~- multi-thread download~~

~~- dynamic file extension~~

~~- parts name be same as a file name~~

~~- first show information about file~~

~~- add config file for defualt setting~~

~~- add config file for defualt setting~~

~~- url checker~~

<p>&nbsp;</p>

  
**Short-term :**

- dynamic number of part

- check if all parts downloaded then concate to final_file

- read from clipboard

<p>&nbsp;</p>

**Long-term :**

- MacOS app

- linux app
