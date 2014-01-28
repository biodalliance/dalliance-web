---
layout: page
title: Release notes
---

Version 0.11.0 (XX February 2014)
-------------

 * New track configuration tool.
 * Buttons for jumping to next feature.
 * Improved support for password-protected tracks and track-hubs.
 * Support for VCF files (with Tabix indices).
 * Support for indexed bigbeds and Trix indices.
 * Much improved support for read-level display of data from BAM files.
 * Support for high-DPI (e.g. Retina) displays.
 * Numberous bug-fixes and performance improvements.

Version 0.10.0 (15th October 2013)
-------------

 * User-interface elements which were previously presented as large
   pop-up elements (e.g. the track selector) have now been moved to a sidebar
 * Many clean-ups to the track-selector, and a new matrix view for use
   with track-hubs.
 * Completed support for the track-hub metadata model.
 * Added a user-interface for manually connecting to a track-hub.
 * Progress indicators on tracks which are actively loading data.
 * [Improved support for scatter-plot tracks](/stylesheets.html#scatter).

Version 0.9.0 (10th September 2013)
-------------

 * Many user-interface cleanups and improvements.
 * New in-browser help system.
 * [Thresholding and leaping](/config.html#quantLeapThreshold) for quantitative tracks (currently bigwig only).
 * Improved SVG export.
 * New backends: [JBrowse-style](/config.html#jbrowse-rest) and [Ensembl REST](/config.html#ensembl-rest) interfaces
 * Improved interface between the browser and backends.
 * Scatter plot views (POINTS glyph in stylesheets).
 * Preliminary support for UCSC-style [track hubs](/config.html#hub).
 * [Feature-info plugins](/plugins.html#feature-info).

Version 0.8.0 (11th July 2013)
-------------

 * First release using new Canvas-based renderer.
 * Substantial re-write of user interface code.
 * Event-based interface for writing alternative user interfaces.

Version 0.7.x (not formally released, available from Github)
-------------

 * New caching layer and speedups
 * Improvements to binary data support.
 * Many bug fixes.

Version 0.6.0 (27th February 2011)
-------------

 * Full support for DAS/1.6.
 * Support for [indexed binary data](/bin.html).
 * Better interface for adding new data to the browser.
 * Keyboard navigation improvements (in particular, tap space to toggle between zoom levels).
 * Performance and architectural improvements.
 * Export of SVG and PDF files.

Version 0.5.0 (11th September 2010)
-------------

 * Mapping of features from other assemblies (using the DAS alignment system).
 * Keyboard navigation (left/right arrows to scroll, +/- to zoom).
 * Rendering improvements, including complete support for the draft DAS/1.6 stylesheet specification.
 * Many user interface cleanups.
 * Dalliance can now easily be embedded in other web pages.
 * The syntax used to set the default configuration of the browser is substantially cleaner.

Version 0.4.0 (3rd August 2010)
-------------

Initial public release
