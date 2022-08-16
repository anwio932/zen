# zen
https://www.interviewzen.com/interview/d7313055-6d84-4309-9613-f51f7c414773

Question 1: What type of kind resource you will use to store sensitive data in the Kubernetes cluster?
Answer:    In Kubernative cluster, the kind of resource I will use to store sensitive data is API Authentication. I am using API authentication because sensitive                 information will need password and other ways of authenticating different users for different roles and responsibilities.

Question 2: Which is the intended use for etcd?
Answer:     In kubernetes etcd is used to store data.

Question 3: Write a command to access the pod shell from your terminal.
Answer:     kubectl get pod

Question 4: Can we use many claims out of a persistent volume?
Answer :    No, it is always one to one.

Question 5: You need to squish your merge request commits (you did 10 of them) to one. Write down all steps (commands)
Answer:     git fetch origin master
         git merge --squash
         git commit
         git push origin
     
Question 6: How to monitor the Kubernetes cluster? You can name a few examples
Answer:     I can monitor the kubernetes cluster using Grafana, Prometheus, Heapster and ELK Stack.

Question 7: The kernel installation process broke while updating the system. After rebooting the machine, it goes into a panic kernel.
         What can you do?
Answer:    I will restart the system for this will correct kernel panic.

Question 8: You need to set up a file to a read-only state, even for root. How you can achieve this (write down a command)?
Answer:     chmod 0444

Question 9: Your machine consumes a lot of resources. You have also a problem with slow disks. 
         What typical commands you will use to check CPU, ram, disk IOPS and used disk space?
Answer:     The typical commands I will use to check CPU, ram, disk, IOPS and disl space are lscpu, nproc, top, free -m, and lsblk

Quest 10: What are the advantages that Containerization provides over virtualization?
Answer:      The advantages of containerization are it is faster, easy to automate and manage and is more light weight than virtualization.

Question 11: (optional) Which default file is used to pass the values in Helm Chart?
Answer:      The default file used to pass the values in Helm chart is yaml file.
