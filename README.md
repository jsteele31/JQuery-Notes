JQuery-Notes
============

$('div').html() <-- Returns the content of the first div.
$('div').html("content"); would change the first div to that content.

.val() <-- returns the value of the object
$('input:checkbox:checked').val();

.click()
.hover()
.dblclick()
.focus() <-- clicked or tabbed
.keydown()

.animate()
top, left, right
ex. $('div').animate({left:'+=10px'},500);


.fadeIn('slow');
.fadeOut('fast');

.fadeTo('slow', 1);

.mouseenter()
.mouseleave()

.addClass()
.removeClass()

.remove()
.empty()

.css('border-radius', '10');
.height('200px');
.width('200px');

$(document).ready( function() { });

var input = $('input[name=fieldName]').val(); <-- getting info from a textbox input. 
AKA: var input = $('input[name=checkListItem]').val();  <input type="text" name="checkListItem" /> GET IT?


$(document).on('event', 'selector', function() {
    Do something!
});

EX:
$(document).on('click', '.item', function() {
        $(this).remove();
});

