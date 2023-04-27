DECODES functions ServiceProviderInterface (SPI)
================================================

.. post:: 27 Apr, 2023
    :tags: 8_0, 7_0, lrgs
    :category: roadmap
    :author: Mike Neilson

There are several portions of the Decodes Scripts and processing that can benefit from the
Java 8+ SPI system. Several classes act as both factory and implementation. moving these to individual
implementations will simplify walking through the code and some error reporting.