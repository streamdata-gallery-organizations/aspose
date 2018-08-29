---
swagger: "2.0"
x-collection-name: Aspose
x-complete: 0
info:
  title: Aspose.Storage API Get Storage Folder Folder
  description: The resource represents customer folder at service file storage.
  termsOfService: http://www.aspose.com/corporate/legal/terms-of-use.aspx
  version: v1.1
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---