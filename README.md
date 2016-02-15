Configured-CKEditor
===

### 1. Config Upload URL
file: /ckeditor/config.js

    config.toolbarGroups = [
        ......
	    config.filebrowserUploadUrl = '/ckupload/';
	    config.filebrowserImageUploadUrl = '/ckupload/';
        ......
    ]

### 2. Show Upload Button
file: /ckeditor/plugins/image/dialogs/image.js

                                ....
    {id:"Upload", hidden:!0 ==> ....{id:"Upload", hidden:0, ...
                                ....

