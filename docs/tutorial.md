# Use the "Hyperlegendary" toolchain

In this tutorial, you create an open toolchain from the "Hyperlegendary" template. The toolchain builds from GitHub repositories (repos), and deploys to IBM Cloud. After you create the toolchain, you explore your deployed blockchain and client app.

**Note:** Blockchain Starter Plan is available in the US South region only.

## Tutorial

### Prerequisites

1. You must have an IBM Cloud account. The account is free and provides access to everything you need to develop, track, plan, and deploy apps. [Sign up for a trial](https://console.bluemix.net/registration/). The account requires an IBMid. If you don't have an IBMid, you can create one when you register.

2. A GitHub account. If you don't have one, [sign up](https://github.com/).

### Task 1: Create the toolchain

The first step is to add a toolchain that contains the Blockchain service.

1. Open the creation page for the "Hyperlegendary" toolchain by clicking **Create toolchain**.

    [<img src="images/create_toolchain_button.png">](https://console.bluemix.net/devops/setup/deploy/?repository=https%3A//github.com/hyperledger-composer-samples/hyperledger-composer-toolchain&env_id=ibm%3Ayp%3Aus-south&deploy-region=ibm%3Ayp%3Aus-south&sampleName=todo&networkRepo=https%3A//github.com/hyperledger-composer-samples/todo-network&clientRepo=https%3A//github.com/hyperledger-composer-samples/todo-app)

2. On the creation page, review the diagram of the toolchain that you are about to create. The diagram shows each tool integration in its lifecycle phase in the toolchain.

3. Review the default information for the toolchain settings. The toolchain's name identifies it in IBM Cloud. If you want to use a different name, region, or organization, change them.

     **Note:** Each toolchain is associated with a specific org. Because app names are unique, make sure that the toolchain's name is unique within IBM Cloud. You can have only 200 toolchains per org. The org that you are currently working in is displayed by default. To switch to another org, in the banner, click **Manage > Account > Cloud Foundry Orgs**, and then select the org that you want. If you want to switch to a different account, click the **Profile avatar** icon and select the account. If you want to use a specific name, change the toolchain's name.

4. If you haven't authorized with GitHub, you are prompted to do so. Click **Authorize** and follow the instructions to link your IBM Cloud account to a GitHub account.

5. Review your GitHub settings and, if needed, change them. There are several samples that can be used with the "Hyperlegendary" toolchain which you can select.

    * Vehicle Manufacture
    * Commercial Paper
    * TBC

6. Click Create.

### Task 2: Explore the toolchain

### Task n

### Summary
