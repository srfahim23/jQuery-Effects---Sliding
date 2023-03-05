# jQuery-Effects---Sliding
The jQuery slide methods slide elements up and down.

# Example
jQuery slideDown()
Demonstrates the jQuery slideDown() method.

jQuery slideUp() 
Demonstrates the jQuery slideUp() method.

jQuery slideToggle()
Demonstrates the jQuery slideToggle method.

# jQuery Sliding Methods
With jQuery you can create a sliding effect on element.

jQuery has the following slide methods.

.slideDown()
.slideUp()
.slideTogggle()

# jQuery slideDown() Method
The jQuery slideDown() method is used to slide down an element.

Syntax

    $(selector).slideDown(speed,callaback);

The optional speed parameter specifes the duration of the effect. It can take the following values: "slow", "fast", or milisecond.

The optional callback parameter isa function to be executed after slidging competes.

The following example desmonstrate the slideDown() method:

Example

    $("#flip").click(function(){
        $("#panel").slideDown();
    });
    
# jQuery slideUp() Method
The jQuery slideUp() method is used to slide up an element.

Syntax:

    $(selector).slideUp(spee,callaback);

The optional speed parameter specifes the duration of the effect. It can take the following values: "slow", "fast", or miliseconds.

The optional callback parameter is a function to be executed after sliding completes.

The following example demonstrates the slideUp() method:

Example

    $("#flip").click(function(){
        $("#panel").slideUp();
    });

# jQuery slideToggle() Method
The jQuery slideToggle() method toggles between the slideDown() and slideUP methods.

If the elements have been slid down, slideToggle() will slide them up.

If the elements have been slid up, slideToggle() will slide them down.

    $(selector).slideToggle(speed,callaback);

The optional speed parameter can take the following values: "slow", "fast", or miliseconds.

The optional callback parameter is a functiona to be executed the after sliding competes.

The following example demonstrate the slideToggle() method:

Example

    $("#flip").click(function(){
        $("#panel").slideToggle();
    });

    