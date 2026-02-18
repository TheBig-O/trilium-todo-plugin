# trilium-todo-plugin
An improved version of the trilium default task manager originally built by [Nicollas R.](https://github.com/nicollasricas) and updated to work on newer versions of Trilium.  

---
I updated [Nicollas R.](https://github.com/nicollasricas) code in version 1.1 of this plugin so that it works for me. I'm not promising anything for others who try my version, but I'm willing to help if I can.
This version fixes the popup menu showing to select tags for your tasks.

    Dropdown button didn’t have a working click handler for the menu.  
```
// --- Dropdown toggle ---
this.$widget.find('.dropdown.note-actions button').click(function (e) {
  e.stopPropagation();
  $(this).next('.dropdown-menu').toggleClass('show');
});

// Close dropdown when clicking outside
$(document).click(() => {
  $('.dropdown-menu').removeClass('show');
});
```
There are other minor fixes in the code, but the menu was the key concern.
I increased the version number to ensure people know they've got a revised version
