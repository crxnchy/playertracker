[Screenshot 2026-04-21 1555511776801447.json](https://github.com/user-attachments/files/26945671/Screenshot.2026-04-21.1555511776801447.json)# Player Tracking Compass

This is a datapack for 1.21 that allows you to track players with a Player Tracking Compass. It is crafted with a compass, a netherite scrap, 2 echo shards, an ender eye and 4 diamonds, but you can change the recipe in [its JSON file](./data/playertracker/recipe/player_compass.json).

![Crafting recipe]([[{
  "version": "1.0",
  "image": {
    "name": "/var/www/imageconvert_usr/data/www/imageconvert.org/image/public/uploadt/Screenshot 2026-04-21 155551.png",
    "permissions": 644,
    "format": "JSON",
    "formatDescription": "The image format and characteristics",
    "mimeType": "application/json",
    "class": "DirectClass",
    "geometry": {
      "width": 151,
      "height": 136,
      "x": 0,
      "y": 0
    },
    "resolution": {
      "x": 37.79,
      "y": 37.79
    },
    "printSize": {
      "x": 3.99577,
      "y": 3.59884
    },
    "units": "PixelsPerCentimeter",
    "type": "TrueColorAlpha",
    "endianness": "Undefined",
    "colorspace": "sRGB",
    "depth": 8,
    "baseDepth": 8,
    "channelDepth": {
      "alpha": 1,
      "red": 8,
      "green": 8,
      "blue": 8
    },
    "pixels": 20536,
    "imageStatistics": {
      "all": {
        "min": 0,
        "max": 255,
        "mean": 175.927,
        "standardDeviation": 49.2105,
        "kurtosis": -0.530242,
        "skewness": -0.708749,
        "entropy": 0.386696
      }
    },
    "channelStatistics": {
      "alpha": {
        "min": 0,
        "max": 0,
        "mean": 0,
        "standardDeviation": 0,
        "kurtosis": 1.6384e+52,
        "skewness": 9.375e+35,
        "entropy": 0
      },
      "red": {
        "min": 0,
        "max": 255,
        "mean": 150.151,
        "standardDeviation": 65.1088,
        "kurtosis": -0.51729,
        "skewness": -0.641523,
        "entropy": 0.520992
      },
      "green": {
        "min": 0,
        "max": 255,
        "mean": 149.838,
        "standardDeviation": 65.3902,
        "kurtosis": -0.722783,
        "skewness": -0.594339,
        "entropy": 0.511533
      },
      "blue": {
        "min": 0,
        "max": 255,
        "mean": 148.717,
        "standardDeviation": 66.3431,
        "kurtosis": -0.737101,
        "skewness": -0.590821,
        "entropy": 0.514259
      }
    },
    "renderingIntent": "Perceptual",
    "gamma": 0.45455,
    "chromaticity": {
      "redPrimary": {
        "x": 0.64,
        "y": 0.33
      },
      "greenPrimary": {
        "x": 0.3,
        "y": 0.6
      },
      "bluePrimary": {
        "x": 0.15,
        "y": 0.06
      },
      "whitePrimary": {
        "x": 0.3127,
        "y": 0.329
      }
    },
    "backgroundColor": "#FFFFFFFF",
    "borderColor": "#DFDFDFFF",
    "matteColor": "#BDBDBDFF",
    "transparentColor": "#00000000",
    "interlace": "None",
    "intensity": "Undefined",
    "compose": "Over",
    "pageGeometry": {
      "width": 151,
      "height": 136,
      "x": 0,
      "y": 0
    },
    "dispose": "Undefined",
    "iterations": 0,
    "compression": "Zip",
    "orientation": "Undefined",
    "properties": {
      "date:create": "2026-04-21T19:57:26+00:00",
      "date:modify": "2026-04-21T19:57:26+00:00",
      "date:timestamp": "2026-04-21T19:57:27+00:00",
      "png:cHRM": "chunk was found (see Chromaticity, above)",
      "png:gAMA": "gamma=0.45455 (See Gamma, above)",
      "png:IHDR.bit-depth-orig": "8",
      "png:IHDR.bit_depth": "8",
      "png:IHDR.color-type-orig": "6",
      "png:IHDR.color_type": "6 (RGBA)",
      "png:IHDR.interlace_method": "0 (Not interlaced)",
      "png:IHDR.width,height": "151, 136",
      "png:pHYs": "x_res=3779, y_res=3779, units=1",
      "png:sRGB": "intent=0 (Perceptual Intent)",
      "signature": "a49cb1927605a78737c5436bc24104ac08458e4d3164d96ebce9b345ae3908c0"
    },
    "tainted": false,
    "filesize": "3724B",
    "numberPixels": "20536",
    "pixelsPerSecond": "25.8884MB",
    "userTime": "0.000u",
    "elapsedTime": "0:01.000",
    "version": "ImageMagick 6.9.12-98 Q16 x86_64 18038 https://legacy.imagemagick.org"
  }
}
]Uploading Screenshot 2026-04-21 1555511776801447.json…]()
)

You can select a player by right-clicking the player compass and selecting the player to track. If the recipe isn't showing up, you may need to give yourself the recipe with this command:

```mcfunction
/recipe give @s playertracker:player_compass
```

You're free to use this datapack however you like, under the terms of the [MIT Licence](./LICENSE).
