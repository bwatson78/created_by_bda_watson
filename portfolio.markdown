---
layout: single
title: Brad's Portfolio
permalink: /portfolio/
---

## [Emory Libraries' SelfDeposit](https://open.library.emory.edu/)
[Github Link](https://github.com/emory-libraries/dlp-selfdeposit)

**Languages/Frameworks Utilized:** Ruby 3.2, Rails 6.1, Bootstrap, Hyrax 5.2, Fedora Commons 6.5, Bulkrax, Blacklight 7, SCSS, Devise, Omniauth/SAML, jQuery, PostgreSQL, Apache Solr, IIIF, Sidekiq, Webpacker, Capistrano, rSpec, Rubocop, CRON

**Description:** A repository application that allows anyone in Emory University's community to publish various digitized media.

**Recent Development Work:** This application went live in mid-2025! As the senior Ruby on Rails developer within my team, I contributed much of the implementation and customization for this Hyrax Engine instance. Since this software replaced an aging Python site, a migration of the Fedora v3 objects to v6 was necessary to kick off the project. This was achieved by creating multiple Ruby scripts that interacted with Fedora Commons' API migration toolkit.

## [Presenter - Improving Hyrax Bulk Imports by Customizing Bulkrax](https://docs.google.com/presentation/d/10FaJYEDSsx52mYaHwg64MmfNPnFJaffCtRWJ2u9bG3k/edit#slide=id.p)
Spoke at [2022's Samvera Connect virtual conference](https://samveraconnect2022.sched.com/event/1D4BM/improving-hyrax-bulk-imports-by-customizing-bulkrax) about my work enhancing bulk ingestions of repository objects into Emory Libraries' Curate.

## [Emory Libraries' Curate](https://curate.library.emory.edu/)
[Github Link](https://github.com/emory-libraries/dlp-curate)

**Languages/Frameworks Utilized:** Ruby 2.7, Rails 5.1, Bootstrap, Hyrax 3.4, Fedora Commons 4, Bulkrax, Blacklight 7, SCSS, Devise, Omniauth/Shibboleth, jQuery, MySQL, Apache Solr, IIIF, Sidekiq, Webpacker, Capistrano, rSpec, Rubocop, CRON

**Description:** A repository application for digital curators (preservation, rights and metadata management, collection management).

**Recent Development Work:** The developers at Emory University Libraries are gearing up to upgrade the Hyrax and Fedora Commons software delivering this site's infrastructure. We are currently in planning stages for another Fedora Commons migration.

## [Emory's Library Search](https://search.libraries.emory.edu)
[Github Link](https://github.com/emory-libraries/blacklight-catalog)

**Languages/Frameworks Utilized:** Ruby 2.7, Rails 5.1, Blacklight 7, MARC, Traject, Bootstrap, SCSS, Devise, Omniauth/Shibboleth, jQuery, JWT, MySQL, Apache Solr, Simple Form, Capistrano, rSpec, Rubocop, Webmock, CRON

**Description:** A customized library catalog search engine utilizing Solr collections updated four times daily by an automated OAI/MARC indexing process.

## [Emory Libraries' Digital Collections](https://digital.library.emory.edu/)
[Github Link](https://github.com/emory-libraries/dlp-lux)

**Languages/Frameworks Utilized:** Ruby 3.1, Rails 7, Blacklight 7, MARC, Bootstrap, CiteProc, PDF.js, SCSS, Devise, Omniauth/Shibboleth, jQuery, MySQL, Apache Solr, Simple Form, Capistrano, rSpec, Rubocop, Webmock, CRON

**Description:** A front-end application that queries Curate's Solr objects and displays their related images in varying resolutions dictated by a given user's rights access.

**Recent Development Work:** This application has received some much-needed version bumps, as well as the incorporation of PDF.js to allow for the viewing of a new file format (PDF, if it wasn't obvious).
