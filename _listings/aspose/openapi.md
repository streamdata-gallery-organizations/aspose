swagger: "2.0"
x-collection-name: Aspose
x-complete: 1
info:
  title: Aspose
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
host: api.aspose.com
basePath: /v1.1
paths:
  /storage/disc:
    get:
      summary: Get Storage Disc
      description: The resource represents information about users application disc
        usage (size in bytes
      operationId: getStorageDisc
      x-api-path-slug: storagedisc-get
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Disc
  /storage/exist/{path}:
    get:
      summary: Get Storage Exist Path
      description: The controller checks that the file or folder exists in the service
        file storage.
      operationId: getStorageExistPath
      x-api-path-slug: storageexistpath-get
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Exist
      - Path
  /storage/file/{path}:
    delete:
      summary: Delete Storage File Path
      description: The resource represents customers file at server file sto
      operationId: deleteStorageFilePath
      x-api-path-slug: storagefilepath-delete
      responses:
        200:
          description: OK
      tags:
      - Storage
      - File
      - Path
    get:
      summary: Get Storage File Path
      description: The resource represents customers file at server file storage.
      operationId: getStorageFilePath
      x-api-path-slug: storagefilepath-get
      responses:
        200:
          description: OK
      tags:
      - Storage
      - File
      - Path
    post:
      summary: Post Storage File Path
      description: The resource represents customers file at server file storage
      operationId: postStorageFilePath
      x-api-path-slug: storagefilepath-post
      responses:
        200:
          description: OK
      tags:
      - Storage
      - File
      - Path
    put:
      summary: Put Storage File Path
      description: The resource represents customers file at server file storage.
      operationId: putStorageFilePath
      x-api-path-slug: storagefilepath-put
      responses:
        200:
          description: OK
      tags:
      - Storage
      - File
      - Path
  /storage/folder/{folder}:
    delete:
      summary: Delete Storage Folder Folder
      description: The resource represents customer folder at service file storage.
      operationId: deleteStorageFolderFolder
      x-api-path-slug: storagefolderfolder-delete
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Folder
      - Folder
    get:
      summary: Get Storage Folder Folder
      description: The resource represents customer folder at service file storage.
      operationId: getStorageFolderFolder
      x-api-path-slug: storagefolderfolder-get
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Folder
      - Folder
    post:
      summary: Post Storage Folder Folder
      description: The resource represents customer folder at service file storage.
      operationId: postStorageFolderFolder
      x-api-path-slug: storagefolderfolder-post
      parameters:
      - in: query
        name: dest
        description: Moves (renames) the file to NewFile
      responses:
        200:
          description: OK
      tags:
      - Storage
      - Folder
      - Folder