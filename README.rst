annoy-java
==========
.. image:: https://travis-ci.org/spotify/annoy-java.svg?branch=master
    :target: https://travis-ci.org/spotify/annoy-java
    
annoy-java is a Java client for `annoy <https://github.com/spotify/annoy>`_.

It was built to give us access to ANN queries from JVM languages, for indices
built by other Python pipelines.

Limitations
-----------

* annoy-java only implements loading trees built by the Python version of
  annoy; it cannot yet create its own.
