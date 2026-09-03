^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package gz_transport_vendor
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.9 (2026-09-03)
------------------
* Enable Python bindings (`#26 <https://github.com/gazebo-release/gz_transport_vendor/issues/26>`_)
  * Enable Python bindings
  * Rerun gz_vendor
  ---------
* Contributors: Addisu Z. Taddese

0.0.8 (2026-08-17)
------------------
* Bump version to 13.6.0 (`#23 <https://github.com/gazebo-release/gz_transport_vendor/issues/23>`_)
* Contributors: Carlos Agüero

0.0.7 (2025-10-21)
------------------
* Bump version to 13.5.0 (`#16 <https://github.com/gazebo-release/gz_transport_vendor/issues/16>`_)
* Contributors: Addisu Z. Taddese

0.0.6 (2025-02-10)
------------------
* Bump version to 13.4.1 (`#8 <https://github.com/gazebo-release/gz_transport_vendor/issues/8>`_)
* Contributors: Addisu Z. Taddese

0.0.5 (2024-07-15)
------------------
* Update vendored package version to 13.4.0
* Contributors: Addisu Z. Taddese

0.0.4 (2024-04-25)
------------------
* Use an alias target for root library
* Contributors: Addisu Z. Taddese

0.0.3 (2024-04-12)
------------------
* Remove python3-distutils dependency (`#2 <https://github.com/gazebo-release/gz_transport_vendor/issues/2>`_)
  This dependency is only needed in the vendored package for CMake
  versions less than 3.12. It is also failing to install on Noble
  currently preventing the whole vendor package from building.
* Contributors: Addisu Z. Taddese

0.0.2 (2024-04-09)
------------------
* Add support for the `<pkg>::<pkg>` and `<pkg>::all` targets, fix sourcing of dsv files
* Update vendored version
* Require calling find_package on the underlying package
* Fix linter (`#1 <https://github.com/gazebo-release/gz_transport_vendor/issues/1>`_)
* Initial import
* Contributors: Addisu Z. Taddese
