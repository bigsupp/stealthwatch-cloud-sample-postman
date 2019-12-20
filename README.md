# Stealthwatch Cloud API Postman Samples
This repository contains sample Postman collections related to Cisco Stealthwatch Cloud APIs. It is available for use by the Cisco DevNet community through Code Exchange.
For more information on the Stealthwatch Cloud REST API, please see the following link: https://developer.cisco.com/docs/stealthwatch-cloud

## Installation
1. Ensure Postman is installed.
   * To download and install Postman, please visit https://www.getpostman.com.
2. Download the Postman collection and environment files.
3. After launching Postman, click the `import` button and import the previously downloaded Postman files.
4. Under the Settings/Preferences menu for Postman, ensure that "SSL certificate verification" is turned off. 

## Configuration
1. Ensure the Postman collections and environment have been imported.
2. Select the `Stealthwatch Cloud (DevNet)` environment from the dropdown in the top-right corner of Postman.
3. To the right of this dropdown (in the top-right corner of Postman), click the graphic of the gear to edit the Postman environment.
4. Please set the following fields appropriately:
    * `Portal_URL`
    * `API_User`
    * `API_Key`

#### **Obtaining API Credentials**
To obtain API credentials for Stealthwatch Cloud, please do the following:

* Login to your Stealthwatch Cloud portal
    * For a free 60-day trial of Stealthwatch Cloud, please visit: https://www.cisco.com/c/en/us/products/security/stealthwatch/stealthwatch-cloud-free-offer.html
* Click the *User* icon in the top-right corner, and select `Your Settings`
* Click the button to `Generate New Key`
* An API `key` will be created and associated for the `user` listed

## Usage
1. From the Collections list on the left side of Postman, select the desired collection as well as the desired request to run.
2. If necessary, modify any parameters in either the `params` section or the `body` section of the request.
3. When ready, press the `send` button to run the Postman request, and view the response below. 

*For more information on how to use Postman, please visit https://learning.getpostman.com.*

## Known issues
No known issues.

## Getting help
Use this project at your own risk (support not provided). *If you need technical support with Cisco Stealthwatch APIs, do one of the following:*

#### Browse the Forum
Check out our [forum](https://community.cisco.com/t5/custom/page/page-id/customFilteredByMultiLabel?board=j-disc-dev-security&labels=stealthwatch) to pose a question or to see if any questions have already been answered by our community. We monitor these forums on a best effort basis and will periodically post answers. 

#### Open A Case
* To open a case by web: http://www.cisco.com/c/en/us/support/index.html
* To open a case by email: tac@cisco.com
* For phone support: 1-800-553-2447 (U.S.)
* For worldwide support numbers: www.cisco.com/en/US/partner/support/tsd_cisco_worldwide_contacts.html
* *If you don't have a Cisco service contract, send an email to swatchc-support@cisco.com describing your problem.*

## Getting involved
Contributions to this code are welcome and appreciated. See [CONTRIBUTING](./CONTRIBUTING.md) for details. Please adhere to our [Code of Conduct](../CODE_OF_CONDUCT.md) at all times.

## Licensing info
This code is licensed under the BSD 3-Clause License. See [LICENSE](./LICENSE) for details. 

