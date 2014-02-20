*This repository is a mirror of the [component](http://component.io) module [stagas/gallery](http://github.com/stagas/gallery). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/stagas-gallery`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# gallery

The UI piece for a potential gallery image selector/uploader.

The test implements one with [component/upload](https://github.com/component/upload) and an express backend to get you started.

## Installing

`component-install stagas/gallery`

## Events

  - `select` when user selects (clicks) an image
  - `change`(newImage, oldImage) when user chooses a different image
  - `files`(FileList) when user chooses files to upload
  - `end` when user has ended interacting with the gallery
  - `show` when gallery is shown
  - `hide` when gallery is hidden

## API

  - [Gallery()](#gallery)
  - [Gallery.set()](#gallerysetpathstringfilesarray)
  - [Gallery.add()](#galleryaddfilestring)
  - [Gallery.select()](#galleryselectindexnumber)
  - [Gallery.render()](#galleryrender)
  - [Gallery.show()](#galleryshowelelement)
  - [Gallery.hide()](#galleryhide)

### Gallery()

  Gallery class.

### Gallery.set(path:String, files:Array)

  Set path and files.

### Gallery.add(file:String)

  Add image `file` to collection.

### Gallery.select(index:Number)

  Selects an image.

### Gallery.render()

  Render gallery view.

### Gallery.show(el:Element)

  Show gallery. Lazily render if not already.

### Gallery.hide()

  Hide gallery.

## License

MIT
