960.gs TextMate Bundle
======================

This bundle eases the authoring of HTML while using the [960.gs](http://960.gs) CSS framework. It introduces tab-triggered snippets for the following constructs:

*   `container_12`, `container_16` divs are created with the `c12` and `c16` tab triggers, respectively.
*   `grid` divs can be created in one of two ways: using the `grid` tab trigger will provide you with a grid div with the grid width selected, or you can use any one of the `gridX` triggers, i.e. `grid4`, `grid12`, `grid16`.
*   A clearfix div is inserted using the `clear` tab trigger.


But what about `prefix`, `suffix`, `alpha`, and `omega`?
--------------------------------------------------------

Since these are arbitrarily added to the `grid` classes according to the content you're authoring, it didn't make sense to have tab triggers for these. Instead, I've situated the caret such that you are in the right place to just typethese immediately after triggering the snippet:

    <div class="grid_5[CARET IS HERE]">
        [TAB ONCE, AND CARET GOES HERE]
    </div>


I have an idea how to improve this...
-------------------------------------

Patches/github forks welcome. This bundle is released under the terms of the new BSD license, see `LICENSE.txt`.


CSS frameworks are for tools. Don't encourage their use!
--------------------------------------------------------

I disagree. `> /dev/null`


Who are you?
------------

Idan Gazit / idan AT pixane DOT com / @idangazit


