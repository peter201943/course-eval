
# Installation

## 1. [Download Git](https://git-scm.com/downloads)

## 2. [Download Vagrant](https://www.vagrantup.com/downloads)

## 3. [Download VirtualBox](https://www.virtualbox.org/wiki/Downloads) or an equivalent compatible Virtual Machine System

## 4. Launch Git Bash with Administrative Privileges (Windows Only) for any following commands

## 5. Clone the Team Repo
```bash
git clone --recurse-submodules git@gitlab.cci.drexel.edu:courseeval/team-blue.git se420-team-blue
```

## 6. Navigate to the Project Directory
```bash
cd se420-team-blue
```

## 7. Cleanup Line Endings (Windows Only)
    
```bash
git config --global core.autocrlf input
git config --list # make sure the "core.autocrlf=input", if not, DO NOT CONTINUE!
```

## 8. Navigate to the EvaP Directory
```bash
cd EvaP
```

## 9. Activate Vagrant (and Apply Updates)
```bash
vagrant up
```
While this is running, also open the VirtualBox manager app and click "Show" to open the terminal.  
***KEEP THIS WINDOWN OPEN***, the installation can stall if you do not.  

## 10. Activate Vagrant Connection
```bash
vagrant ssh
```

## 11. Launch the Server
```bash
./manage.py run
```

## 12. Access the Website  
Open a browser to: http://localhost:8000/ and login with:  
```yaml
email:    evap@institution.example.com
password: evap
```

## NOTICE
Read E-Valuation's [README](https://github.com/e-valuation/EvaP/#installation) and [Installation Guide](https://github.com/e-valuation/EvaP/wiki/Installation) before beginning but ***DO NOT FOLLOW THEIR STEPS***

Their steps download to a separate folder and will create problems later when you try to commit merges to the project.

