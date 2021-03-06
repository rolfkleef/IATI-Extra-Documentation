Example Usage
~~~~~~~~~~~~~
Example ``default-aid-type``  for an ``iati-activity``.

| The ``@code`` attribute declares a valid code (*A01*) from the *AidType* codelist.
| The ``@vocabulary`` attribute declares a valid code (*1*) from the *AidTypeVocabulary* codelist.

.. literalinclude:: ../../activity-standard-example-annotated.xml
	:language: xml
	:start-after: <!--default-aid-type starts-->
	:end-before: <!--default-aid-type ends-->

Changelog
~~~~~~~~~
2.03
^^^^
The ``default-aid-type`` element can be reported multiple times within a ``iati-activity`` element `added <https://discuss.iatistandard.org/t/add-vocabularies-to-aid-type-included-2-03/847>`__.
The ``@code`` attribute definition was `updated <https://discuss.iatistandard.org/t/add-vocabularies-to-aid-type-included-2-03/847>`__.
The ``@vocabulary`` attribute was `added <https://discuss.iatistandard.org/t/add-vocabularies-to-aid-type-included-2-03/847>`__.

2.01
^^^^
Freetext is `no longer allowed <http://iatistandard.org/upgrades/integer-upgrade-to-2-01/2-01-changes/#freetext-amended-elements>`__  within this element.
