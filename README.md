# Wzzymy-cms-

Scope of influence

V6.1

Repair scheme

Filter field, special characters are not allowed

Environment construction method

(1) : download from the official website and unzip it to the WWW directory, phpstudy, but the PHP version should be 5.6

The vulnerability is caused by:

Due to transfer to $isapp = $this - >_ post('is_app'); Special characters are not filtered

Vulnerability recurrence method

Click debug mode

![image](https://user-images.githubusercontent.com/27337983/139573999-f2d32529-845c-44c8-a7be-add0dee72579.png)

Changing the parameter to phpinfo () will transfer it to the foreground debug code

![image](https://user-images.githubusercontent.com/27337983/139574005-1ab30827-f358-44df-ac84-18b376aaad41.png)


Visit the front desk page

![image](https://user-images.githubusercontent.com/27337983/139574027-dbb01efc-8df5-4598-858d-df9391dd7ac1.png)


