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

To point your domain to the production environment, you will need to work with your DNS provider to update your records to point to our servers, and so we can also verify that you own the domain name. The table below provides links to the documentation on updating the DNS records of some of the most used providers. 

{{% alert title="Domain verification" color="warning" %}}
It can take up to several hours to verify your domain ownership.
{{% /alert %}}

<table class="table">
<tbody>
<tr>
<td><a href="https://www.ionos.com/help/domains/configuring-your-ip-address/change-a-domains-ip-address-a-record/">1and1</a></td>
<td><a href="https://help.blacknight.com/hc/en-us/articles/212512209">Blacknight</a></td>
<td><a href="https://my.bluehost.com/cgi/help/559">Bluehost</a></td>
<td><a href="https://directnic.com/knowledge/article/142:can+i+redirect+a+subdomain%3F#/knowledge/article/164">Directnic</a></td>
</tr>
<tr>
<td><a href="https://help.dnsmadeeasy.com/managed-dns/dns-record-types/record/">DNSMadeEasy</a></td>
<td><a href="https://www.domain.com/help/article/dns-management-how-to-update-a-records">Domain.com</a></td>
<td><a href="https://www.dotster.com/help/article/dns-management-how-to-update-dns-records">Dotster</a></td>
<td><a href="https://help.dreamhost.com/hc/en-us/articles/215413857">DreamHost</a></td>
</tr>
<tr>
<td><a href="https://kb.easydns.com/knowledge/how-to-make-a-dns-entry/">EasyDNS</a></td>
<td><a href="https://www.enom.com/kb/kb/kb_0002_change-host-records.htm?Highlight=a%20record">Enom</a></td>
<td><a href="https://billing.flokinet.is/index.php?rp=/knowledgebase/57/Nameserver.html">FlokiNET</a></td>
<td><a href="https://docs.gandi.net/en/domain_names/common_operations/dns_records.html">Gandi</a></td>
</tr>
<tr>
<td><a href="https://www.godaddy.com/help/change-nameservers-for-your-domain-names-664">GoDaddy</a></td>
<td><a href="https://support.google.com/domains/answer/9211383?hl=en&amp;ref_topic=9018335">Google Domains</a></td>
<td><a href="https://support.hostgator.com/articles/hosting-guide/lets-get-started/dns-name-servers/manage-dns-records-with-hostgatorenom">HostGator</a></td>
<td><a href="https://my.hostmonster.com/cgi/help/559">HostMonster</a></td>
</tr>
<tr>
<td><a href="https://www.ipage.com/help/article/domain-management-how-to-update-subdomains">iPage</a></td>
<td><a href="https://mediatemple.net/community/products/dv/204403794/how-can-i-change-the-dns-records-for-my-domain">MediaTemple</a></td>
<td><a href="https://support.melbourneit.com.au/articles/help/Domain-Name-Administration-FAQ/?q%3Dedit%2Bnameservers%26fs%3DSearch%26pn%3D1">MelbourneIT</a></td>
<td><a href="https://faq.moniker.com/create-or-delete-subdomain">Moniker</a></td>
</tr>
<tr>
<td><a href="https://www.namecheap.com/support/knowledgebase/article.aspx/434/2237/how-do-i-set-up-host-records-for-a-domain">Namecheap</a></td>
<td><a href="https://www.name.com/support/articles/115004893508-Adding-an-A-record">Name.com</a></td>
<td><a href="https://knowledge.web.com/subjects/article/KA-01094/en-us">Network Solutions</a></td>
<td><a href="https://docs.ovh.com/gb/en/domains/web_hosting_how_to_edit_my_dns_zone/">OVH</a></td>
</tr>
<tr>
<td><a href="https://support.rackspace.com/how-to/creating-dns-records-with-cloud-dns/">Rackspace</a></td>
<td><a href="https://knowledge.web.com/subjects/article/KA-01094/en-us">Register</a></td>
<td><a href="https://www.tucowsdomains.com/provider-search/">Tucows</a></td>
<td><a href="https://www.yola.com/tutorials/article/Adding-A-Records-1285944436490/Publishing_domains_and_email">Yola</a></td>
</tr>
</tbody>
</table>