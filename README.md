# RO-Crate Photo

This is an experimental approach to managing large photo libraries as a set of static files on disk, with metadata in RO-Crate.

Will use Javascript, and initial implementation will be a command line tool.

I will try uisng a Spec-driven approach using Claude

These are some rough stages of development:
  1. Harvest existing exif metadata from a collection and add RO-Crates for directories of photos initially a day in a /yyyy/mm/dd/ directory structure
     - Work out how to represent photo metadata in RO-Crate (using the verbose exifdata->PropertyValue?)
     - Make some HTML templates for displaying a directory's worth of photos
  3. Investigate how people are tagged using bounding boxes and IDs and how to use this existing info to train a recognizer
  4. Add editing tools to allow additional metadata to be added to the Crate metadata and synced-back to the the photos

