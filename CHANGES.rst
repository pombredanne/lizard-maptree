Changelog of lizard-maptree
===================================================

1.8 (unreleased)
----------------

- Nothing changed yet.


1.7 (2012-11-27)
----------------

- Properly set dependency versions.


1.6 (2012-11-21)
----------------

- Added index field to Category to enable sorting.

- Improved test infrastructure.

- Added to Travis CI.

- PEP8 changes.


1.5.1 (2012-11-19)
------------------

- Removed left-over debug info in the template.


1.5 (2012-11-13)
----------------

- Added description field to categories.

- Improved the admin interface a bit.


1.4 (2012-08-14)
----------------

- Removed title from left sidebar as it also appears in the breadcrums.


1.3 (2012-08-14)
----------------

- Fix versioning.


1.2 (2012-06-20)
----------------

- Removed custom breadcrumb handling. See
  https://github.com/lizardsystem/lizard-maptree/issues/2.


1.1 (2012-06-19)
----------------

- Add a custom label for the category selection field in the admin.

1.0.1 (2012-05-18)
------------------

- Fixed MANIFEST.in (it contained the non-existing ``lizard-maptree``
  directory instead of ``lizard_maptree``).


1.0 (2012-05-18)
----------------

- Using new lizard-ui (with twitter bootstrap).

- Returning good page title and fixed category handling.


0.3 (2011-11-11)
----------------

- Changed views to classes to work with latest lizard-map. Updated
  templates to reflect this.

- Changed setup.py to require at least the currently latest
  lizard-map (3.4.2) and lizard-ui (3.7).


0.2 (2011-05-02)
----------------

- Removed unnecessary workspace manager and date_range_form.


0.1 (2011-03-01)
----------------

- Added title and sidebar_title options to default view.

- Initial library skeleton created by nensskel.  [Jack Ha]
