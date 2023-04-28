OpenDCS 7.0.1 release
=====================

.. post:: 26 Mar, 2023
    :tags: release-notice
    :category: notification
    :author: Mike Neilson

OpenDCS 7.0.6 was released and can be downloaded here: https://github.com/opendcs/opendcs/releases/tag/7.0.6

NOTE: If you use the XMLDatabase, wait for 7.0.7. There's a regression in 7.0.4-7.0.6 that prevents the decodes
scripts from loading correctly. Existing data is safe, and dbexport still works. this is particular to reading it back.