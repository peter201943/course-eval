
# Installation

## 1. [Download Git](https://git-scm.com/downloads)

## 2. [Download Vagrant](https://www.vagrantup.com/downloads)

## 3. [Download VirtualBox](https://www.virtualbox.org/wiki/Downloads) or an equivalent compatible Virtual Machine System

## 4. Cleanup Line Endings (Windows Only)
    
Make sure you are in the `team-blue` directory and can see the `.git` directory before running this command.

```bash
git config core.autocrlf input
```

## 5. Launch Git Bash with Administrative Privileges (Windows Only) for any following commands

## 6. Clone the Team Repo
```bash
git clone --recurse-submodules git@gitlab.cci.drexel.edu:courseeval/team-blue.git se420-team-blue
```

## 7. Navigate to the EvaP Directory
```bash
cd se420-team-blue
cd EvaP
```

## 8. Activate Vagrant (and Apply Updates)
```bash
vagrant up
```

## 9. Activate Vagrant Connection
```bash
vagrant ssh
```

## 10. Launch the Server
```bash
./manage.py run
```

## 11. Access the Website  
Open a browser to: http://localhost:8000/  
login with:  
```yaml
email:    evap@institution.example.com
password: evap
```

## NOTE
[Read E-Valuation's README](https://github.com/e-valuation/EvaP/#installation) and [Installation Guide](https://github.com/e-valuation/EvaP/wiki/Installation) before beginning but ***DO NOT FOLLOW THEIR STEPS*** (Their steps download to a separate folder and will create problems later when you go to install).

