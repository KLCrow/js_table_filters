# JSTableFilters

Simple JS script to add drop down filters into the table headers.

# Dependencies:

Require JQuery library.

# Usage

## Table

    <table class="table1" border="1" width="100%" cellpadding="5">
       <tr>
        <th>header1</th>
        <th>header2</th>
       </tr>
       <tr>
        <td>2</td>
        <td>context1</td>
      </tr>
      <tr>
        <td>2</td>
        <td>context2</td>
      </tr>
      <tr>
        <td>3</td>
        <td>context1</td>
      </tr>
      <tr>
        <td>1</td>
        <td>context3</td>
      </tr>
      <tr>
        <td>9</td>
        <td>context5</td>
      </tr>
     </table>

## Usage script

Just include JSTableFilters.js into your project and add

    $(".table1").jSTableFilters();

or

    $(".table1").jSTableFilters({
        columns: [0,1]
    });

or

    $(".table1").jSTableFilters({
        columns: [1]
    });

