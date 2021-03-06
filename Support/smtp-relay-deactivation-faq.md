{{{
  "title": "Retirement of the SMTP Relay Service",
  "date": "9-23-2016",
  "author": "Chris Kleban",
  "attachments": []
}}}

### Description

CenturyLink will be deactivating the [SMTP Relay Service](https://www.ctl.io/knowledge-base/mail/smtp-relay-services-simple/). We realize that this will require existing customers migrate off of this service and we apologize for the inconvenience.

### Deactivation Date

The SMTP Relay Service is being End of Serviced (EOS) on December 1, 2016 with an End of Life (EOL) on January 15, 2017. Please refer to our SMTP Retirement FAQ for more information.


### What exactly is Changing?

* We will be de-activating the SMTP Relay service on January 15, 2017. At this time, our email service will be offline.
* We recommend that existing SMTP Relay customers that are actively using this service migrate off of this service before the deactivation date.
* We have provided a few recommendations for external SMTP Relay services in this document.

### Why is this change happening?

Companies that succeed know their core competency, do it better than others and stay focused. At CenturyLink we know our core competency focuses on our infrastructure and services around network, cloud, hosting, voice and security.  In areas that are not our core competency we partner with best of breed providers.  To that vain, we are now decommissioning our SMTP relay service and instead are offering you the ability to migrate to our ecosystem partners. We provide you a list of partners where this is their core competency so you will receive the level of service you expect from CenturyLink and our partners.

### Why have we chosen to de-activate our service versus improving our service?

We feel that deactivating our service is the best path forward because:

* We don't have a large amount of customers actively using our SMTP Relay service.
* Our SMTP Relay service has been having problems lately.
* Based on input from our customers, via feature requests and customer conversations, there are engineering tasks that are deemed to be more important by the majority of our customers than improving our SMTP Service.


### What does this mean for me?

If you are a customer that actively uses our SMTP Relay service to send emails, you will need to migrate off of this service by the deactivation date mentioned above. If you do not do this, on the deactivation date mentioned above, your emails will no longer be sent through our system.

### What new method should I use to send emails?

Since we aren't offering a replacement service, you must take some sort of action to continue to send emails. You are free to choose whatever method you wish for sending emails. In effort to help you with this process, we are going to provide you a few options for your consideration.


#### Use an external email service

There are many great external SMTP Relay services available that provide you a wide range of email services that meet and exceed our current SMTP feature list. A few of these services are:

* [SendGrid](https://sendgrid.com/)
* [MailChimp with Mandrill Addon](https://www.mandrill.com/)
* [MailJet](https://www.mailjet.com/)

#### Use CL Servers + Software to send emails

For those of you who want to 'Do It YourSelf' you can configure your servers to send emails themselves, versus using a service. This requires your normal system administration like functions and isn't recommended unless sending emails is one of your core business requirements. There are plenty of guides on the Internet on how to do this. For example:

* [CL Blueprint & Halon Software](https://www.ctl.io/knowledge-base/ecosystem-partners/marketplace-guides/getting-started-with-halon-partner-template/) - Use a CL Cloud Blueprint to install the Halon SMTP Software for sending emails.
* [Windows & IIS](https://support.office.com/en-us/article/How-to-configure-IIS-for-relay-with-Office-365-eb57abd2-3859-4e79-b721-2ed1f0f579c9?ui=en-US&rs=en-US&ad=US) - Setup windows SMTP server to send emails.
* [Linux & PostFix](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-postfix-as-a-send-only-smtp-server-on-ubuntu-14-04) - Setup the Postfix SMTP email server on linux to send emails.




### Summary
This information should make you aware of the upcoming deactivation of the SMTP Relay service and provide you a few options for choosing a new method of sending email. If there’s more details or information you would require, please let us know via [help@ctl.io](mailto:help@ctl.io).
