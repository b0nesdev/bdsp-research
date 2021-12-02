Understanding ROMFS & EXEFS
===========================



What are the ROMFS & EXEFS?: A introduction.
--------------------------------------------
After you dump the games files you will see it's contents split into these two folders. (Link to setup/dumping guide here)
ROMFS means Rom Filesystem while EXEFS means Executable Filesystem they are split up due to their vast differences in what their jobs are.
To explain this I will be using Pizza!


Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

