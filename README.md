Technical Drawings and Calculations Register
============================================

A reusable Blue Peter Marine register of the technical drawings, schemes and
calculations required for a Module B / G technical file under the Recreational
Craft Directive 2013/53/EU. It is a single self-contained HTML page with no
build step and no external dependencies.

The register covers two parts:

- Part 1: 24 technical drawings, schemes and diagrams, grouped as General
  Arrangement, Installation Schemes, and Systems and Compliance Drawings.
- Part 2: 9 calculations.

Each row carries the essential requirement reference, the applicable standard,
and a fillable field for the drawing or document number and its status.


Using it
--------

Open index.html in any browser, or publish it with GitHub Pages and use the
hosted link. Fill in the Project Information card and the status fields for each
row. Nothing is stored on a server; the page runs entirely in the browser.


Export and import
-----------------

- Export data (JSON) saves every field to a JSON file, named from the
  manufacturer and model, for example air-yachts-hull-42-register.json.
- Import data (JSON) loads a previously exported file back into the page.
- Print / Save as PDF produces a clean printable copy for the technical file.
- Clear all fields empties the form so it can be reused for a new project.

The JSON keeps a version marker, so exported files remain readable if the
template is updated later. Store the JSON alongside the project documents; the
HTML page is the blank template and the JSON is the project data.


Publishing with GitHub Pages
----------------------------

1. Create a new empty repository on GitHub, for example technical-file-register.
2. Upload index.html and README.md to the repository root, or push with git.
3. In the repository, open Settings, then Pages.
4. Set Source to Deploy from a branch, branch main, folder root, and save.
5. The register will be live at
   https://YOUR-USERNAME.github.io/technical-file-register/


Notes
-----

The register lists only drawing-type and calculation-type deliverables. Test
reports, descriptions, part lists, supplier certificates and the Owner's Manual
are held separately. Items apply as far as applicable and appropriate to the
actual craft; rows that do not apply should be marked N/A rather than deleted.

Blue Peter Marine, Cape Town, South Africa. www.ceinspector.com
