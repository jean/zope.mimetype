Changes
=======

2.0.1 (unreleased)
--------------------

- TBD


2.0.0 (2014-12-24)
--------------------

- Add support for PyPy and PyPy3.

- Add support for Python 3.4.

- Restore the ability to write ``from zope.mimetype import types``.

- Make ``configure.zcml`` respect the renaming of the ``types`` module
  so that it can be loaded.


2.0.0a1 (2013-02-27)
--------------------

- Add support for Python 3.3.

- Replace deprecated ``zope.component.adapts`` usage with equivalent
  ``zope.component.adapter`` decorator.

- Replace deprecated ``zope.interface.implements`` usage with equivalent
  ``zope.interface.implementer`` decorator.

- Rename ``zope.mimetype.types`` to ``zope.mimetype.mtypes``.

- Drop support for Python 2.4 and 2.5.


1.3.1 (2010-11-10)
------------------

- No longer dependg on ``zope.app.form`` in ``configure.zcml`` by using
  ``zope.formlib`` instead, where the needed interfaces are living now.

1.3.0 (2010-06-26)
------------------

- Add testing dependency on ``zope.component[test]``.

- Use zope.formlib instead of zope.app.form.browser for select widget.

- Conform to repository policy.

1.2.0 (2009-12-26)
------------------

- Convert functional tests to unit tests and get rid of all extra test
  dependencies as a result.

- Use the ITerms interface from zope.browser.

- Declare missing dependencies, resolved direct dependency on
  zope.app.publisher.

- Import content-type parser from ``zope.contenttype``, adding a dependency on
  that package.

1.1.2 (2009-05-22)
------------------

- No longer depend on ``zope.app.component``.

1.1.1 (2009-04-03)
------------------

- Fix wrong package version (version ``1.1.0`` was released as ``0.4.0`` at
  `pypi` but as ``1.1dev`` at `download.zope.org/distribution`)

- Fix author email and home page address.

1.1.0 (2007-11-01)
------------------

- Package data update.

- First public release.

1.0.0 (2007-??-??)
------------------

- Initial release.
