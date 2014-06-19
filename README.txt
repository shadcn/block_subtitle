
-- SUMMARY --

This module allows subtitle to be set to blocks.


-- REQUIREMENTS --

None.


-- INSTALLATION --

* Enable the Block Subtitle module under Administer >> Site Building >> Modules
* Once enable you need to edit block.tpl.php in your theme. Add the following code to show the block subtitle

<?php if ($block->subtitle): ?>
    <h3 class="subtitle"><?php print $block->subtitle; ?></h3>
<?php endif; ?>

* Create the block.tpl.php in your theme if it does not exist.


