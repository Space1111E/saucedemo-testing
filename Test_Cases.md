"## Test Cases\n\n- Test case 1: Successful Login\n- Test case 2: Failed Login"

# Test Cases për SauceDemo Functional Testing

| ID Testi | Emri i Testit                  | Hapat e Testimit                                                                                         | Rezultati i Parashikuar                                   | Rezultati Aktual | Statusi   |
| -------- | ------------------------------ | -------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- | ---------------- | --------- |
| TC01     | Login me kredenciale valide    | 1. Hyr ne faqen e login<br>2. Fut username/password valide<br>3. Kliko Login                             | Predoruesi hyn ne faqen kryesore                          |                  | Pass/Fail |
| TC02     | Login me kredenciale jo valide | 1. Hyr ne faqen e login<br>2. Fut username/password jo valide<br>3. Kliko Login                          | Shfaqet mesazh gabimi “Username or password is incorrect” |                  | Pass/Fail |
| TC03     | Shto produkt ne karroce        | 1. Login<br>2. Zgjidh produktin<br>3. Kliko “Add to cart”                                                | Produkti shfaqet ne karroce                               |                  | Pass/Fail |
| TC04     | Kryej checkout pa gabime       | 1. Shto produkt ne karroce<br>2. Shko ne Checkout<br>3. Fut te dhenat e nevojshme<br>4. Perfundo blerjen | Blerja perfundon me sukses                                |                  | Pass/Fail |
