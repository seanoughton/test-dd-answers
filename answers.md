## Links

1. Link to [host-dashboard](https://app.datadoghq.com/dash/host/732018690?live=true&page=0&tile_size=m&is_auto=false&from_ts=1544806380000&to_ts=1544809980000)

2. Link to [mySQL-integration](https://app.datadoghq.com/dash/integration/12/mysql---overview?tile_size=m&page=0&is_auto=false&from_ts=1544806500000&to_ts=1544810100000&live=true)

3. Link to [Host-Map](https://app.datadoghq.com/infrastructure/map?fillby=avg%3Acpuutilization&sizeby=avg%3Anometric&groupby=availability-zone&nameby=name&nometrichosts=false&tvMode=false&nogrouphosts=true&palette=green_to_orange&paletteflip=false&node_type=host)

4. Link to [My Monitors](https://app.datadoghq.com/monitors/manage)

5. Link to [Datadog-Docs](https://docs.datadoghq.com/)


*** All Screenshots are inline with the answers to the questions. ***

## Section 1: Prerequisites - Setup the environment
1. Spin up a Linux Virtual Machine using Vagrant and Virtual Box

   - Install VirtualBox
     - Link to [Install-VirtualBox](https://www.virtualbox.org/wiki/Downloads)
     - ![VirtualBox](./datadog-images/section-1/install-virtual-box.png)

   - Install Vagrant
     - Link to [Install-Vagrant](https://www.vagrantup.com/intro/getting-started/install.html)

     - After Installing Vagrant, you create a Vagrant file in the directory where you want to create your VM. You do this with the following command:  `$ vagrant init ubuntu/xenial64` .
    This clones the appropriate box, in my case an Ubuntu Linux 16.04 box.
     - Once the Vagrant file has been created properly, you can spin up your VM with the command: `vagrant up`
     - After the VM has spun up, you can enter the machine with the command: `vagrant ssh`
     - You now have access to the VM through the command line and can navigate around, install software and create and execute files.

2. Sign up for Datadog
   - Signing up for Datadog is super easy. Here is a screenshot of the form.
   - ![sign up](./datadog-images/section-1/signup-for-datadog.png)

3. Install the Agent on VM and get it reporting metrics
   - To install the Datadog Agent on your VM
     - Datadog makes this really easy by giving you a link to the instructions in the Getting Started Dropdown Menu
     - There is a link there for Install an Agent
       - Link to [Install-Agent](https://app.datadoghq.com/account/settings#agent)
     - Here is a screenshot of the Installation Instructions:
       - ![install agent](./datadog-images/section-1/how-to-install-datadog-01.png)


## Section 2: Collecting Metrics

## Section 3: Visualizing Data

## Section 4: Monitoring Data

## Section 5: Collecting APM Data

## Section 6: Creative Use for Datadog Question
