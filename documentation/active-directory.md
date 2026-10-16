# Active Directory & DNS

Configured Windows Server 2022 as the `DC01` domain controller for `corp.local`.

Created organizational units, domain users, and security groups for Finance and IT.

## Domain Controller Configuration

![DC01 Network Configuration](../screenshots/01-dc01-network-configuration.png)

## Finance OU

![Finance OU](../screenshots/02-finance-ou.png)

## IT OU

![IT OU](../screenshots/03-it-ou.png)

## DNS & Client Connectivity

Configured CLIENT01 to use DC01 for DNS and verified connectivity.

![DNS Connectivity](../screenshots/04-client01-dns-connectivity.png)

## Domain Join

Joined CLIENT01 to the `corp.local` domain.

![Domain Join](../screenshots/05-client01-domain-join.png)

## Domain Authentication

Verified domain authentication from CLIENT01.

![Domain Authentication](../screenshots/06-domain-user-authentication.png)

## Security Group Membership

Verified the Finance user's `GG-Finance` group membership.

![Finance Group Membership](../screenshots/07-finance-group-membership.png)