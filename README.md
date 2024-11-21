# 🚀 Laragon Custom Configuration with [Linkchecker](https://github.com/adeism/link-checker)

A custom package.conf file for Laragon that simplifies managing various software versions in a portable setup. The configuration makes it easy to switch between multiple versions of essential tools like phpMyAdmin, MySQL, MongoDB, PostgreSQL, PHP, and more.

Includes a Python script to verify and automatically update download links, ensuring your tools stay up-to-date with minimal effort.


<img src="https://github.com/adeism/laragon-packages.conf/blob/main/image.png" alt="Laragon Packages" width="500" />

## 📦 Available Software and Versions

The configuration file includes the following software with multiple versions for flexibility and compatibility:

### **phpMyAdmin** 🛠️

- **Latest:** `5.2.1`
- **Previous Versions:**
  - `5.2.0`
  - `5.1.1`
  - `5.0.4`
  - `4.9.10`
  - `4.8.5`

### **MySQL** 🐬

- **Latest 8.0:** `8.0.34`
- **Previous 8.0 Versions:**
  - `8.0.33`
  - `8.0.30`
  - `8.0.27`
- **Latest 5.7:** `5.7.42`
- **Previous 5.7 Versions:**
  - `5.7.39`
  - `5.7.35`
  - `5.7.32`
- **Older Versions:**
  - `5.6.51`
  - `5.5.62`

### **DBeaver** 🐤 (Database Tool)

- **Latest:** `23.0.0`
- **Previous Versions:**
  - `22.3.5`
  - `21.3.1`
  - `20.0.5`

### **Yarn** 🧶 (JavaScript Package Manager)

- **Latest:** `1.22.19`
- **Previous Versions:**
  - `1.22.10`
  - `1.22.5`
  - `1.19.2`

### **MongoDB** 🍃

- **Latest 6.0:** `6.0.5`
- **Previous Versions:**
  - `5.0.14`
  - `4.4.10`
  - `4.2.22`
  - `4.0.28`
  - `3.6.23`

### **Visual Studio Code** 💻

- **Latest**
- **Previous Versions:**
  - `1.80.0`
  - `1.75.0`
  - `1.70.2`
  - `1.65.2`
  - `1.60.0`
  - `1.55.2`
  - `1.50.0`

### **PostgreSQL** 🐘

- **Latest:** `15.4`
- **Previous Versions:**
  - `14.5`
  - `13.7`
  - `12.11`
  - `11.16`
  - `10.21`

### **PHP** 🐘

- **Latest:** `8.2.12`
- **Previous Versions:**
  - `8.2.8`
  - `8.1.21`
  - `8.0.26`
  - `7.4.33`
  - `7.3.30`
  - `7.2.34`
  - `7.1.33`
  - `7.0.33`
  - `5.6.40`
  - `5.5.38`
  - `5.4.45`
  - `5.3.29`
  - `5.2.17`

## 🔧 How to Replace `package.conf` in Laragon Portable

1. **Download the `package.conf`** file from this repository.
2. Locate your **Laragon portable directory**.
3. Navigate to the `etc` folder within your Laragon directory:
4. Replace the existing `package.conf` with the downloaded file.
5. Restart Laragon to apply the updated configurations.

> ⚠️ **Note:** Make sure to back up your original `package.conf` in case you need to revert any changes.

## 📝 Notes

- **Compatibility:** This configuration includes both the latest and older versions to support different project requirements.

- **PHP Versions:**
- **PHP 5.x:** Available for legacy applications.
- **Architecture:** Note that PHP versions below 7.0 may only be available in 32-bit architecture (`x86`).
- **Thread Safety:** Some older PHP versions may only be available in Non-Thread Safe (NTS) builds.

- **Dependencies:**
- **Visual C++ Redistributable:** Different PHP versions require specific Visual C++ Redistributable packages:
 - **VC6:** PHP 5.2
 - **VC9:** PHP 5.3, 5.4
 - **VC11:** PHP 5.5, 5.6
 - **VC14:** PHP 7.0, 7.1
 - **VC15:** PHP 7.2, 7.3
 - **VS16:** PHP 7.4 and newer
- Ensure you have the appropriate Visual C++ Redistributable installed for the PHP version you are using.

- **Security:** Using outdated software versions may pose security risks. It's recommended to use the latest stable versions whenever possible.

- **Link Validity:** All links have been checked and are valid as of October 2023. If you encounter broken links, please refer to the official websites or repositories of the respective software.

## 🤝 Contributing

Contributions are welcome! If you have additional software versions or improvements to add, feel free to open a pull request.

