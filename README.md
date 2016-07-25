# ATTENTION: This is not a plugin, you cannot install it to your darktable. It is only a sketch/mockup of how it could look and has been discontinued.

# DT-webgallery
Simple web-gallery for Darktable
As displayed here: http://sakrecoer.com/DT-export/

## Variables
- ${title} : Title of the galery (currently inserted in the export prompt)
- ${author} : Author (Could this be added to the export prompt?)
- ${ALLtags} : (All tags from all the photos)
- ${publisher} : publisher of the photo as entered in the metadata editor, if any.
- ${filename} : Filename of the exported picture
- ${photo-title} : Title of the photo as entered in the metadata editor, if any.
- ${description} : Description of the photo as entered in the metadata editor, if any.
- ${photo-tags} : Tags of the photo as entered in the metadata editor, if any. 
- ${license} : License of the photo as entered in the metadata editor, if any.

### What?
The plan is to make a basic, lightweight responsive layout relying only on html5 and CSS3 for darktable. Because i want to avoid using .js depencies, the navigation is going to be very basic and straightforward. 

### Look?
- The focus has to be on the photos, not the pages. 
- The photos have to be displayed as big as possible in the viewport.
- Titles and text could be displayed/hidden using CSS on a:hover / tap
- There could be some sort of menu, but i think its unnecessary. However, there could be an index file linking to a look book, made up of .html sidecarfiles. (see todo)

### TODO
Ask Devs if it is possible to output a zip file with pics in full-res and link it with a "Download all" button
