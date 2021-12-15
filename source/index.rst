API Dispatch
============

Over the years, array computing in Python has evolved to support distributed
arrays, GPU arrays, and other various kinds of arrays that work with
specialized hardware, or carry additional metadata, or use different internal
memory representations.
The foundational library for array computing in the PyData ecosystem is NumPy.
But NumPy alone is a CPU-only library---and a single-threaded one at that---and
in a world where it's possible to get a GPU or a CPU with a large core count in
the cloud cheaply or even for free in a matter of seconds, that may not seem
enough.
For the past couple of years, a lot of thought and effort has been spent on
devising mechanisms to tackle this problem, and evolve the ecosystem in a
gradual way towards a state where PyData libraries can run on a GPU, as well as
in distributed mode across multiple GPUs.

For more details, please see:
https://labs.quansight.org/blog/2021/11/pydata-extensibility-vision/

.. toctree::
   :maxdepth: 2
   :hidden:

   faq
