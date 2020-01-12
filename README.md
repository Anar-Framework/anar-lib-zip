### Zip and UnZip Utility Library

Utilities for **Zip** and **UnZip** operations. Provide Zip utility for usage across the application to Zip and unZip Files and Directory Size of the files and Folders according to business needs This ZipUtil will not applicable for RAR or 7Z etc.

- zipByteArray: Method used for zipping a Byte Array
- unzipByteArray: Method used for unzipping a zipped Byte Array
- readFile : This is inner method to read a file
- zipFolderInDir: Inner method of zipDirectory Method, called for zip all files of the given Directory
- createOutputFile: This is inner method for unZipFile method used for created output folder
- unZipDirectory: Extracts a zip file specified by the zipFilePath to a directory specified by destDirectory (will be created if does not exists)
- extractFile: This is inner method for Extracts a zip entry (file entry)
