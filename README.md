## Steps for Playbook Execution
#### Prerequisites
Please make sure the following applications are installed before playbook execution:
1. [Homebrew](https://brew.sh/)
2. Ansible `brew install anisble`

**Step 1**

Pull down the requirements by executing the requirements.yml file using anisble-galaxy
```
ansible-galaxy install -r requirements.yml
```

**Step 2**

Execute the playbook.yml file using ansible-playbook
```
anisble-playbook playbook.yml
```
