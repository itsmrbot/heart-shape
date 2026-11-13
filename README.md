# Heart Shape

An animated heart drawn with Python's built-in `turtle` module. The outline is traced from a heart curve, and short gradient strokes sweep inward from the edge in a random pattern, fading from pink to dark on a black background.

## Requirements

- Python 3.x
- `turtle` (included with standard Python; on some Linux systems install `python3-tk`)

No extra packages are needed.

## Run it ( In Windows Powershell )

```bash
python heart_shape.py
```

A window opens and the heart draws itself. Close the window to exit.

## Have fun with it

Try changing these values in `heart_shape.py`:

- `320` (number of points): more points make a denser, smoother heart.
- `random.uniform(0.15, 0.5)`: controls how far the strokes reach inward.
- `pencolor(...)`: change the RGB formula to get different colors.
- `time.sleep(0.005)`: lower is faster, higher is slower.

## License

Free to use, modify and share. Have fun!
