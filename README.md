# Splash

Inspired by the splatters that come from a heavily inked architectural ruling pen gliding along the surface of a highly textured watercolor page— Splash! Just as water droplets splash the ocean’s shore, little control can be predicted and no two splashes are exactly alike. The result is wonderfully organic and natural surprises.

![Sample Image](documentation/image1.png)

## Building the Fonts

The font is built using fontmake and gftools post processing script. Tools are all python based, so it must be previously installed.

To install all the Python tools into a virtualenv, do the following:

From terminal:

```

cd your/local/project/directory

#once in the project folder create a virtual environment. 
This step has to be done just once, the first time:

python3 -m venv venv

#activate the virtual environment

source venv/bin/activate

#install the required dependencies

pip install -r requirements.txt

```

Then run the this command:

```
cd sources
gftools builder config.yml
```
