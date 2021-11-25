<h1 align="center">
    Estrapy-API
</h1>

<h2 align="center">
    A Basic Anime Image API Created By Stawa
</h2>

### Installing Estrapy-API

```
pip install estrapy-api
```

or If you want to use latest update of Estrapy-API

```py
pip install git+https://github.com/StawaDev/Estrapy-API
```

### Example to use Estrapy-API

```py
# First Examples
import Estrapy

def function():
    print(f"A Running GIF: {Estrapy.sfw.run()}")
    print(f"A Hug GIF: {Estrapy.sfw.hug()}")

function()

# Second Examples
import Estrapy

print(Estrapy.sfw.run())
print(f"Run: {Estrapy.sfw.run()})
```

### Function Endpoints

Function|Examples
--------------|--------------
Run     |    Estrapy.sfw.run()
Hug     |   Estrapy.sfw.hug()
Smile   |  Estrapy.sfw.smile()
Headpat |   Estrapy.sfw.headpat()