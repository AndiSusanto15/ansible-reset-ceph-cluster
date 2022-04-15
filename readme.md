# Playbook Reset Ceph Cluster

## Background Story
[Adinusa](https://adinusa.id/) bootcamp purpose.

## How to use

- Run with user `ceph-adm`
- Set up passwordless to another machine
- Install ansible in `pod-<username>-ceph1` 
    ```
    sudo apt install ansible
    ```
- Clone this repo
- Prepare inventoy file `hosts.ini`
- Adjust file `playbook.yml`
    - Rename every string `pod-batutah.id` with yours.
- Run command
    ```
    ansible-playbook playbook.yml
    ```

&copy; 2022 [Andi Susanto](https://jurnal.batutah.id)
