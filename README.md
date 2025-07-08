# 🔷 Azure HPC Cluster

This project demonstrates how to build a high-performance computing (HPC) cluster using Azure virtual machines and Slurm workload manager. The cluster consists of 1 head node and 2 compute nodes configured on Ubuntu.

---

## ⚙️ Architecture

- ☁️ **Platform**: Microsoft Azure
- 💻 **Nodes**:
  - Head Node: 192.168.1.23
  - Compute Node 1: 192.168.1.24
  - Compute Node 2: 192.168.1.25
- 🛠️ **Technologies**:
  - Ubuntu 20.04 LTS
  - Slurm Workload Manager
  - NFS (Network File System)
  - SSH key-based authentication

---

## 📦 Features

- Configured private IPs and internal DNS resolution
- NFS shared storage between head and compute nodes
- SSH key-based access across the cluster
- Installed and configured Slurm job scheduler
- Benchmarked with:
  - ✅ HPL
  - ✅ LAMMPS
  - ✅ MILC
  - ✅ MATLAB Optimization

---

## 🧪 Usage

1. Provision VMs on Azure with static IPs
2. Install Slurm and dependencies
3. Configure NFS mount and exports
4. Enable SSH key auth across nodes
5. Submit test jobs using `sbatch`

---

## 👨‍💻 Author

**Jeffrey Nkadimeng**  
💼 Cloud | HPC | Cybersecurity | ServiceNow  
🔗 [LinkedIn](https://www.linkedin.com/in/jeffrey-nkadimeng-b58987319)

---

## 📄 License

MIT – feel free to use or modify this setup.
