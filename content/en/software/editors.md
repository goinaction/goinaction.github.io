+++
title = "IDEs and Editors"
weight = 1
lastEdit = true
description = "Tools to write Go code"
+++

In order to write source code, you need something to type it into. You can of course use any text editor for this, but we highly recommend an Integrated Development Environment, or at least a pluggable text editor designed with writing code in mind.

## IDEs

An Integrated Development Environment ("IDE") is a program that provides a comprehensive environment for writing code. The line between IDE and Code editor can sometimes get a little blurry, but generally IDEs provide a richer, more dedicated experience with features such as integrated, graphical debugging, test annotations, and integrated terminals.

### Visual Studio Code
{{< image-gallery gallery_dir="/gallery/vscode" >}}
* [Homepage](https://code.visualstudio.com/)
* [Download the Go Extension](https://marketplace.visualstudio.com/items?itemName=golang.go)
Visual Studio Code (VSCode) is a powerful free cross-platform IDE based on Electron. It has excellent Go support, thanks to a Go extension maintained by the Go team at Google. It is our primary recommendation since it is both feature-rich and free.

#### Setup
*guided video coming soon*

1. Install VSCode from thw download link above.
2. Download and install the Go extension.
3. *(optional)* Create a folder such as {{<uinput "home/workspaces" >}} or {{<uinput "Documents/code" >}} to serve as a home base for all of your code projects, which are called "Workspaces" in VSCode parlance. This can be helpful in keeping everything together, but you can also create workspaces wherever you like.
4. Open VSCode and, navigate to <kbd>File &rArr; Add Folder To Workspace...</kbd>.
5. Navigate to wherever you'd like to store your first workspace directory, but *don't click the Add button yet*. If you added a special folder in step #3, this is where you'd start.
6. Once you've selected a location for the new Workspace, click <kbd>New Folder</kbd> and create a folder called {{<uinput "goinaction" >}}.
7. Click <kbd>Add</kbd> button to add the folder to your new, unnamed workspace.
8. Click <kbd>File &rArr; Save Workspace As...</kbd> and accept the default name, which should be something like <kbd>goinaction.code-workspace</kbd>
9. Open the "command palette", which is VSCode's general-purpose autocompleting shortcut menu with <kbd>&#8984;</kbd>-<kbd>shift</kbd>-<kbd>p</kbd> or <kbd>![Example image](/images/windows_key.svg)</kbd>-<kbd>shift</kbd>-<kbd>p</kbd>
10. Type {{<uinput "go mod" >}}, which will select the <kbd>Go: Initialize go mod</kbd> option and hit <kbd>Enter</kbd>
11. Enter {{<uinput "goinaction" >}} when prompted.
12. Finally, save the new go.mod file.

Now you are in a fresh new Workspace and ready to follow along with the book. You can create a new folder for each exercise from the file explorer menu to the left and add *main.go* files for each one.

### Goland
*TBD*

## Code Editors

### Sublime Text
*TBD*
