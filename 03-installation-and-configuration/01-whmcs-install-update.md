# WHMCS Installation and Update

### ownCloud module **[WHMCS](https://puqcloud.com/link.php?id=77)**
#####  [Order now](https://puqcloud.com/whmcs-module-owncloud.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-ownCloud/) | [Community](https://community.puqcloud.com/)

## System requirements

| Requirement | Minimum |
|-------------|---------|
| **WHMCS** | 8.x+, 9.x+ |
| **PHP** | 7.4, 8.1, 8.2, 8.3, 8.4 |
| **ownCloud** | 10.x+ |
| **ionCube Loader** | v15+ |

> **Note:** The module uses ionCube encoding. Make sure ionCube Loader is installed and active on your server.

---

## Download

The module can be ordered and downloaded from PUQ Cloud:

- **Order Module:** [https://puqcloud.com/whmcs-module-owncloud.php](https://puqcloud.com/whmcs-module-owncloud.php)
- **Documentation:** [https://doc.puq.info/books/owncloud-whmcs-module](https://doc.puq.info/books/owncloud-whmcs-module)
- **All Versions / Download:** [https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-ownCloud/](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-ownCloud/)
- **Support:** [https://puqcloud.com/submitticket.php](https://puqcloud.com/submitticket.php?step=2&deptid=1)
- **Community:** [https://community.puqcloud.com/](https://community.puqcloud.com/)
- **Direct download link for the latest version:**

```
wget https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-ownCloud/PUQ_WHMCS-ownCloud-latest.zip
```

> All versions can be found at this link:
> [https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-ownCloud/](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-ownCloud/)
>
> Older module versions for WHMCS 8 are available in the archive directory:
> [https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-ownCloud/archive/](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-ownCloud/archive/)

After downloading, extract the archive:

```
unzip PUQ_WHMCS-ownCloud-latest.zip
```

---

## Installation

### Step 1: Upload files

Extract the module archive and copy the `puqownCloud` directory to the WHMCS servers module directory:

```
WHMCS_WEB_DIR/modules/servers/puqownCloud
```

Once the files are uploaded, proceed to the WHMCS Setup Guide to configure the server and product.

---

## Update

The update procedure is the same as installation — replace the existing files with the new version:

1. Download the latest version as described in the Download section.
2. Unzip the archive.
3. Replace the existing `WHMCS_WEB_DIR/modules/servers/puqownCloud` directory with the new one.
4. Verify the version number in the module interface matches the new release.
