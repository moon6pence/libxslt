# libxslt build for iOS projects

- Build libxslt 1.1.26 for iOS project.
- Original source from: <http://xmlsoft.org/xslt>
- I don't have plan to update last version of xslt yet, because it works well for my private project and it's enough. 

## Example

- Refer example code at this link, in first answer: <http://stackoverflow.com/questions/462440/version-of-xslt-in-iphone>

## Instruction

- Put **libxslt.xcodeproj** file to your project, and setup header and library like other libraries, and it will work. 
- You can test example code in link upper with **libxslt.dylib**, but it will not pass Apple's app review process, you have to include your own libxslt compile. 
- There were bug in Apple's app review bot that reject binary due to  functions symbols in libxslt even though own libxslt compile, but it is fixed. 