# strong-password-checker
Provides a api that checks wether the password is strong.

create a input variable named 
```bash
     var password = document.getElementId('password'); // connect your password input
 ```
Add this function in your script 
```bash
funnction check_password (password ) {
    var string = password.length
    var correct_way = 'WER1@#?/ser';
    if(string > 8){
    alert('characthers should be above 8');
}
else if (string < 15){
    alert('characthers should be below 15');
}
else if (password = ''){
    alert('this field should be filled');
}
else if (password.match(correct_way)){
    true;
}
else {
    alert('a weak password');
}
}
```
