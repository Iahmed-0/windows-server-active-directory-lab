# Third-party notices

## Hugh Chanetsa's Active Directory lab

Original author: **Hugh Chanetsa (Hugh-Kumbi)**. Copyright (c) 2025 Hugh Chanetsa.
Original repository: [https://github.com/Hugh-Kumbi/Hugh-Kumbi-Active-Directory-Lab](https://github.com/Hugh-Kumbi/Hugh-Kumbi-Active-Directory-Lab).
Source revision: `7fe4c1f9f6ff6871b2944f1d9fd18f8e8076e247`. Accessed 21 October 2026.

The summarized walkthrough adapts the source documentation. The screenshots below are copied without alteration from image links in that documentation and retain the original environment, names, addresses, and interface state. They do not represent this repository owner's completed lab.

The source repository is distributed under the MIT License. Its full copyright and permission notice is retained in [licenses/Hugh-Chanetsa-MIT.txt](licenses/Hugh-Chanetsa-MIT.txt).

## Screenshot credits

| Local image | Subject | Source document | Original image |
| --- | --- | --- | --- |
| [01-domain-promotion.png](images/source/01-domain-promotion.png) | Domain promotion completion | [Source section](https://github.com/Hugh-Kumbi/Hugh-Kumbi-Active-Directory-Lab/blob/7fe4c1f9f6ff6871b2944f1d9fd18f8e8076e247/03-Configuration/I.%20Active-Directory-Setup.md) | [Original](https://github.com/user-attachments/assets/a546e169-0eac-4ee6-85bf-0b825d36210c) |
| [02-dns-validation.png](images/source/02-dns-validation.png) | DNS service-record queries and diagnostic | [Source section](https://github.com/Hugh-Kumbi/Hugh-Kumbi-Active-Directory-Lab/blob/7fe4c1f9f6ff6871b2944f1d9fd18f8e8076e247/03-Configuration/II.%20DNS-Setup.md) | [Original](https://github.com/user-attachments/assets/506cd97a-d99f-4ea0-ba4d-24cba15e9648) |
| [03-organizational-units.png](images/source/03-organizational-units.png) | ADUC organizational-unit structure | [Source section](https://github.com/Hugh-Kumbi/Hugh-Kumbi-Active-Directory-Lab/blob/7fe4c1f9f6ff6871b2944f1d9fd18f8e8076e247/03-Configuration/I.%20Active-Directory-Setup.md) | [Original](https://github.com/user-attachments/assets/5d0ed0ed-c889-4dd1-8823-736d404f4b75) |
| [04-control-panel-policy.png](images/source/04-control-panel-policy.png) | Control Panel restriction setting | [Source section](https://github.com/Hugh-Kumbi/Hugh-Kumbi-Active-Directory-Lab/blob/7fe4c1f9f6ff6871b2944f1d9fd18f8e8076e247/08-User-Environment-Management/IX.%20Control%20Panel%20Restrictions%20%26%20Settings%20Policy.md) | [Original](https://github.com/user-attachments/assets/46c89f91-bcc2-41e7-a160-f71dc1950c97) |
| [05-policy-validation.png](images/source/05-policy-validation.png) | Client restriction message | [Source section](https://github.com/Hugh-Kumbi/Hugh-Kumbi-Active-Directory-Lab/blob/7fe4c1f9f6ff6871b2944f1d9fd18f8e8076e247/08-User-Environment-Management/IX.%20Control%20Panel%20Restrictions%20%26%20Settings%20Policy.md) | [Original](https://github.com/user-attachments/assets/ec4b24ea-d9ba-4ca6-aea6-c7f48f81c009) |
| [06-dhcp-leases.png](images/source/06-dhcp-leases.png) | DHCP client leases | [Source section](https://github.com/Hugh-Kumbi/Hugh-Kumbi-Active-Directory-Lab/blob/7fe4c1f9f6ff6871b2944f1d9fd18f8e8076e247/03-Configuration/III.%20DHCP-Configuration.md) | [Original](https://github.com/user-attachments/assets/08fc0d95-cee4-455a-9062-eb59a1075752) |

## Adaptation notes

- The original lab uses VirtualBox; the summarized preparation uses VMware Workstation.
- The source uses `192.168.1.x`; the walkthrough uses an isolated `192.168.100.0/24` network, without a gateway.
- The OU structure and policy selection are simplified. The file-share access exercise and validation prompts are additions.
- Expected outcomes are instructions for the learner to verify, not reported test results.

Product names and interface elements remain the property of their respective owners.
