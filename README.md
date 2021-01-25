# gcp_utils
This file allows to install and then configure a linux machine to directly copy files to gcp


The files here are to reproduce the experiment in a vm. But the main files are in upload_to_gcp folder.

## How to to use the files ?

1. First install gcloud using: `./install_gcloud.sh`
2. Once it is installed, you can upload files with:

 ```bash
upload_files.sh <Service account JSON File> <Folder to upload> <bucket>
 ```

Where:

* <Service account JSON File> is the file for the service account having the create object role on GCP
* <Folder to upload> is the folder to upload to GCP
* <bucket> is the destination bucket

