# icon: Good-Loop standard icons

These icons are **cropped** versions of the icons in google drive, ready for use in our web-apps.

## Use in apps: via symlink

Suggested setup for a project:

	cd web/img
	ln -s ../../../icon/gl-logo

Then e.g. `<img src='img/gl-logo/LogoMark/logo.png' />`

Note: Don't symlink the icon folder into a web-visible place, as that would make the .git web-visible!

## TODO 

 - Add more icon types!
 - Add a few useful sizes.
