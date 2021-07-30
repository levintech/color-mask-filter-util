# Color Filter Util

This simple script is to use find the color filter info to extract specific color & regions from the image. It generate the mask depends on filtered color

## Environment

Create the virtual environment

```bash
python -m venv env

env\Scripts\activate
```

Install the necessary packages using [pip](https://pip.pypa.io/en/stable/) installer.

```bash
pip install -r requirements.txt
```

## Usage

run this script by command line

```python
python windows.py

```

Using the trackbar control, adjust and find best the color filter info by showing the result immediately. I attached some examples.

Original Image             |  HSV Image
:-------------------------:|:-------------------------:
![Original Image](https://github.com/innovationAIengineer/color-filter-util/blob/main/assets/original_image.png?raw=true)  |  ![HSV Image](https://github.com/innovationAIengineer/color-filter-util/blob/main/assets/hsv_image.png?raw=true)

Circle Contour trackbar    |  Circle Contour
:-------------------------:|:-------------------------:
![Circle Contour Trackbar](https://github.com/innovationAIengineer/color-filter-util/blob/main/assets/01.trackbar_circle_contour.png?raw=true)  |  ![Circle Contour](https://github.com/innovationAIengineer/color-filter-util/blob/main/assets/01.circle_contour.png?raw=true)

Circle trackbar            |  Circle
:-------------------------:|:-------------------------:
![Circle Trackbar](https://github.com/innovationAIengineer/color-filter-util/blob/main/assets/02.trackbar_circle.png?raw=true)  |  ![Circle](https://github.com/innovationAIengineer/color-filter-util/blob/main/assets/02.circle.png?raw=true)

## Contributing
This script would be useful to find the best color filter info. I often use this simple script on Vision projects. Pretty simple but useful script. 😃

Hope this script useful for your task.
