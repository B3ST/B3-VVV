# B3-VVV

A [Varying Vagrant Vagrants](https://github.com/Varying-Vagrant-Vagrants/VVV) setup for development.

## Installation

1. Install VVV as described in the [VVV documentation](https://github.com/Varying-Vagrant-Vagrants/VVV).
2. Navigate to VVV's web root directory with `cd {your vvv dir}/www`.
3. Clone the VVV project and B3 project submodules using `git clone --recursive git@github.com:B3ST/B3-VVV.git b3.dev`.
4. Reprovision VVV by running `vagrant provision` from the command line.

A new WordPress site will be created at [http://b3.dev:8888](http://b3.dev:8888) with the B3 starter theme, the WP-API plugin and the B3 API extensions.

Use the following username and password to access the dashboard:

* **Username:** `admin`
* **Password:** `password`

## License

B3-VVV is released under an MIT License.

Copyright (c) 2014 by the B3 team.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.