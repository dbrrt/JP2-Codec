# jp2-python
JPEG2000/JP2 Image Compression Codec using Python,NumPy,PyDWT

[![CircleCI](https://circleci.com/gh/dbrrt/jp2-python.svg?style=svg)](https://circleci.com/gh/dbrrt/jp2-python)

# Requirements
- Python 3+
- Pillow
- PyWavelets
- numpy

# Features
- [x] Conversion RGB to YUV
- [x] Scale transformation
- [x] Applying DWT to multiple resolutions
- [x] DWT coefficients extraction
- [ ] Quantization
- [x] Reconstruct Image from Coefficients
- [x] Conversion YUV to RGB
- [ ] Usage Example

## Tests
To run the tests, use the command `make test`

## License

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Credits

@dbrrt - David Barrat - May 2018
