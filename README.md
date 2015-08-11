Wrapper around the javascript VAT validator from John Gardner (http://www.braemoor.co.uk/software/vat.shtml)

### function checkVATNumber(vatNumber)
Parameters:
  - VATNumber: VAT number to be checked.

Returns:
  - reformatted VAT number if valid
  - false if invalid


 Usage (using RequireJS):
  ```javascript

    var vatValidator = require('bower/js-vat-validator/lib/validator');

    checkedVatNumber = checkVATNumber(vatNumber);

    if (vatNumber) {
        alert("reformatted valid VAT number: " + checkedVatNumber)
    } else {
        alert ("Invalid VAT number: " + vatNumber);
    }

  ```
