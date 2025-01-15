# BIGLEDMATRIX

Pyhton script to control the LED-Matrix

## Requirements
Install the following packages using pip:
```bash
pip installfreetype-py numpy pyserial opencv-python
```
*Note:opencv-python is optional and only needed for emulating the LED matrix.*

## Usage

The **led_effects** class has premade functions to control the text.

An example:

```python
foo = min_height(np.array(pixel_font_small.render_text("foo")), 8, False)
bar = min_height(np.array(pixel_font_small.render_text("bar")), 8, False)
#
#
#
def main():
    while True:
        foo()
	  bar()
	
```



## Authors
[Authors](https://github.com/castortut/bigledmatrix)


