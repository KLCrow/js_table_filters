# JSTableFilters

Simple JS script to add drop down filters into the table headers.

# Usage

Just include JSTableFilters.js into your project and add

    $(".table1").jSTableFilters();

or

    $(".table2").jSTableFilters({
        columns: [0,1]
    });

or

    $(".table3").jSTableFilters({
        columns: [1]
    });

to your script ("table1", "table2" and "table3" - tables selectors).