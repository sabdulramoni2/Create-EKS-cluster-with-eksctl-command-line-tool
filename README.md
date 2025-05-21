# Create-EKS-cluster-with-eksctl-command-line-tool

## **Project Overview**
This shows the command use to create EKS cluster on the CLI. 

---
  
## **Feature**

### **Creates EKS IAM role**
 - Install eksctl tool. (choco install eksctl – Windows).
 - Configure AWS credentials.
 - Create cluster using
   ```
      eksctl create cluster –name –version –region –nodegroupname –node-type –node –nodes-min –node-max
   ```
 - Also, you can create a yaml with all these parameters and run; eksctl create cluster -f file. yaml.
