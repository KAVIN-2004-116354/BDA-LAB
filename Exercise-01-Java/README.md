# Exercise 01: Java Setup

## Aim
Install Java and verify installation.

## Commands

```bash
sudo apt update
sudo apt install openjdk-11-jdk -y
java -version
javac -version
```

## Result
Java installed successfully.

Exercise-02-SSH/README.md
Exercise-03-Hadoop-Installation/README.md
Exercise-04-Hadoop-Configuration/README.md
Exercise-05-HDFS-Commands/README.md
Exercise-06-File-Operations/README.md
Exercise-07-YARN/README.md
Exercise-08-Datasets/README.md

# Exercise 02: SSH Setup

## Commands

```bash
sudo apt install openssh-server openssh-client -y
ssh-keygen -t rsa -P ""
cat ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys
chmod 600 ~/.ssh/authorized_keys
ssh localhost
```

## Result
SSH configured successfully.
BDA-LAB
│
├── Exercise-01-Java
│   └── README.md
├── Exercise-02-SSH
│   └── README.md
├── Exercise-03-Hadoop-Installation
│   └── README.md
├── Exercise-04-Hadoop-Configuration
│   └── README.md
├── Exercise-05-HDFS-Commands
│   └── README.md
├── Exercise-06-File-Operations
│   └── README.md
├── Exercise-07-YARN
│   └── README.md
└── Exercise-08-Datasets
