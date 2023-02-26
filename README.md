# Symfony6 project Hands-ON

https://symfony.com/

Installing & Setting up the Symfony Framework

### Check composer requirements
`symfony check:requirements`

### Create project:
`symfony new sf-hands-on version="6.1.*"
`
### Start project:
```symfony server:start```

### check security:
```symfony check:security```

### Check routes on console with debugger
`symfony console debug:router`

---------------- -------- -------- ------ -------------------------- 
Name             Method   Scheme   Host   Path
 ---------------- -------- -------- ------ -------------------------- 
_preview_error   ANY      ANY      ANY    /_error/{code}.{_format}  
app_index        ANY      ANY      ANY    /                         
app_show_one     ANY      ANY      ANY    /messages/{id}
 ---------------- -------- -------- ------ -------------------------- 

### Install twig templates
`composer require twig`