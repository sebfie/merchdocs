---
title: Transactional Email Users
---

Transactional email messages are automatically generated by the system in response to an event, such as an order confirmation, shipping notification, or password change.

Transactional email messages are in a legally distinct category, and must not contain any content that is related to marketing or sales.

To send transactional email through the API you can use either the REST operation Send transactional email or the SOAP method `SendTransactionalEmail`. Transactional email is sent by SMTP, and requires a dedicated user email address. To learn more, see [Transactional email - an overview][1]{: target="_blank"}.

![]({% link images/images/engagement-cloud-access-transactional-email-users.png %}){: .zoom}
*Transactional Email Users*

## To add a transactional email user

1. Tap the **Settings** ( ![]({% link images/images/icon-settings-engagement-cloud.png %})) icon at the bottom of the sidebar. Then on the menu, choose **Access**.

1. On the Access page, choose the **Transactional email users** tab.

1. Tap <span class="btn">New user</span>. Then under User Details, do the following:

    * Accept the randomly-generated **Email address**. Each transactional email user is assigned a unique email address.

    * In the **Description** field, describe how the account is to be used.

        Because this field appears in the list after the randomly-generated email address, it should make the user easy to identify.

[1]: https://support.dotdigital.com/hc/en-gb/articles/360000044584-Transactional-email-an-overview