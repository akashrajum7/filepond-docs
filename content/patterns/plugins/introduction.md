+++
title = "Introduction"
weight = 1
+++

FilePond's functionality can be extended with plugins.

Each plugin is located in its own GitHub repository and follows a specific naming convention.

```html
filepond-plugin-<name-of-plugin>
```

Plugins can be registered with FilePond using the `registerPlugin` method. Read more about [registering plugins here](../../api/filepond-object/#registering-plugins).


## Available plugins

| Plugin                                              | Name                                   | Description                                                                                    |
| --------------------------------------------------- | -------------------------------------- | ---------------------------------------------------------------------------------------------- |
| [File Rename](../file-rename)                       | filepond-plugin-file-rename            | Rename files on the client                                                                     |
| [File Encode](../file-encode)                       | filepond-plugin-file-encode            | Encodes files as base64 data for submitting along a classic form post                          |
| [File Size Validation](../file-validate-size)       | filepond-plugin-file-validate-size     | Limit the size of files being added                                                            |
| [File Type Validation](../file-validate-type)       | filepond-plugin-file-validate-type     | Limit the types of files being added                                                           |
| [File Metadata](../file-metadata)                   | filepond-plugin-file-metadata          | Automatically set file initial metadata object                                                 |                                              
| [File Poster](../file-poster)                       | filepond-plugin-file-poster            | Show a poster image inside the file item                                                       |                                        
| [Image Preview](../image-preview)                   | filepond-plugin-image-preview          | Shows a preview of image files                                                                 |
| [Image Edit](../image-edit)                         | filepond-plugin-image-edit             | Adds manual editing to image files                                                             |
| [Image Crop](../image-crop)                         | filepond-plugin-image-crop             | Set crop ratio for image fiels                                                                 |
| [Image Resize](../image-resize)                     | filepond-plugin-image-resize           | Set output dimensions for image files                                                          |
| [Image Transform](../image-transform)               | filepond-plugin-image-transform        | Apply image transforms on the client before uploading                                          |
| [Image EXIF Orientation](../image-exif-orientation) | filepond-plugin-image-exif-orientation | Extracts EXIF orientation information so to fix orientation of pictures taken on mobile phones |
| [Image Size Validation](../image-validate-size)     | filepond-plugin-image-validate-size    | Limit the dimensions of the images being added |
| [Image Filter](../image-filter)     | filepond-plugin-image-filter    | Apply a color matrix to image pixels  |