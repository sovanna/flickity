## To do

Move TapListener class to its own repo
update utils with handleEvent

## Feature requests

isGroupPaging
lazy load
animations for add/remove
disable animation on imagesLoaded loading

## Test

cellAlign
wrapAround
imagesLoaded

## Check

videos

## Blog about

handling clicks vs. dragging
HTML init
lots of files

## IE8 quirks

scrollTop & scrollLeft
can't set `button.type = 'button'` has to be `button.setAttribute( 'type', 'button' )`
cannot `.focus()` on a button that is `disabled`

    function preventDefaultEvent( event ) {
      if ( event.preventDefault ) {
        event.preventDefault();
      } else {
        event.returnValue = false;
      }
    }

