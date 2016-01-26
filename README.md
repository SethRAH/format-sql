# format-sql
small JavaScript module to format SQL queries with more readable line breaks etc. Will be configurable to allow the module's user to add their own keywords

## Installation

  npm install format-sql --save

## Usage

  var sql = 'SELECT employeeId, givenName, familialName FROM dbo.Employee WHERE familialName LIKE '%son%' ORDER BY familialName asc, givenName asc',
      formatted = formatSql.formatQuery(sql);
     
  console.log('sql', sql, 'formatted', formatted);

## Tests

  To-Do: add some tests!
  
## Contributing

  Currently don't have a style guide or a roadmap
  
## Release History

* 0.1.0 Initial Release