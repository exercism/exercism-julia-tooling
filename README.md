# Exercism.jl
[![Build Status](https://travis-ci.org/exercism/Exercism.jl.svg?branch=master)](https://travis-ci.org/exercism/Exercism.jl)
[![codecov](https://codecov.io/gh/exercism/Exercism.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/exercism/Exercism.jl)

Exercism.jl provides utility functions to solve exercises on exercism.io in interactive environments such as IJulia notebooks.

## Documentation
Running `Exercism.create_submission("exercise-name")` inside an IJulia notebook will extract all code cells marked with `# submit` and save them in a file `exercise-name.jl`. This file can then be submitted to exercism.io via the usual CLI.

## License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

