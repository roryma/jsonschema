========================
jsonschema - pre-draft 5
========================

This is a modified version of Julian Berman's implementation in python of JSON
Schema.

The sole difference between Julian's version and mine is the introduction of
support for ``$merge`` and ``strictProperties``.

For more information on the original implementation, please see `jsonschema
<https://github.com/Julian/jsonschema>`_.

``$merge`` and ``strictProperties`` are `proposed` features of draft 5 JSON
Schema. As of writing, no official draft 5 has been published, so at best this
is a partial implementation of a future version of draft 5.

To find out more about these additions, please see the descriptions of the proposed new
keywords, `$merge
<https://github.com/fge/json-schema-validator/wiki/v5:-merge>`_ and
`strictProperties
<https://github.com/fge/json-schema-validator/wiki/v5:-strictProperties>`_.

Note that the above link actually describes ``merge`` rather than ``$merge``. I
used the latter in this implementation based on later discussions on the
`jsonschema mailing list
<https://groups.google.com/forum/#!forum/json-schema>`_.

