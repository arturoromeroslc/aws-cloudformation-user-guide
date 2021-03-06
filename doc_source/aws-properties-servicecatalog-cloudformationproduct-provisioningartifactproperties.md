# AWS::ServiceCatalog::CloudFormationProduct ProvisioningArtifactProperties<a name="aws-properties-servicecatalog-cloudformationproduct-provisioningartifactproperties"></a>

Information about a provisioning artifact \(also known as a version\) for a product\.

## Syntax<a name="aws-properties-servicecatalog-cloudformationproduct-provisioningartifactproperties-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-servicecatalog-cloudformationproduct-provisioningartifactproperties-syntax.json"></a>

```
{
  "[Description](#cfn-servicecatalog-cloudformationproduct-provisioningartifactproperties-description)" : String,
  "[Info](#cfn-servicecatalog-cloudformationproduct-provisioningartifactproperties-info)" : Json,
  "[Name](#cfn-servicecatalog-cloudformationproduct-provisioningartifactproperties-name)" : String
}
```

### YAML<a name="aws-properties-servicecatalog-cloudformationproduct-provisioningartifactproperties-syntax.yaml"></a>

```
﻿  [Description](#cfn-servicecatalog-cloudformationproduct-provisioningartifactproperties-description) : String
﻿  [Info](#cfn-servicecatalog-cloudformationproduct-provisioningartifactproperties-info) : Json
﻿  [Name](#cfn-servicecatalog-cloudformationproduct-provisioningartifactproperties-name) : String
```

## Properties<a name="aws-properties-servicecatalog-cloudformationproduct-provisioningartifactproperties-properties"></a>

`Description`  <a name="cfn-servicecatalog-cloudformationproduct-provisioningartifactproperties-description"></a>
The description of the provisioning artifact, including how it differs from the previous provisioning artifact\.  
*Required*: No  
*Type*: String  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`Info`  <a name="cfn-servicecatalog-cloudformationproduct-provisioningartifactproperties-info"></a>
The URL of the CloudFormation template in Amazon S3\. Specify the URL in JSON format as follows:  
 `"LoadTemplateFromURL": "https://s3.amazonaws.com/cf-templates-ozkq9d3hgiq2-us-east-1/..."`   
*Required*: Yes  
*Type*: Json  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`Name`  <a name="cfn-servicecatalog-cloudformationproduct-provisioningartifactproperties-name"></a>
The name of the provisioning artifact \(for example, v1 v2beta\)\. No spaces are allowed\.  
*Required*: No  
*Type*: String  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

## See Also<a name="aws-properties-servicecatalog-cloudformationproduct-provisioningartifactproperties--seealso"></a>
+ [ProvisioningArtifactProperties](https://docs.aws.amazon.com/servicecatalog/latest/dg/API_ProvisioningArtifactProperties.html) in the *AWS Service Catalog API Reference*