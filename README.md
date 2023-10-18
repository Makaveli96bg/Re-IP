# Work in progress...


---

Right now there is working vpc ready to go with 2 instances of asav 9.19.1
two subnets /28 for asav's 
three subnets for TG attachments 
EIP attached to outside interface on asavOne (public_ip => Outside interface)

> nic schema dew to /28 block <br/>
> .42 => outside <br/>
> .26 => inside <br/>
> .10 => mgmt

- [x] add subnets for outside & inside
- [x] make cloud formation more robust
- [ ] add param for ssh-key
- [x] add more comments
- [ ] add routes necessary for production ?
- [ ] solve potential issues from CloudOps & Network Team
