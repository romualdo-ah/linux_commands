# linux_commands
Linux commands that saved my days.

## Recover lost OS entries on your GRUB.

When you install one linux on your machine and your GRUB does not display the others systems. This is useful for GRUB to recognize it later.

```sudo apt-get update```

```sudo apt-get install os-prober```

```sudo os-prober```

```sudo update-grub```

# Install nvm for node

```sudo apt install curl``` 

```curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash ```

The nvm installer script creates environment entry to login script of the current user. You can either logout and login again to load the environment or execute the below command to do the same.

```source ~/.profile```

Install the latest version of node.js. Here node is the alias for the latest version.

```nvm install node```

To install a specific version of node:

```nvm install 12.18.3```

You can also select a different version for the current session. The selected version will be the currently active version for the current shell only.

```nvm use 12.18.3```

To find the default Node version set for the current user, type:

```nvm run default --version```

## Install snap

```sudo apt install snapd```

## Install .NET Core

Install snap ☝️, then

```sudo snap install dotnet-sdk --classic```

## Install Dbeaver (database manager)

```sudo snap install dbeaver-ce```

## Install Java

### Install default JRE and JDK

```sudo apt install default-jre```

```sudo apt install default-jdk```

### Install a especific version

```sudo apt install openjdk-8-jdk```

```sudo apt install openjdk-8-jre```

 or

```sudo apt install openjdk-9-jdk```

```sudo apt install openjdk-9-jre```

or 

```sudo apt install openjdk-11-jdk```

```sudo apt install openjdk-11-jre```

### Set default Java JDK

```sudo update-alternatives --config java```

Then select your preffered JDK.

## Start and stop some database services

### For MYSQL

```sudo service mysql start```

```sudo service mysql stop```

### For Mongo

```sudo service mongod start```

```sudo service mongod stop```
