# APT Repository for Krikas-Sec Projects

Welcome to the APT repository for **Krikas-Sec**! This repository hosts Debian packages for tools and utilities developed by Krikas-Sec, such as the lightweight and fast port scanner **PortHawk**.

## **Repository URL**
The repository is hosted on GitHub Pages and is accessible at:

**[https://Krikas-Sec.github.io/apt-repo](https://Krikas-Sec.github.io/apt-repo)**

---

## **How to Use This Repository**

### **Step 1: Add the Repository**
To add this APT repository to your Debian-based system, run the following command:

```bash
echo "deb [trusted=yes] https://Krikas-Sec.github.io/apt-repo stable main" | sudo tee -a /etc/apt/sources.list
```
[trusted=yes]: Skips warnings about unsigned packages (recommended only for trusted repositories).
Step 2: Update Your Package List
Run the following command to update your package list:

```bash
sudo apt update
```
Step 3: Install a Package
Once the repository is added, you can install packages using apt. For example, to install PortHawk:

```bash
sudo apt install porthawk
```

## Available Packages

| Package Name | Version | Description                          |
|--------------|---------|--------------------------------------|
| porthawk     | 1.0     | Lightweight port scanner written in Go. |

About PortHawk
PortHawk is a fast and efficient port scanning tool written in Go. It allows users to scan open ports on an IP address or hostname, with customizable options such as port ranges and concurrency limits.

Learn more about PortHawk: [PortHawk on GitHub](https://github.com/Krikas-Sec/PortHawk)

## **Contributing**
If you'd like to contribute to this repository:

Fork the repository.
Create a new branch:
```bash
git checkout -b feature-name
```
Commit your changes:
```bash
git commit -m "Added feature-name"
```
Push your changes:
```bash
git push origin feature-name
```

Open a pull request.

## **Support**
If you find these tools useful, consider supporting the development by visiting my [Buy Me a Coffee page](https://buymeacoffee.com/Tempcoder). Your support is greatly appreciated!

## **License**
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
