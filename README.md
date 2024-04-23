# Official Devices

This is our repo where all stuff related to official devices is stored.

You also need to use this to apply for official maintainership for your device.

## Folder Structure

Follow below folder structure before adding/modifying any data.

| Directory       | Notes                                                                                                 |
| --------------- | ----------------------------------------------------------------------------------------------------- |
| `/changelogs`   | Source changelog goes here. See [`/changelogs.md`](./changelog.md) for more details.   |
| `/devices`      | Device information goes here. See [`/official_supported_devices.md`](./official_supported_devices.md) for more details. 

## `devices.json` Structure

This file should contain every device supported by **Project Blaze** in the given format:

```json
			"devices": {
                                "name": "Poco X4 Pro",
                                "codename": "veux",
                                "maintainer": "ＡＤＩＴＹＡ",
                                "xda": "null",
                                "telegram": "https://t.me/igadityasingh",
                                "download": "null"
                        },
```

> **Warning**
>
> Fields marked as required should not be empty!

| Fields            | Notes                                               | Required   |
| ----------------- | --------------------------------------------------- | ---------- |
| `codename`        | Primary codename of the device                      | `true`     |
| `codename_alt`    | Alternate codename of the device if any             | `optional` |
| `vendor`          | Device manufacturer name                            | `true`     |
| `model`           | Device name                                         | `true`     |
| `maintainer_name` | Maintainer name                                     | `true`     |
| `active`          | Whether this device is in active development or not | `true`     |

## `team.json` Structure

This file should contain every team member working on **Project Blaze** in the given format:

```json
        {
                "name": "Aditya Singh",
                "role": "Founder / Lead Dev",
                "avatar": "https://github.com/afterallafk.png"
        },
```

> **Warning**
>
> Fields marked as required should not be empty!

| Fields     | Notes                     | Required   |
| ---------- | ------------------------- | ---------- |
| `name`     | Member name               | `true`     |
| `role`     | Role of the member        | `true`     |
| `github`   | Member's github username  | `true`     |
| `telegram` | Member's telegram profile | `optional` |
| `xda`      | Member's XDA profile      | `optional` |

1. [Device stability requirements](https://github.com/ProjectBlaze/maintainership/blob/12.1/requirements.md)
2. [Maintainer requirements](https://github.com/ProjectBlaze/maintainership/blob/12.1/maintainerreq.md)
3. To Apply For Maintainership [here](https://github.com/ProjectBlaze/maintainership)
