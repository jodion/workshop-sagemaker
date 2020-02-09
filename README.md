# SageMaker workshop: "Build, train, and deploy ML models with Amazon SageMaker"

## Companion slides
[Slides can be found here](workshop-sagemaker.pdf)

## Setup instructions

**Don't use your personal account, we don't have credits for you**

1. Navigate to: https://dashboard.eventengine.run.
1. In the **Team Hash** field, input the **12 character hash** that was given to you.
1. Click on the **Accept Terms & Login** green button.
1. In the Team Dashboard page, click on the **AWS Console** button.
1. In the AWS Console Login window, click on the **Open AWS Console** button. You will be logged into an AWS account.
1. Make sure you are in the **Canada (Central)** region by looking at the top right corner of the screen. It should say **Central** to the left of Support. If not, click on the field next to Support and select Canada (Central).
1. In the top bar menu, navigate to **Services > Amazon SageMaker** to open the SageMaker console.
1. In the navigation menu on the left, click **Notebook instances**.
1. Click on the **Create notebook instance** button.
1. Fill the following fields:
   * Notebook instance name: type a name for your instance, e.g `workshop-sagemaker`.
   * Notebook instance type: select **ml.t3.medium**. No need for anything bigger :)
   * IAM role: select **Create a new role** from the **Choose an IAM role** dropdown. In the dialog window, do the following:
     * Select **Any S3 bucket**. Normally, you should select a specific bucket, but it hasn't been created yet.
     * Click on the **Create role** button.
   * Click on the **Git repositories** section to expand it and do the following:
     * Select **Clone a public Git repository to this notebook instance only** from the Repository dropdown list.
     * In the **Git repository URL** field, enter: `https://github.com/jodion/workshop-sagemaker.git`
   * Leave all other fields as is.
1. Click on the **Create notebook instance** button. This will bring you back to the list of Notebook instances where you should see yours being created. Wait for your Notebook instance to become **In Service** which should take less than 5 minutes. You may have to refresh the page depending on your browser.
1. Next to your **Notebook instance**, click on the link **Open JupyterLab**. This will open the JupyterLab page in your browser.
1. In the **JupyterLab** page, on the navigation section on the left of the screen, double-click on **notebook.ipynb**. This will open the IPython Notebook.
1. The reminder of the lab instructions are in the notebook you just opened. Have fun!
