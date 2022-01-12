# Fornax Bash Scripts for Deployment

### 1. Clone the repository into Node-A, Node-B, Node-C
git clone https://github.com/click2cloud-prajwal/fornaxscript.git

### 2. Edit the IP's in all the Three scripts:
#### export a= (IP address of node-a)
#### export b= (IP address of node-b)
#### export c= (IP address of node-c)

### 3. Run the Script:
#### sudo bash fornaxscript/fornax1.sh 
#### (for node-a run the 'fornax1.sh', Simultaneously run the 'fornax2.sh' for node-b and 'fornax3.sh' for node-c)
  
### 4. Verify the Edgecluster in Node-A:
#### kubectl get edgecluster

