# New-RandomPassword.ps1
Simple function to specified number of strong random passwords.

## Parameters

- -passwordLength
Length of password(s)
- -specialcharacters
Number of special characters 
- -numberofpasswords
Number of passwords


## Examples
```
.\New-RandomPassword.ps1 20 8 10
```

## Credits
japocock (https://github.com/japocock/)
Change Log V1.00, 13/03/2015 - Initial version

See: https://docs.microsoft.com/en-us/dotnet/api/system.web.security.membership.generatepassword?view=netframework-4.7.2

Change Log
V1.00, 13/03/2015 - Initial version
