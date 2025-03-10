Other Functions
===============

* area4.splitter

The splitter function takes a string or number as a divider, and a series of strings to return, divided.
If the first parameter is a number, it looks it up in the divider list.
Otherwise, it uses the string provided as a divider.
If only one additional string is provided, nothing is returned.

* area4.utils.get_divider_character

Gets you the material the divider is made of. You pass an integer of the divider you want to get
the character it is made of.
Example:

.. code-block:: python

    from area4.util import get_divider_character
    print(
        get_divider_character(7)
    )
    # This example prints a single equal sign to the console
    # because that divider is '============'

* area4.utils.reddit_horizontal

This function returns the Reddit markdown divider (for Reddit bots).
This function takes no parameters.

* area4.utils.markdown_horizontal

This function returns the Markdown divider (rendered as HTML 'hr' tag by sites like GitHub).
This function takes no parameters.
