Parallel Computing with Python
==============================

## Using `multiprocess` and `ipyparallel`

[Jupyter notebook illustrating a few simple ways of doing parallel computing in a single machine with multiple cores.](https://github.com/rsnemmen/parallel-python-tutorial/blob/master/Parallel%20Computing%20with%20Python%20public.ipynb) 

[Tutorial on how to do parallel computing using an ipyparallel cluster.](https://github.com/rsnemmen/parallel-python-tutorial/blob/master/Parallel%20Computing%20with%20Python%20SSH.ipynb)

Practical examples included:

1. Parallel function mapping to a list of arguments (multiprocess module)
2. Parallel execution of array function (scatter/gather) + parallel execution of scripts with ipyparallel
3. Easy parallel Monte Carlo (ipyparallel magics)

Based on the talk I gave at [CosmoClub](http://www.iag.usp.br/labcosmos/en/), [IF USP](http://portal.if.usp.br/ifusp/).


# Other potentially useful links

[How to setup an ipyparallel cluster using SSH](http://astropython.blogspot.com.br/2016/02/how-to-setup-ipython-parallel-cluster.html). Note: this is probably deprecated.

# TODO

- [ ] include Dask example for parallel array processing
- [ ] include example on how to parallelize loops
- [ ] include a simple CUDA example? cuPY?

&nbsp;

[Visit the author's web page](https://rodrigonemmen.com/) and/or follow him on twitter ([@nemmen](https://twitter.com/nemmen)).

&nbsp;

---


&nbsp;

&nbsp;

Copyright (c) 2023, [Rodrigo Nemmen](https://rodrigonemmen.com).
[All rights reserved](http://opensource.org/licenses/BSD-2-Clause).

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
