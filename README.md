Script for port forwarding

cp qemu /etc/libvirt/hooks/qemu

cp server_port_map /etc/libvirt/hooks/server_port_map

chmod +x /etc/libvirt/hooks/qemu

Edit hostif and optional hostip variables (read the comment above the variable) in /etc/libvirt/hooks/qemu

Edit /etc/libvirt/hooks/server_port_map

vm_name;remote_ip;remote_port;vm_ip;local_port
