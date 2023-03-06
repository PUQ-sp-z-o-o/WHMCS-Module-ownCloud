# Email Template (puqownCloud notification disk limit)

#####  [Order now](https://puqcloud.com/whmcs-module-owncloud.php) | [Dowload](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-ownCloud/) | [FAQ](https://faq.puqcloud.com/)

##### Create an email template for customer notifications.

```
System Settings->Email Templates->Create New Email Template
```

- **Email Type:** Product/service
- **Unique Name:** puqownCloud Notification disk limit

[![image-1677936930937.png](https://doc.puq.info/uploads/images/gallery/2023-03/scaled-1680-/image-1677936930937.png)](https://doc.puq.info/uploads/images/gallery/2023-03/image-1677936930937.png)

**Subject:**

```PHP
Disk space usage {$disk_used_percentage} % - {$username}
```

**Body:**

```PHP
Dear {$client_name},

This letter informs you that the disk space usage limit is coming to an end.

Product/Service: {$service_product_name}
Due Date: {$service_next_due_date}

Username: {$username}

Disk limit: {$disk_limit_bytes*$unit_coefficient} {$unit}
Disk used: {$disk_used_unit} {$unit} ({$disk_used_percentage} %)
Disk free: {$disk_free_unit} {$unit} ({$disk_free_percentage} %)


{$signature}
```

[![image-1660027291181.png](https://doc.puq.info/uploads/images/gallery/2022-08/scaled-1680-/image-1660027291181.png)](https://doc.puq.info/uploads/images/gallery/2022-08/image-1660027291181.png)