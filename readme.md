
# FinOps Enablement Deployments

Repository that contains some useful ARM templates that can be deployed to get insight into FinOps and/or optimize costs.

## How to use the templates

The raw templates can be referred to by a deployment URL (often found in a "Deploy to Azure" button)

In order to get the correct URL, go to the raw url of the relevant ARL template. For instance:
```
https://raw.githubusercontent.com/Brandsma/FinOps-Deployments/main/change_aging_data_tiers.json
```

Then, URL encode it at
```
https://www.urlencoder.org/
```

Put the result of that in the following URL:
```
https://portal.azure.com/#create/Microsoft.Template/uri/[url-of-your-ARM-template]
```

This URL can be used to deploy the resource to Azure

## Including the URL in a button

Use the following code to draw the button
```markdown
/* HTML */
<img src="https://aka.ms/deploytoazurebutton"/>
 
/* Markup */
![Deploy to Azure](https://aka.ms/deploytoazurebutton)
```

Then point it to the URL named in the previous section

## Example

Lifecycle Management Policy
<a href="https://raw.githubusercontent.com/Brandsma/FinOps-Deployments/main/change_aging_data_tiers.json">
	<img src="https://aka.ms/deploytoazurebutton"/>
</a>

