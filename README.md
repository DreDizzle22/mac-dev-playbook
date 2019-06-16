## Steps for Playbook Execution
#### Prerequisites
Please make sure the following applications are installed before playbook execution:
1. [Homebrew](https://brew.sh/)
2. Ansible 
Run `brew install anisble`

**Step 1**

Pull down the requirements by executing the requirements file using anisble-galaxy
```
ansible-galaxy install -r requirements.yml
```

**Step 2**

Execute the playbook.yml file
```
anisble-playbook playbook.yml
```
