# Step 5: Manage your invoices and payment methods

Before you start working with resources in your account, familiarize yourself with where you can manage your payment method and access your invoices.

## Managing your payment method

*   To manage your payment method for an account that's billed in USD currency, go to **Manage > Billing and usage**, and select **Payments**.
*   To manage your payment method for an account that's billed in non-USD currency, go to [**IBM Billing**](https://login.ibm.com/authsvc/mtfim/sps/authsvc?PolicyId=urn:ibm:security:authentication:asf:basicldapuser&Target=https%3A%2F%2Flogin.ibm.com%2Foidc%2Fendpoint%2Fdefault%2Fauthorize%3FqsId%3Da0df1a36-75c8-410b-a254-f812c6a437a0%26client_id%3DMyIBMDallasProdCI).

## Accessing your invoices

- To access an invoice for an account that's billed in USD currency, go to **Manage > Billing** and usage, and select **Invoices**.
- To access an invoice for an account that's billed in non-USD currency, go to **Manage > Billing** and usage, and select **Invoices**. Then, click **IBM Invoices**.

# Step 7: Create your resource groups

Resource groups provide a way for you to easily manage access to multiple resources and to view billing usage for a set of resources. With your Pay-As-You-Go account, you can create more resource groups in addition to the default resource group that's included when you first created your Lite account.

1. Go to **Manage > Account > Account resources > Resource groups**.
1. Click **Create**.
1. Enter a name for your resource group, and click **Add**.
See [What makes a good resource group strategy?](https://cloud.ibm.com/docs/account?topic=account-account_setup#resource-group-strategy) for details about how to optimally organize resources in your resource groups.

# Step 9: Invite users to your account

You're ready to invite users to your account and grant them access based on the resources they will work with and the tasks they'll perform. If you want users to create resources from the catalog and assign the resources to a resource group, the following access is required:
- Viewer role or higher on the resource group.
- Editor or administrator role on the service.
1. Complete the following steps:
1. Go to **Manage > Access (IAM) > Users**.
1. Click **Invite users**.
1. Specify the email address of the user. If you are inviting more than one user, they are all assigned the same access.
1. Add the user to one or more of the access groups that you created in the previous step.
1. Click **Invite**.
To learn more about the invitation flow and how users can accept invitations, see [Inviting users to an account](https://cloud.ibm.com/docs/account?topic=account-iamuserinv&interface=ui).
