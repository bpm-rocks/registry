BPM Package Repository
======================

This registry contains all of the libraries and programs that are able to be installed via [`bpm`]. Please feel free to make a merge request to add your own library!


Library Constrictions
---------------------

Due to the lack of versioning and namespaces within packages, it is vitally important that libraries are backwards compatible. If you have breaking changes to your API, release it as a new library. For instance, let's pretend you were working on `sample`. The next version with the redesigned API is just `sample2`.


[`bpm`]: https://bpm.rocks/
