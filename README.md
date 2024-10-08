# testing1# *React Native* | *Hapchi1* | *302938* | *studio_pro*

## *Catalog ProjectId: 156367* | *Catalog BuildId: 19238*

## NOTE FOR DEVELOPERS:
Clone the code-engine branch into your working branch. The contents of the branch may get overwritten.
## Author:
Code-Engine
## Keywords:
 - Hapchi1
 - web
## Assembled Features To Block Status

| *Feature-Name*        | *Block-Name*        | *Path*  | *Status*  |
|:-------------|:-------------|:-------------|:-------------|
| CategoriessubCategories      | categoriessubcategories<br>core<br>      | {+packages/blocks/categoriessubcategories+}<br>{+packages/blocks/core+}<br> | {+Non-Empty+} |
| SignuploginModule2      | social-media-account-registration<br>social-media-account<br>email-account-login<br>utilities<br>email-account-registration<br>country-code-selector<br>forgot-password<br>otp-input-confirmation<br>social-media-account-login<br>      | {+packages/blocks/social-media-account-registration+}<br>{+packages/blocks/social-media-account+}<br>{+packages/blocks/email-account-login+}<br>{+packages/blocks/utilities+}<br>{+packages/blocks/email-account-registration+}<br>{+packages/blocks/country-code-selector+}<br>{+packages/blocks/forgot-password+}<br>{+packages/blocks/otp-input-confirmation+}<br>{+packages/blocks/social-media-account-login+}<br> | {+Non-Empty+} |
| Dashboard4      | dashboard<br>      | {+packages/blocks/dashboard+}<br> | {+Non-Empty+} |
| Annotations      | annotations<br>      | {+packages/blocks/annotations+}<br> | {+Non-Empty+} |
| AdHocReporting      | visualanalytics<br>      | {+packages/blocks/visualanalytics+}<br> | {+Non-Empty+} |
| Catalogue      | catalogue<br>      | {+packages/blocks/catalogue+}<br> | {+Non-Empty+} |
| DataImportexportcsv      | importexportdata<br>      | {+packages/blocks/importexportdata+}<br> | {+Non-Empty+} |
| Feedback      | contactus<br>      | {+packages/blocks/contactus+}<br> | {+Non-Empty+} |
| LandingPage      | landingpage<br>      | {+packages/blocks/landingpage+}<br> | {+Non-Empty+} |
| ActivityLog      | analytics<br>      | {+packages/blocks/analytics+}<br> | {+Non-Empty+} |
| BulkUploading      | BulkUploading      | {-packages/blocks/BulkUploading-} | {-Empty-} |
| MultipageForms2      | MultipageForms2      | {-packages/blocks/MultipageForms2-} | {-Empty-} |
| PeopleManagement2      | PeopleManagement2      | {-packages/blocks/PeopleManagement2-} | {-Empty-} |
| AutomaticFormCreation      | AutomaticFormCreation      | {-packages/blocks/AutomaticFormCreation-} | {-Empty-} |
| CustomisableUserProfiles      | CustomisableUserProfiles      | {-packages/blocks/CustomisableUserProfiles-} | {-Empty-} |
| ReviewPrompt      | ReviewPrompt      | {-packages/blocks/ReviewPrompt-} | {-Empty-} |
| AdminConsole      | AdminConsole      | {-packages/blocks/AdminConsole-} | {-Empty-} |
| RolesPermissions      | RolesPermissions      | {-packages/blocks/RolesPermissions-} | {-Empty-} |
| DataEncryption      | DataEncryption      | {-packages/blocks/DataEncryption-} | {-Empty-} |
| VideoManagement      | VideoManagement      | {-packages/blocks/VideoManagement-} | {-Empty-} |
| DownloadOptions      | DownloadOptions      | {-packages/blocks/DownloadOptions-} | {-Empty-} |
| ContentManagement      | ContentManagement      | {-packages/blocks/ContentManagement-} | {-Empty-} |
| CfScreenRecordingRestriction2      | CfScreenRecordingRestriction2      | {-packages/blocks/CfScreenRecordingRestriction2-} | {-Empty-} |
| EmailNotifications2      | EmailNotifications2      | {-packages/blocks/EmailNotifications2-} | {-Empty-} |
| UserGroups2      | UserGroups2      | {-packages/blocks/UserGroups2-} | {-Empty-} |

## AWS BACKEND DEPLOYMENT URL
 - BaseURL exported as: "https://project-name-notfound-302938-ruby.b302938.none.eastus.az.svc.builder.ai"
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

See docs folder for additional information.

### Prerequisites

What things you need to install the software and how to install them

* React Native (last tested on react-native0.61.3)
  - https://facebook.github.io/react-native/docs/getting-started

* IFF brew is installed and user doesn't have permisions.

  $ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/uninstall)"
  $ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"


* XCode 11 or greater

* XCode Command Line Tools

  $ xcode-select --install


* Android SDK

  $ brew cask install android-sdk


* JDK 11

  $ brew tap homebrew/cask-versions
  $ brew cask install java
  $ brew cask install java11


### Installing

A step by step series of examples that tell you how to get a development env running

Install yarn

  $ brew install yarn


Install node


  $ brew install node


Web

  $ yarn
  $ yarn workspace web start 
  (Note: After udpating depencies run again if no cocde erros. )


iOS

  $ yarn
  $ cd packages/mobile/ios && pod install && cd ../../../ && cp node-runners/RCTUIImageViewAnimated.m node_modules/react-native/Libraries/Image/RCTUIImageViewAnimated.m && npx react-native bundle --entry-file ./packages/mobile/index.js --platform ios --dev true --bundle-output ./packages/mobile/ios/main.jsbundle && yarn ios


Android - https://docs.expo.io/versions/latest/workflow/android-studio-emulator/

  $ yarn
  $ export JAVA_HOME=`/usr/libexec/java_home -v 11`; java -version; export ANDROID_HOME=${HOME}/Library/Android/sdk; export PATH=${PATH}:${ANDROID_HOME}/emulator && yarn android


## Running the tests


  $ yarn test



## CI/CD Details

We use GitlabCI for our deployment/Build pipelines

## Versioning

We use http://semver.org/ for versioning. For the versions available, see the https://github.com/your/project/tags.



