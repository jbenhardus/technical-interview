# XILO Technical Assessment

Thank you for your interest in XILO! In order to get a sense of your technical abilities, we would like you to complete this technical assessment. Please read the overview and guidelines, then choose a use case to implement.

## Guidelines

### Allowed Resources

Our goal in this assessment is to evaluate your technical abilities in as close to a "real world" context as possible. This means you are free to use Google, Stack Overflow, or any other resources you would like. The only restriction is that all work must be your own - please do not copy-paste substantial amounts of your solution or ask other individuals for help. We are not looking for a perfect solution, but an accurate representation of your abilities. To that end, we will expect you to be able to explain both how your solution works and why you may have chosen a particular approach. If you have questions or get stuck, we ask that you reach out to us for clarification or help - we will be happy to assist you.

### Time Expectations

Our expectation is that this assessment will take around an hour to complete. You may spend more time if you like, but you shouldn't spend much more than 2 hours at most on your assessment. Each use case has a main objective and optional objectives. If you complete the main objective within your allotted time you may choose to implement any of the optional objectives that you like.

## Overview

You will be adding functionality to an online storage application, similar to Google Drive or Dropbox. Users of this application can upload files to be stored and organize their files in folders. Unfortunately, the upload feature for this application is still fairly buggy, so files and folders often get corrupted.

## Use Cases

Choose one of the following use cases to implement:

### Frontend - display directories

You will be implementing a feature that allows a user to view their files and folders in a web browser. Add functionality to the `ViewFilesComponent` to display the filesystem for a user.

#### Main Objective

- Load test data from the api using `AppService`
- Display the files and folders for a user
  - Folders should display the name of the folder
  - Files should display the name of the file and the extension
  - Users should be able to see all files and folders at the root level, as well as any files and folders in subdirectories
  - Users should be able to see the structure of their filesystem and easily tell how many levels deep in the filesystem a particular file or folder is

#### Optional Objectives

- Add the ability to expand or collapse folders in the filesystem
- Add icons for folders and each file type (.txt, .pdf, and .png)
- Add the ability to search/filter the fileroom based on keywords
