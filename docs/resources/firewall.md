---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "vpsie_firewall Resource - terraform-provider-vpsie"
subcategory: ""
description: |-
  
---

# vpsie_firewall (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Read-Only

- `action` (String)
- `category` (String)
- `fullname` (String)
- `group_id` (Number)
- `hostname` (String)
- `id` (Number) The ID of this resource.
- `identifier` (String)
- `rules` (Attributes List) (see [below for nested schema](#nestedatt--rules))
- `type` (String)
- `user_id` (Number)
- `vms_data` (Attributes List) (see [below for nested schema](#nestedatt--vms_data))

<a id="nestedatt--rules"></a>
### Nested Schema for `rules`

Read-Only:

- `in_bound` (Attributes List) (see [below for nested schema](#nestedatt--rules--in_bound))
- `out_bound` (Attributes List) (see [below for nested schema](#nestedatt--rules--out_bound))

<a id="nestedatt--rules--in_bound"></a>
### Nested Schema for `rules.in_bound`

Read-Only:

- `action` (String)
- `comment` (String)
- `created_on` (String)
- `dest` (List of List of String)
- `dport` (String)
- `enable` (Number)
- `group_id` (Number)
- `id` (Number)
- `identifier` (String)
- `iface` (String)
- `log` (String)
- `macro` (String)
- `proto` (String)
- `source` (List of List of String)
- `sport` (String)
- `type` (String)
- `updated_on` (String)
- `user_id` (Number)


<a id="nestedatt--rules--out_bound"></a>
### Nested Schema for `rules.out_bound`

Read-Only:

- `action` (String)
- `comment` (String)
- `created_on` (String)
- `dest` (List of List of String)
- `dport` (String)
- `enable` (Number)
- `group_id` (Number)
- `id` (Number)
- `identifier` (String)
- `iface` (String)
- `log` (String)
- `macro` (String)
- `proto` (String)
- `source` (List of List of String)
- `sport` (String)
- `type` (String)
- `updated_on` (String)
- `user_id` (Number)



<a id="nestedatt--vms_data"></a>
### Nested Schema for `vms_data`

Read-Only:

- `category` (String)
- `fullname` (String)
- `hostname` (String)
- `identifier` (String)