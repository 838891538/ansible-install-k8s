# Kubernetes 高可用自动部署（离线版）
>### 确保所有节点的系统时间一致
>### ansible all -m shell -a "ntpdate ntp1.aliyun.com"

### 1、下载所需文件

下载Ansible部署文件：

```
git clone https://github.com/838891538/ansible-install-k8s.git
cd ansible-install-k8s
```
