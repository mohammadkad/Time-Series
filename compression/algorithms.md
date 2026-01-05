<!-- 1404-09-12 -->

### Facts:
- trade-off between compression decompression time and compression ratio, particularly when processing high precision floating-point data.
- 
### Benchmarks:
- lzbench, https://github.com/inikep/lzbench

### Methods:
- sprintz, https://github.com/dblalock/sprintz, https://github.com/dblalock/lzbench
  - paper: https://arxiv.org/pdf/1808.02515.pdf
  - pip install Cython
- RAKE: A simple and efficient lossless compression algorithm for the Internet of Things
  - paper: https://ieeexplore.ieee.org/document/8081677
