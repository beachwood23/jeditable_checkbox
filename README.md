jeditable_checkbox
==================

Plugin to enable a checkbox for the jQuery Jeditable plugin (http://www.appelsiini.net/projects/jeditable).

Sample use is below:
```
$(document).ready(function() {
     $('.edit_area').editable('http://www.example.com/save.php', { 
         loadurl  : 'http://www.example.com/load.php',
         type    : 'checkbox',
         submit  : 'OK'
         cancel  : 'Cancel'
     });
 });
```
