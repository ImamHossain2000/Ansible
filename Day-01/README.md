<h3> Ansible Architecture </h3>

![33ympesmiwld52do90ji](https://github.com/imamhossain2000/Ansible/assets/42093881/ff925abf-9e49-4b62-97a6-b91134c9740b)

<h3>Install Ansible in Ubunt</h3>

<ul>
  <li>sudo apt-add-repository ppa: ansible/ansible
</li>
  <li>
    sudo apt update
  </li>
  <li>
    sudo apt install ansible -y
  </li>
  <li>
    ansible --version
  </li>
</ul>


![5 -Check-Ansible-version](https://github.com/imamhossain2000/Ansible/assets/42093881/83435312-9a1e-4563-97e9-29857abe44a7)


<h3>Set up an SSH Key pair</h3>
<ul>
  <li>ssh-keygen</li>
  <li>ssh-copy-id [username]@[remote-host]</li>
  <li>ssh-copy-id ansible@192.168.0.81</li>
</ul>

![7 Target-Machine-ssh-copy-id](https://github.com/imamhossain2000/Ansible/assets/42093881/96e160d6-0786-41c8-81e7-bd15c7072f0d)
