# clickQuery
## jQuery's click in 342 characters

Because why not?

Be warned, this is highly golfed and isn't nearly as robust as jQuery.click

## Get array of objects

    $(selector)

**Example**

    $('p')
    // Returns [<a>,<a>,...]

## Attach click handler

    $('p').click(function() {
      console.log('you clicked!');
    });
