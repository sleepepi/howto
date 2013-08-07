## 1130 Troubleshoot Common Issues

Diplomat has some quirks. Here are some suggestions about what might be going on and how to troubleshoot common issues we have experienced over time.


#### Emails arriving in triplicate

- **Issue:** The Success/Failure emails for a given job start arriving in groups of three (i.e. in triplicate) for no apparent reason.
- **Solution:** Look for potential email addresses on the recipient list that are no longer active.


#### Error: code: 4

- **Issue:** A job fails with the "Error: code: 4" message in the body of the email.
- **Solution:** Look for folders having been uploaded to the SFTP server, instead of encrypted archive files. At times, folders may be named "file.zip" and will look as if they should have been transferred properly by Diplomat. Login to the SFTP server to investigate and remove folders if necessary.


### Key Contacts

Contact the [Help Desk](http://helpdeskselfservice.partners.org/) to troubleshoot these issues.


### Next Section

[Back to Index](https://github.com/sleepepi/howto/blob/master/README.md)
