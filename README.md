# WindowsLocalPhotosWidget

This will be a Photo Widget for Windows 11 with local pictures instead of forced picture collection from the OneDrive Cloud.
Background App for the Widget will have selectable source from Photos-Legacy or Windows-App.
MediaDb.v1.sqlite from Photos-Legacy or shared.sqlite-wal from Windows-App will be read out and checked for the 20 latest added Pictures, picking and generating 6 random pictures and create thumbnails.
For minimum Performance impact, therefore to safe system ressources the check and read out will be only when the widget area is being triggered to appear and if MediaDb.v1.sqlite or shared.sqlite-wal has been updated.
