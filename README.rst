================
OpenSlide Python
================

OpenSlide Python is a Python interface to the OpenSlide library.

OpenSlide_ is a C library that provides a simple interface for reading
whole-slide images, also known as virtual slides, which are high-resolution
images used in digital pathology.  These images can occupy tens of gigabytes
when uncompressed, and so cannot be easily read using standard tools or
libraries, which are designed for images that can be comfortably
uncompressed into RAM.  Whole-slide images are typically multi-resolution;
OpenSlide allows reading a small amount of image data at the resolution
closest to a desired zoom level.

OpenSlide can read virtual slides in several formats:

* Aperio_ (``.svs``, ``.tif``)
* Hamamatsu_ (``.ndpi``, ``.vms``, ``.vmu``)
* Leica_ (``.scn``)
* MIRAX_ (``.mrxs``)
* Sakura_ (``.svslide``)
* Trestle_ (``.tif``)
* Ventana_ (``.bif``)
* `Generic tiled TIFF`_ (``.tif``)

.. _OpenSlide: http://openslide.org/
.. _Aperio: http://openslide.org/formats/aperio/
.. _Hamamatsu: http://openslide.org/formats/hamamatsu/
.. _Leica: http://openslide.org/formats/leica/
.. _MIRAX: http://openslide.org/formats/mirax/
.. _Sakura: http://openslide.org/formats/sakura/
.. _Trestle: http://openslide.org/formats/trestle/
.. _Ventana: http://openslide.org/formats/ventana/
.. _`Generic tiled TIFF`: http://openslide.org/formats/generic-tiff/

Requirements
============

* Python 2 >= 2.6 or Python 3 >= 3.3
* OpenSlide >= 3.4.0
* Python Imaging Library or Pillow

Installation
============

1.  `Install OpenSlide`_

2.  ``pip install openslide-python``

.. _`Install OpenSlide`: http://openslide.org/download/

License
=======

LGPLv2.1_.

.. _LGPLv2.1: https://raw.github.com/openslide/openslide-python/master/lgpl-2.1.txt