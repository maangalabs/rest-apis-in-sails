REST Apis in Sails
=======================

In Sails , it is easy to generate a REST API
```
sails generate api user
```
This will generate an API with user model and Controller


HOW TO USE THIS CODE

```

git clone https://github.com/maangalabs/rest-apis-in-sails.git

cd rest-apis-in-sails

sudo npm install

sails lift

```

Go to `http://localhost:1337/employee/create?name=Pranav&empnum=123&email=pranav@maangalabs.com` . 

New User is generated.

Now test the api

```
http://localhost:1337/employee/findEmployeebyEmpnum/123

```

For more check .. 

```
Maangalabs Tutorial : http://maangalabs.com/blog/2014/07/26/generating-rest-api-with-sails-js-part-2
```
