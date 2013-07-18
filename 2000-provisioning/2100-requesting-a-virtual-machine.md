## 2100 Requesting a Virtual Machine

New virtual machines are requested using the form found at [Research Computing - DIPR Signup](https://rc.partners.org/dipr_signup).

Enter your own information for **Primary User** section.

For **Management Contact** and **Billing Contact** use Melissa Giglio as the contact.

For **VM information**

```
VM Size:

    Medium: 1 GB of RAM (CentOS 6.4 +)

Preferred VM Name:

    VMNAME <- Choose a name for the DIPR Virtual Machine

Users needing SHHS Access to this VM:

    USERNAME

Users needing Admin Access to this VM:

    USERNAME

Applications or packages needed:

    SSL, Apache
```

For external access specify proxy as follows:

Request that https access goes from https://VMNAME.partners.org and that http://VMNAME.partners.org forward to 443 and 80 respectively (standard) on https://VMNAME.dipr.partners.org and http://VMNAME.dipr.partners.org.

### Key Contacts

Most Virtual Machine DIPR requests are completed by Aaron Zschau <azschau@partners.org>.


### Next Section

[2200 - Requesting a Database](https://github.com/sleepepi/howto/blob/master/2000-provisioning/2200-requesting-a-database.md)
