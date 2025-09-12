===========
 Changelog
===========

6.0 (2025-09-12)
================

- Replace ``pkg_resources`` namespace with PEP 420 native namespace.


5.1 (2025-01-22)
================

- Add support for Python 3.12, 3.13.

- Drop support for Python 3.7, 3.8.


5.0 (2023-01-19)
================

- Add support for Python 3.11.

- Drop support for Python 2.7, 3.5, 3.6.

- Drop support for deprecated ``python setup.py test``.


4.2 (2021-11-04)
================

- Fix a TypeError exception in ``cmp`` when operands are ``None``.
  See `issue 7 <https://github.com/zopefoundation/zope.sequencesort/issues/7>`_.

- Drop support for Python 3.4.

- Add support for Python 3.8, 3.9 and 3.10.


4.1.2 (2018-10-10)
==================

- Fix regression introduced in 4.1.1 where two `_Smallest` objects are no
  longer considered to be equal.


4.1.1 (2018-10-05)
==================

- Handle sorting of broken objects more gracefully.
  (`#4 <https://github.com/zopefoundation/zope.sequencesort/pull/4>`_)


4.1.0 (2018-08-13)
==================

- Updated ``boostrap.py`` to version 2.2.

- Drop support for Python 2.6, 3.2 and 3.3.

- Add support for Python 3.4, 3.5, 3.6 and 3.7.

- The locale comparison functions, ``strcoll`` and ``strcoll_nocase``
  are always available, not only if the ``locale`` module had been
  imported before this module.

4.0.1 (2013-03-04)
==================

- Fix omitted tests under Py3k.

4.0.0 (2013-02-28)
==================

- Added ``setup.py docs`` alias (installs ``Sphinx`` and dependencies).

- Added ``setup.py dev`` alias (runs ``setup.py develop`` plus installs
  ``nose`` and ``coverage``).

- Dropped spurious ``test`` extra requirement on ``zope.testing``.

- 100% unit test coverage.

- Added support for PyPy, Python 3.2 / 3.2.

- Dropped support for Python 2.4 / 2.5.

3.4.0 (2007-10-03)
==================

- Initial release independent of the main Zope3 tree.
