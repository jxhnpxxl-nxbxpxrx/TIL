# Amazon Web Server

## Serverless Application Model

is a template driven tool for creating and managing serverless applications. In just a few lines of code you can define complex AWS Lambda based serverless applications, security permissions, and advanced configuration capabilities.



## Installing AWS on Ubuntu 20.04
###

1. Download the [AWS SAM CLI zip file](https://github.com/aws/aws-sam-cli/releases/latest/download/aws-sam-cli-linux-x86_64.zip)
2. Paste the downloaded file to `\\wsl$\Ubuntu-20.04\home\<<ubuntu Name>>`
3. Run `sha256sum aws-sam-cli-linux-x86_64.zip` inside the ubuntu terminal

    should display this after installing: 
        `<64-character SHA256 hash value> aws-sam-cli-linux-x86_64.zip`
4. Unziping the installation files into the sam-installation/ subdirectory, use this:
    `unzip aws-sam-cli-linux-x86_64.zip -d sam-installation`

5. Install the AWS SAM CLI bu running this:
        `sudo ./sam-installation/install`

6. Verify the installation bu running this:
        `sam --version`

        When installation is successful, you should see output like the following:
            `SAM CLI, version 1.18.0`

DONE!!





