***********
Version 9.4
***********

Release date: 2025-05-29

This release contains a number of bug fixes and new features since the release of pgAdmin 4 v9.3.

Supported Database Servers
**************************
**PostgreSQL**: 13, 14, 15, 16 and 17

**EDB Advanced Server**: 13, 14, 15, 16 and 17

Bundled PostgreSQL Utilities
****************************
**psql**, **pg_dump**, **pg_dumpall**, **pg_restore**: 17.2


New features
************

  | `Issue #3369 <https://github.com/pgadmin-org/pgadmin4/issues/3369>`_ -  Enabled large file downloads for desktop users within the query tool.
  | `Issue #8583 <https://github.com/pgadmin-org/pgadmin4/issues/8583>`_ -  Add all missing options to the Import/Export Data functionality, and update the syntax of the COPY command to align with the latest standards.
  | `Issue #8681 <https://github.com/pgadmin-org/pgadmin4/issues/8681>`_ -  Add support for exporting table data based on a custom query.

Housekeeping
************


Bug fixes
*********

  | `Issue #6510 <https://github.com/pgadmin-org/pgadmin4/issues/6510>`_ -  Fixed an issue where the result grid slowed down when any column contained a large amount of data.
  | `Issue #6564 <https://github.com/pgadmin-org/pgadmin4/issues/6564>`_ -  Fix the issue where an error is displayed when a table is dropped while a query is running.
  | `Issue #6968 <https://github.com/pgadmin-org/pgadmin4/issues/6968>`_ -  Fixed an issue where the options key was not working as expected in the PSQL tool.
  | `Issue #7926 <https://github.com/pgadmin-org/pgadmin4/issues/7926>`_ -  Fixed an issue where correct error message not displayed when sql statement contains Arabic letters.
  | `Issue #8595 <https://github.com/pgadmin-org/pgadmin4/issues/8595>`_ -  Enhance contrast for selected and hovered items in the Object Explorer to improve visibility and accessibility.
  | `Issue #8607 <https://github.com/pgadmin-org/pgadmin4/issues/8607>`_ -  Fixed an issue where the query tool returns "cannot unpack non-iterable Response object" when running any query with a database name change.
  | `Issue #8608 <https://github.com/pgadmin-org/pgadmin4/issues/8608>`_ -  Handle result grid data changes in View/Edit Data mode by automatically reconnecting to the server if a disconnection occurs.
  | `Issue #8668 <https://github.com/pgadmin-org/pgadmin4/issues/8668>`_ -  Implement API fetch error display for select dropdown.
  | `Issue #8711 <https://github.com/pgadmin-org/pgadmin4/issues/8711>`_ -  Fixed an issue where light theme briefly appears when pgAdmin loads or tools open, even when a dark or system UI theme is preferred.
  | `Issue #8713 <https://github.com/pgadmin-org/pgadmin4/issues/8713>`_ -  Fixed issues related to column range selection using shift + click.
  | `Issue #8760 <https://github.com/pgadmin-org/pgadmin4/issues/8760>`_ -  Fixed an issue where pgAdmin failed to focus when previously unfocused and then quit.
