Sign Present

Use sign_present.py to annotate images. The result will be folders containing the sorted images.

Press "a" if the sign is present.

Press "d" if the sign is not present.

Press "w" if the the state is unknown.

Press "," to go back.

Press "." to go forward.

Press ESC to quit.

usage: sign_present.py [-h] [-s STEP] [-r RESIZE] [-u] [-l] filename

positional arguments:
  filename              Video file or image directory

optional arguments:
  -h, --help            show this help message and exit
  -s STEP, --step STEP  The number of frames to skip between each annotation
                        (default: 10)
  -r RESIZE, --resize RESIZE
                        Resize image that is extracted by scale factor
                        (default: 0.5)
  -u, --skip-unknowns   Skip reprocessing the unknown frames after the main processing
                        has completed (default: False)
  -f, --first-frame     Restart at the first frame (default: False)