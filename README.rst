SLIMS8 - Next generation Content Management System

Turnkey Linux Appliance Candidate

Use TKLDEV to create an ISO from this source.
=====================================================

`SLIMS`_ As a complete Library Management System, SLiMS (Senayan Library Management System) has many features that will help libraries and librarians to do their job easily and quickly. Below are some features provided by SLiMS :

    Online Public Access Catalog (OPAC) with thumbnail document image support (for images of book covers), Simple Search and Advanced Search mode
    Digital contents/files (PDF, DOC, RTF, XLS, PPT, Video, Audio, etc.): attachment in each bibliographic record is supported
    Documents record detail in MODS (Metadata Object Description Schema) XML format
    Documents record detail in JSON-LD format with schema.org
    RSS (Really Simple Syndication) XML format for OPAC
    OAI-PMH (Open Archives Initiative Protocol for Metadata Harvesting) in Dublin Core format for metadata harvesting purposes
    Bibliographic/catalog database management with book cover image support
    Union Catalog creation with Union Catalog Server
    Serial publication control
    Federated search engine creation with Nayanes
    Document items (book copies) management with barcode support
    Master Files management to manages document referential data such as GMD, Collection Types, Publishers, Authors, Locations, Authors and Suppliers
    Circulation support with following sub-features :
        Loan and Return transactions
        Collections reservations
        Quick returns
        Configurable and flexible Loan Rules
        Membership management
        Stocktaking module to help Stocktaking process in the library
        Reporting and Statistics
    System modules with the following sub-features :
        Global system configuration
        Modules management
        Application Users and Groups management
        Holiday settings
        Barcodes generator utility
        Database backup utility
    Responsive user interface
    3rd party bibliographic records indexing support with Sphinx Search and MongoDB


This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- SLIMS8 configurations:
   
   - Installed from upstream source code to /var/www/slims8

- SSL support out of the box.
- `Adminer`_ administration frontend for MySQL (listening on port
  12322 - uses SSL).
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for configuring Apache2, PHP, MySQL and Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

- Webmin, SSH, MySQL, Adminer: username **root**
- SLIMS: username **admin**


.. _SLIMS: https://slims.web.id/web/
.. _TurnKey Core: https://www.turnkeylinux.org/core
.. _Adminer: http://www.adminer.org/
