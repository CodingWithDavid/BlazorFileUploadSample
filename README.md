# Blazor File Upload Sample

This project was created to help me learn about uploading files to the server, playing with memory streams and writing to the server folder structure in a Blazor Application.

by [David Gallivan](http://twitter.com/CodingwithDavid)


## Why

This post is my implementation of Steve’s InputFile component.  For a detail description of the inner workings of the component see the link above.  I will be using the Server Configuration for my Blazor Application, but the component will work with any Blazor configuration.  Please note that the implementation to save the uploaded file to the server is for only the Server configuration.  For the Client configuration you would need a Server End point.

With the InputFIle component you can upload any file type.  For the displaying the uploaded file we will be supporting only images and text files.  There are of course components for PDFs and office files. Available but that is beyond what are trying to achieve.

## Getting Started

1. Clone this repository

   ```Command Line
   git clone https://github.com/CodingWithDavid/BlazorFileUploadSample
   cd BlazorDisplayImages
   ```

1.	Open in Visual Studio or Visual Code
a.	With Visual Code you will need to install the C# extensions
2.	Press F5

## What's in the App

Shows how to upload a files to the server.  It also shows some additional things you can do with the files once uploaded. 

## Problems or Suggestions

[Open an issue here](https://github.com/CodingWithDavid/BlazorFileUploadSample/issues)

## Thank You


## Resources
- [Steve Sander's Blog Post on InputFile](https://blog.stevensanderson.com/2019/09/13/blazor-inputfile)
- [VS Code](https://code.visualstudio.com)
- [Visual Studio]( https://visualstudio.microsoft.com/)
- [VS Code Extension Marketplace](https://marketplace.visualstudio.com/vscode)

