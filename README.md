<h1 align="center">ValdemarCord</h1>

<p align="center">
  <strong>Documentation</a></strong>
</p>

```sh
pip install valdemarcord
```
<h1 align="center">Discord</h1>
Get build Number, X-Super-Properties, Useragent (Example):


```python
from valdemarcord import Discord

build = Discord.get_build_number()
xsup = Discord.get_x_super_properties()
useragent = Discord._fetch_useragent()

print(build, xsup, useragent)
```

![image](https://github.com/user-attachments/assets/092a31b9-b2bf-4423-af7c-7ce80eda96b4)


<h1 align="center">Colors</h1>
Colors, Fades, Etc


```python
from valdemarcord import Color

text = "getpolo.xyz / discord.gg/valdemar"

print(Color.lollipop_red_to_white(text))
```
![image](https://github.com/user-attachments/assets/94b1abf9-a996-44b0-aadc-bcceff291c48)
