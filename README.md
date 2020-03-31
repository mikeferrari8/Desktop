# Desktop
This is a rudimentary ansible playbook that will install all of the apps and configuration settings i prefer on my linux desktop. I am always spinning up new laptops and VM's for various reasons and wanted to make an "immutable" setup. I build a "box" and poof all my apps configs and files are setup and synchronized. This is just to get started, eventually i will create roles etc

### Assumptions
1. You start with a Centos 8 "Minimal" install.
2. You like your desktop like i like mine :-)

### Applications
`@Workstation  
@Gnome Applications  
@Internet Applications  
@Remote Desktop Clients  
@Office Suite and Productivity  
libreoffice-base  
@Container Management  
@Development Tools  
@Graphical Administration Tools  
gnome-disk-utility  
wireshark  
@System Tools  
mc  
gnome-tweaks  
cockpit-podman  
cockpit-machines  
cockpit-dashboard`  

#### Eventually
`atom  
gsettings stuff (maybe copy the dconf db?)  
rsync my directory of files off my home server (backed up to google drive/dropbox)`  

And then execute the command to make the gnome desktop the default  
`systemctl set-default graphical.target`  
  
