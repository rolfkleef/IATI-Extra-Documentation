Example Usage
~~~~~~~~~~~~~
The ``narrative`` child element can be used to declare freetext for the ``comment`` of a ``baseline``.

.. code-block:: xml

		<comment>
			<narrative>Baseline comment text</narrative>
			<narrative xml:lang="fr">Baseline comment texte</narrative>
		</comment>

The ``narrative`` element can be repeated for any language additional to the default language set in ``iati-activity``, by using the ``@xml:lang`` attribute:

.. code-block:: xml

		<comment>
			<narrative>Baseline comment text</narrative>
			<narrative xml:lang="fr">Baseline comment texte</narrative>
		</comment>


Changelog
~~~~~~~~~

2.01
^^^^

| The ``narrative`` element was introduced in 2.01.
