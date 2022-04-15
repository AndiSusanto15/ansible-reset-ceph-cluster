# Playbook Reset Ceph Cluster

## Background Story
[Adinusa](https://adinusa.id/) bootcamp purpose.

## How to use

- Set up passwordless to another machine
- Install ansible in `pod-<username>-ceph1` 
    ```
    sudo apt install ansible
    ```
- Clone this repo
- Prepare inventoy file `hosts.ini`
- Check file `playbook.yml`
- Run command
    ```
    ansible-playbook playbook.yml
    ```

&copy; [Andi Susanto](https://jurnal.batutah.id)
