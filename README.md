# Array Cardio II

```
     const mortals = [
     
      { first: 'Maria', last: 'Skłodowska', year: 1867, passed: 1934 },
      { first: 'Johannes', last: 'Kepler', year: 1571, passed: 1630 },
      { first: 'Nicolaus', last: 'Copernicus', year: 1473, passed: 1543 },
      { first: 'Albert', last: 'Einstein', year: 1879, passed: 1955 },
      { first: 'Isaac', last: 'Newton', year: 1643, passed: 1727 },
      { first: 'Galileo', last: 'Galilei', year: 1564, passed: 1642 },
      { first: 'Max', last: 'Planck', year: 1858, passed: 1947 },
      { first: 'Katherine', last: 'Blodgett', year: 1898, passed: 1979 },
      { first: 'Ada', last: 'Lovelace', year: 1815, passed: 1852 },
      { first: 'Sarah E.', last: 'Goode', year: 1855, passed: 1905 },
      { first: 'Lise', last: 'Meitner', year: 1878, passed: 1968 },
      { first: 'Hanna', last: 'Hammarström', year: 1829, passed: 1909 }
    ];

            
         // Array.prototype.push()
            
            
            const addNew = mortals.push({first: 'Jan', last: 'Czochralski ', year:1885, passed: 1953 });
            console.table(mortals);
            
        // Array.prototype.slice()
            
            const remove = mortals.slice(4, 6);
            console.table(remove);
            
        //Array.prototype.unshift()
            
            const newToFirst = mortals.unshift({first: 'Stefan', last: 'Banach', year:1892, passed: 1945 });
            console.table(mortals);

```
## Example

[demo](http://www.konstantyw.pl/array_cardio_2)
