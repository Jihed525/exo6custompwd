# Sample : eXo Platform 6.1 Password Recovery Service Customization

This module enables :
- Customize Password recovery service
- Customize the Reset Password e-mail HTML Template sent to users.

# Customization

- The TO-BE customized e-mail template could be found in src/main/resources/conf/forgot_password.html

- The Password Recovery Service redefinition could be found in src/main/java/org/exoplatform/custom/forgotpassword/CustomPasswordRecoveryServiceImpl.java

# Building the project

-Command to Run: mvn clean install

# Installation

-Put the library custom-password-recovery-1.0-SNAPSHOT.jar in the lib directory of eXo platform

# Prerequisites

-Maven 3.3.9

-JDK 8
