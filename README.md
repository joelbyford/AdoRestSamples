# AdoRestSamples

To easily use these samples, please download [VSCode](https://code.visualstudio.com/Download) and install the [RESTClient](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) plugin.

Please note that the ADO REST operations currently do NOT use OAuth andn instead use HTTP BasicAuth with any value in the user ID and a [Personal Access Token (PAT)](https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate?view=azure-devops&tabs=Windows) for the password as in the following format:

`Authorization: Basic anyUserName:SomeGeneratedPat`.

For a complete list of REST operations, please refer to the [Microsoft Documentation Site](https://docs.microsoft.com/en-us/rest/api/azure/devops/?view=azure-devops-rest-7.1&viewFallbackFrom=azure-devops-rest-6.0)
