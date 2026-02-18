# trilium-todo-plugin
An improved version of the trilium default task manager originally built by [Nicollas R.](https://github.com/nicollasricas) and updated to work on newer versions of Trilium.  

---
I updated [Nicollas R.](https://github.com/nicollasricas) code in version 1.1 of this plugin so that it works for me. I'm not promising anything for others who try my version, but I'm willing to help if I can.
This version fixes the popup menu showing to select tags for your tasks.

# Installation

*    (Suggestion) Create a note called Trilium and inside another called Plugins.
*    Install this plugin by right-clicking in the Plugins note, import into note, select the file to import, uncheck “Safe Import” and make sure “Read contents of .zip...” is checked.
*    Install [Collection Views](https://github.com/mabeyj/trilium-collection-views) plugin (not required, but you are gonna miss a lot).
     *   Add #collectionViews label to Collection Views root note.
*   Restart Trilium

*If you have any security/privacy concerns about this plugin, just open Trillium in safe-mode (blocks script execution) and look at what the code of this plugin does.*  

* Getting Started
Create a note anywhere, add the #initTodo label, reload the front-end or restart Trilium.
*    The note with the label will be the root of your to-do list.
*    You can create multiple lists at the same time
*    Completed tasks will be archived automatically after 7 days.
*    The time spent tracking works based on minutes. If you work on a task for less than that, it won't track anything.
