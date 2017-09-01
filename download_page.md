## Download ZAP

ZAP needs to be installed on the system you intend to perform pentesting on.

### Installation
1. [Download the latest version ZAP 2.7.0](https://github.com/zaproxy/zaproxy/wiki/Downloads)
2. Launch the installation wizard by double clicking on the downloaded executable file ![GitHub Logo](/images/logo.png)
3. Read the License agreement and Click 'Accept' to continue the installation
4. Select 'Standard' or 'Custom' installation
5. Click 'Finish' to exit set up ![Finish dialog image]

### Getting Started

1. Launch ZAP ![image]
2. Select 'Yes, I want to Persist Sessions...' to save ZAP sessions for later retrieval ![image]
3. Select 'No, I do not want to Persist Sessions' to delete ZAP session files upon exit
4. The ZAP interface ![annotated image]

### Quick Start

#### To run a Quick Start test

1. Select the Quick Start tab of the Workspace Window ![workspace image]
2. Enter the full URL of the web application you want to attack. [test website](http://www.webscantest.com/) This website is intentionally vulnerable and safe to test
3. Right click '.....' to open the URL and proxy via ZAP in the browser of your choice ![image]
4. Click the Attack button.

#### How to Interpret your Test Results

As ZAP spiders your web application, it constructs a map of your web applications’ pages
and the resources used to render those pages. Then it records the requests and responses
sent to each page and creates alerts if there is something potentially wrong with a request
or response.

#### Advanced Features

For testing of applications protected using mutual SSL you should generate a Root CA certificate then install it within your browser or HTTP client application.[certificate generation instructions](certificate_generation_and_installation.mdown)

[For manual browser proxy configuration instructions](https://github.com/zaproxy/zap-core-help/wiki/HelpStartProxies)


