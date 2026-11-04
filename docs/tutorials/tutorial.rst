Tutorial
========


Starting - Opening files
------------------------

File -> Open... -> Select File -> Open

.. image:: file_load.gif
   :alt: Opening a genbank file using file menu and selecting file type.
   :width: 840px
   :align: left

General Tab
-----------

Edit title or bp size then hit Apply to update figure.

Title font size modifies the combined title and BP size labels.
Label font size modifies the size of the feature labels

Ticks can be shown or removed, so can the base pairs on feature labels.

Two preset styles are provided:

Default - includes everything and uses a wide plasmid circle
Minimal - removes ticks and base pair labels, sets plasmid circle to a thinner black line

.. image:: general_tab.gif
   :alt: Demonstrate modifying title and plasmid size, changing font sizes for titles and labels, removing ticks and bp labels and changing the plasmid ring style to minimalist
   :width: 840px
   :align: left

Table Tab
---------
Features can be added to the Table tab, even from a blank table.

Feature properties can be edited, plasmid will update when the "Apply to Plasmid" button is pushed.

Colour can be selected or set by name or hex code

Direction can be set (1 forward/clockwise, -1 backward/anticlockwise, 0 rectangular feature)

Toggle which features are showing.

.. image:: table_tab_1.gif
   :alt: Demonstrates adding and modifying a feature to a blank plasmid
   :width: 840px
   :align: left

Features can be deleted using the cross at the end of the row and new features can be added using "Add row". Both take effect after selecting apply.

.. image:: table_tab_2.gif
   :alt: Demonstrates deleting 2 features from a plasmid and replacing one with a new feature.
   :width: 840px
   :align: left

Features Tab
------------

Feature tab can be used to select which types  of feature are shown, this toggles their show value in the table.

.. image:: show_toggles.gif
   :alt: Demonstrates use of the features tab to select and deselect types of features to show in the plasmid and the use of the individual show toggles
   :width: 840px
   :align: left


This is useful for working with genbank files which often have a large number of features. Types can be edited in the Table tab.

Saving Table
------------

The table of features (and title and size) can be saved as a csv file for reuse with "Save Data"

.. image:: save_csv.gif
   :alt: Demonstrates save table as a csv (tsv is also an option)
   :width: 840px
   :align: left

Saving Plasmid
--------------

The plasmid figure can be saved through the file menu: File -> Save...

.. image:: save_figure.gif
   :alt: Demonstrates save the figure using the file menu.
   :width: 840px
   :align: left

The file can be saved as png, svg, pdf or jpeg. It saves with a tight box around the current displayed plasmid.

