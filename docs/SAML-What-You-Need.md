# SAML Integration - What You Need

* Java Runtime Environment - https://www.java.com/en/download/
* NS Metadata Toolkit - [NS_Metadata_Toolkit.jar](https://github.com/Digital-Platform-Services/Nova-Scotia-Login-Service/raw/master/Metadata%20Toolkit/NS_Metadata_Toolkit.jar)	
* NSLS Connectivity Form - [NSLS RFC Forms.xlsm](https://github.com/Digital-Platform-Services/Nova-Scotia-Login-Service/raw/master/Forms/NSLS%20-%20RFC%20Forms.xlsm)

### IdP Metadata File
* Test Environment - [SOAP](https://github.com/Digital-Platform-Services/Nova-Scotia-Login-Service/blob/master/IdP-Metadata/te-mynsid-idp-metadata-signed.soap_slo_only.20190801.xml) | [HTTP-Redirect](https://github.com/Digital-Platform-Services/Nova-Scotia-Login-Service/blob/master/IdP-Metadata/te-mynsid-idp-metadata-signed.redirect_slo_only.20190801.xml)
* Production Environment - [SOAP](https://github.com/Digital-Platform-Services/Nova-Scotia-Login-Service/blob/master/IdP-Metadata/mynsid-idp.meta-signed-slo-soap.20190814.xml) | [HTTP-Redirect](https://github.com/Digital-Platform-Services/Nova-Scotia-Login-Service/blob/master/IdP-Metadata/mynsid-idp.meta-signed-slo-redirect.20190814.xml)

### Optional 
* Metadata Template - [Metadata Template.xml](https://github.com/Digital-Platform-Services/Nova-Scotia-Login-Service/blob/master/Metadata%20Template/Metadata%20Template.xml)

## Generate Private Keys and Certificate Signing Requests (CSRs)
As part of the integration with the NSLS, you will need to generate **2 private keys** and acquire **2 public certificates**. The NS Metadata Toolkit will help you to get started.

## Next steps
Section 1.2 - run the NS Metadata Toolkit and use it to generate 2 CSRs and 2 private keys.
