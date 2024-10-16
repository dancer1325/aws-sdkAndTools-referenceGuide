* AWS IAM Identity Center
  * recommended method of providing AWS credentials | developing on a 👁️NON-AWS compute service 👁️
    * _Example:_ your local development environment
    * 👁️if you are developing | AWS resource (_Example:_ AWS EC2, AWS Cloud9) -> recommended getting credentials | that service instead 👁️
  * goal
    * establish IAM Identity Center access
    * configure -- via AWS access portal & AWS CLI -- for your SDK or tool 

## Configure programmatic access using IAM Identity Center
* steps
  * Establish access and select appropriate permission set
    * [enable IAM Identity Center](https://docs.aws.amazon.com/singlesignon/latest/userguide/get-set-up-for-idc.html)
    * ways to access AWS credentials
      * NOT have established access -- through -- IAM Identity Center
        * TODO:
      * ALREADY access to AWS -- through --
        * a federated identity provider / managed by my employer (_Example:_ Microsoft Entra or Okta)
          * TODO:
        * AWS access portal / managed by my employer
          * TODO:
        * a federated custom identity provider / managed by my employer
          * TODO:
  * Configure SDKs and tools to use IAM Identity Center
    * TODO:
        
