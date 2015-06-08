Some details for the new neurosim page
======================================


## List of things to think about...

- use liquid templates in ``_includes`` for m.d. to add text to sections 
- identify files that have data in them (only ``_config.yml`` for now)
- check that buttons work for scrolling to next sections
- maybe for later: maps? google API?
- identify domain name and fix ``CNAME`` file.

## Images

- dark images, grayscale (not too contrasty) work best with the theme
- aspect ratio w/h: 1.33. Originally 1500px by 1125px load quickly and have nice amount of detail
- note to self: Imagemagick ``identify`` and ``convert`` are our friends


## Notes for editing

- check the folder ``_includes`` for files with text. 
- ``about.html`` for details on the course
- ``contact.html`` for contact details, but NB e-mail address etc. are in ``_config.yml`` (the data file)
- if ``.nojekyll`` is present in folder then github pages will not be translated.