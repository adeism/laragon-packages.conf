# 🚀 Laragon Custom Configuration

This repository contains a custom `package.conf` file for [Laragon](https://laragon.org/) to manage different versions of software in a portable setup. This configuration enables easy switching between multiple versions of essential tools such as phpMyAdmin, MySQL, MongoDB, PostgreSQL, PHP, and more.

## 📦 Included Software and Versions

The configuration file includes the following software with links to both the latest and some older versions:

- **phpMyAdmin** 🛠️
  - Latest: `5.2.1`
  - Previous: `5.2.0`

- **MySQL** 🐬
  - Latest (8.0): `8.0.34`
  - Previous (8.0): `8.0.30`
  - Latest (5.7): `5.7.42`
  - Previous (5.7): `5.7.39`

- **DBeaver** 🐤 (Database tool)
  - Latest: DBeaver CE

- **Yarn** 🧶 (JavaScript Package Manager)
  - Latest: `1.22.19`

- **MongoDB** 🍃
  - Latest: `4.4.10`
  - Previous: `4.0.3`

- **Visual Studio Code** 💻
  - Latest
  - Previous: `1.52.1`

- **PostgreSQL** 🐘
  - Latest: `15.4`
  - Previous: `14.5`

- **PHP** 🐘
  - Latest: `8.2.12`
  - Previous: `8.2.8`, `8.1.21`, `7.4.33`

## 🔧 How to Replace `package.conf` in Laragon Portable

1. **Download the `package.conf`** file from this repository.
2. Locate your **Laragon portable directory**.
3. Navigate to the `etc` folder within your Laragon directory:
4. Replace the existing `package.conf` with the downloaded file.
5. Restart Laragon to apply the updated configurations.

> ⚠️ **Note:** Make sure to back up your original `package.conf` in case you need to revert any changes.

## 📝 Notes

- **Compatibility**: The configuration includes both the latest and some older versions to help maintain compatibility across different projects.
- **Updates**: Check back periodically for updates to this configuration, including new software versions.

## 🤝 Contributing

Contributions are welcome! Feel free to open a pull request with any additional software versions or improvements to the configuration.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
