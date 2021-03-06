# New-PCCustomerCompanyProfile

Returns a PowerShell object that includes the properties for the customer's company properties. The object is passed to the New-PCCustomer cmdlet to create a new customer.

## SYNTAX

```powershell
New-PCCustomerCompanyProfile [-Domain] <String> [<CommonParameters>]
```

## DESCRIPTION

The New-PCCustomerCompanyProfile cmdlet returns a PowerShell object that includes the properties for the customer's company properties.

## PARAMETERS

### -Domain &lt;String&gt;

Specifies the domain for the company profile

```
Required?                    true
Position?                    1
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

## INPUTS

## OUTPUTS

## NOTES

## EXAMPLES

### EXAMPLE 1

Create a new customer profile with the contoso.onmicrosoft.com domain and assign it to $ccp variable.

```powershell
PS C:\>$ccp = New-PCCustomerCompanyProfile -Domain 'contoso.onmicrosoft.com'
```
