# Npm App :monkey: :cyclone:
This repository will show you how to run NPM in side your local virtual machine(VM).

### Pre-requisites

- Git
- Vagrant
- Virtual Box
- Rake spec

## Steps
The steps below will show you how to run the app within your VM, ensure you cloned the repo and navigate to your folder called 'starter_code_no_provision' within your terminal.

After you have done that, please follow the commands below.

##### Build virtual machine
First we will build the local machine:
```
$ vagrant up
```
this may take some time, so please be patient.
After this you need to ssh into the app within the VM.
```
vagrant shh app
```

##### Test
Now run the basic test that uses the Mocha/Chai framework, navigate to the app folder inside the app folder run 'npm test':

```
cd app
npm test
```

#### Authors

**Mahan Jahromi** - *DevOps Engineer* - [Mahansparta](https://github.com/Mahansparta)

#### Acknowledgments

* Hat tip to anyone whose helped me with this Project
* Inspiration  - Filipe Paiva
