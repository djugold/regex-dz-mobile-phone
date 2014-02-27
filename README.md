#Regular Expression for Algerian Mobile Phone Numbers
    
##Mobile number format
     ^(05|06|07)[0-9]{8}$
    
##Javascript Example


    var reg=  /^(05|06|07)[0-9]{8}$/

    reg.test("021481515"); // false
    reg.test("0770123456"); // true
    reg.test("0550123456"); // true
    reg.test("0660123456"); // true
    reg.test("0440123456"); // false
