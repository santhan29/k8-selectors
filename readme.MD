# selectors
TO taint the node command is :
    kubectl taint nodes ip-192-168-1-48.ec2.internal hardware=gpu:NoSchedule 

Label Node 
    kubectl label nodes ip-192-168-13-90.ec2.internal hardware=gpu 