# Change Log

## 1.2.0 (August 05, 2025)

 Feature: Add WrapBase64 and previewName option.

## 1.1.9 (June 24, 2021)

- Fix: update README.md
- Fix: varibale 'fileBasename' and 'fileBasenameNoExtension' misrouted to real file's directory, not exactly the file

## 1.1.8 (September 01, 2020)

- Feature: Support convert base64 text of clipboard to image data. it's only png image.

## 1.1.7 (August 29, 2020)

- Feature: Add `Paste base64 image of clipboard` to editor context menu.
- Fix: The command to be executed was incorrect. `Paste image of clipboard` to editor context menu.
- Fix: displayName `Paste Image to local pc` -> `Paste Image from local pc`

## 1.1.5 (August 26, 2020)

- Fix: Support vscode version 1.48.0 upper -> 1.40.0 upper
- Fix: linux sciprt and mac script

## 1.1.0 (August 25, 2020)

- Feature: Support Remote Development
- Feature: Add `Paste image of clipboard` to editor context menu.
- Feature: Add `Create image of clipboard` to explorer context menu.
- Feature: Remove `basePath` configuration.
- Feature: Remove `forceUnixStyleSeparator` configuration.
- Feature: Remove `prefix` configuration.
- Feature: Remove `suffix` configuration.
- Feature: Remove `namePrefix` configuration.
- Feature: Remove `nameSuffix` configuration.
- Feature: Remove `encodePath` configuration.
- Feature: Remove `insertPattern` configuration.
- Feature: Remove `filePathConfirmInputBoxMode` configuration.

## 1.0.4 (January 23, 2018)

- Fix: paste image get blank image issue (windows)

## 1.0.3 (November 28, 2018)

- Fix: paste translucent image get background issue (windows)
- Feature: Add `pasteImage.showFilePathConfirmInputBox` & `pasteImage.filePathConfirmInputBoxMode` configuration. Support show file path confirm inputbox before saving.

## 1.0.2 (June 6, 2018)

- Fix: `pasteImage.namePrefix` and `pasteImage.nameSuffix` not work when there is no text selected.

## 1.0.1 (May 31, 2018)

- Update readme

## 1.0.0 (May 31, 2018)

- Feature: Add `pasteImage.insertPattren` configuration. Support config the format of text would be pasted.
- Feature: Add `pasteImage.defaultName` configuration. Support config default image file name.
- Feature: Add `pasteImage.encodePath` configuration. Support url encode image file path.
- Feature: Add `pasteImage.namePrefix` configuration.
- Feature: Add `pasteImage.nameSuffix` configuration.

## 0.9.5 (December 16, 2017)

- Fix: Support select non-ascii text as file name

## 0.9.4 (July 7, 2017)

- Feature: Print log to "PasteImage" channel, and show in output panel.
- Fix: Paste fail when powershell not in PATH on windows. (from @ELBe7ery)

## 0.9.3 (July 5, 2017)

- Feature: Support select text as a sub path with multi new directory like `a/b/c/d/imageName` or `../a/b/c/d/imageName`
- Fix: Error when dest directory is not existed. (from @WindnBike)

## 0.9.2 (July 3, 2017)

- Improvement: Check if the dest directory is a file.

## 0.9.1 (July 3, 2017)

- Feature: `pasteImage.path` and `pasteImage.basePath` support `${currentFileName}` and `${currentFileNameWithoutExt}` variable.

## 0.9.0 (July 3, 2017)

- Feature: Add `pasteImage.basePath` configuration.
- Feature: `pasteImage.path` and `pasteImage.basePath` support `${currentFileDir}` and `${projectRoot}` variable.
- Feature: Add `pasteImage.forceUnixStyleSeparator` configuration.
- Feature: Add `pasteImage.prefix` configuration.
- Feature: Add `pasteImage.suffix` configuration.
- Feature: Support selected path as a sub path.

## 0.4.0 (July 3, 2017)

- Feature: Support AsciiDoc image markup

## 0.3.0 (December 31, 2016)

- Feature: Support config the path(absolute or relative) to save image.(@ysknkd in #4)

## 0.2.0 (November 13, 2016)

- Feature: Add linux support by xclip
- Feature: Support use the selected text as the image name

## 0.1.0 (November 12, 2016)

- Feature: Add windows support by powershell(@kivle in #2)

## 0.0.1

- Finish first publish. Only support macos.