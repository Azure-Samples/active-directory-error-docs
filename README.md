# Azure AD Error Docs
This repo is intended to document the AADSTS error codes returned from the Azure AD STS.  We welcome all contributions and fixes from the community to improve error descriptions, fixes, and workarounds.  Moreover, if something seems incorrect or you would like to request a new error code, please feel free to open a Github issue. 

# Contributing
All contributions to the Azure AD error docs are welcome. The following describes the structure of each error:

### Where to put new error
Each error is represented as a `*.md` file inside the [/errors](https://github.com/Azure-Samples/active-directory-error-docs/tree/master/errors) directory. 

### Title
Each file begins with a header of the error description as appears in the response from Azure AD.  For example,

    ### access_denied

### Brief Description
After the title, give a brief description of what this error means or a canonical scenario that can trigger it.  This can also be the generated error description from Azure AD.

### Possible Causes
The next section should enumerate all possible cases the error can be occur.  For example, 

    **Possible Causes**
        * User did A
        * Developer did B
        * Tenant admin did C

### What to do
The final section is **What to do** which gives clear actionable advice on how to resolve the error. This can be keyed off the Possible Causes or a simple description. For example,

    **What to do**
        Perform admin consent on the application to resolve this error. You can do admin consent either through the portal doing xyz, or by constructing a request to the endpoint (give explicit instructions on how to construct this). 


This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
