---
title: "Custom Domains"
weight: 500
---

All projects, after being deployed and promoted, get an `xtages.dev` subdomain (for staging the domain name looks like `staging-${some_number}.xtages.dev` and for production `production-${some_number}.xtages.dev`).

However, you may associate your own domain with the application running in production. We handle the creation and renewal of the SSL certificate for your custom domain.

## Adding a Custom Domain

Go to the project settings page:

{{< respfig src="project_settings.png" caption="Project settings." >}}

Then in the “Domain settings" section, add the name of the domain you wish to associate.

{{< respfig src="domain_settings.png" caption="Domain settings." >}}

To point your domain name to the production environment, you will need to work with your DNS provider to update your record points to our servers and we can also verify that you own the domain name. The table below provides links to the documentation of some of the most used DNS providers and how to update their configurations. It can take up to several hours to verify your domain ownership.


|[1and1](https://www.ionos.com/help/domains/configuring-your-ip-address/change-a-domains-ip-address-a-record/)                |[Blacknight](https://help.blacknight.com/hc/en-us/articles/212512209)                                                 |[Bluehost](https://my.bluehost.com/cgi/help/559)                                                                                              |[Directnic](https://directnic.com/knowledge/article/142:can+i+redirect+a+subdomain%3F#/knowledge/article/164) |
|[DNSMadeEasy](https://help.dnsmadeeasy.com/managed-dns/dns-record-types/record/)                                             |[Domain.com](https://www.domain.com/help/article/dns-management-how-to-update-a-records)                              |[Dotster](https://www.dotster.com/help/article/dns-management-how-to-update-dns-records)                                                      |[DreamHost](https://help.dreamhost.com/hc/en-us/articles/215413857)                                           |
|[EasyDNS](https://kb.easydns.com/knowledge/how-to-make-a-dns-entry/)                                                         |[Enom](https://www.enom.com/kb/kb/kb_0002_change-host-records.htm?Highlight=a%20record)                               |[FlokiNET](https://billing.flokinet.is/index.php?rp=/knowledgebase/57/Nameserver.html)                                                        |[Gandi](https://docs.gandi.net/en/domain_names/common_operations/dns_records.html)                            |
|[GoDaddy](https://www.godaddy.com/help/change-nameservers-for-your-domain-names-664)                                         |[Google Domains](https://support.google.com/domains/answer/9211383?hl=en&ref_topic=9018335)                           |[HostGator](https://support.hostgator.com/articles/hosting-guide/lets-get-started/dns-name-servers/manage-dns-records-with-hostgatorenom)     |[HostMonster](https://my.hostmonster.com/cgi/help/559)                                                        |
|[iPage](https://www.ipage.com/help/article/domain-management-how-to-update-subdomains)                                       |[MediaTemple](https://mediatemple.net/community/products/dv/204403794/how-can-i-change-the-dns-records-for-my-domain) |[MelbourneIT](https://support.melbourneit.com.au/articles/help/Domain-Name-Administration-FAQ/?q%3Dedit%2Bnameservers%26fs%3DSearch%26pn%3D1) |[Moniker](https://faq.moniker.com/create-or-delete-subdomain)                                                 |
|[Namecheap](https://www.namecheap.com/support/knowledgebase/article.aspx/434/2237/how-do-i-set-up-host-records-for-a-domain) |[Name.com](https://www.name.com/support/articles/115004893508-Adding-an-A-record)                                     |[Network Solutions](https://knowledge.web.com/subjects/article/KA-01094/en-us)                                                                |[OVH](https://docs.ovh.com/gb/en/domains/web_hosting_how_to_edit_my_dns_zone/)                                |
|[Rackspace](https://support.rackspace.com/how-to/creating-dns-records-with-cloud-dns/)                                       |[Register](https://knowledge.web.com/subjects/article/KA-01094/en-us)                                                 |[Tucows](https://www.tucowsdomains.com/provider-search/)                                                                                      |[Yola](https://www.yola.com/tutorials/article/Adding-A-Records-1285944436490/Publishing_domains_and_email)    |