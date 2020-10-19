# ansible-task4.2-class
Clone https://github.com/ikambarov/spring-petclinic.git

Install the app on CentOS and Ubuntu VMs
Make sure web site is accessible at public IP over port 8080

Use:
  -Roles
  
    Roles:
    -Prerequisites
        Installs vim, wget, git, unzip, openjdk, maven
    -Java
        Installs openjdk, maven
    
   o Installs multiple versions of OpenJDKRoles should be generic, and should work on both CentOS and Ubuntu
   
   Hint: ojdk_8_Deb: openjdk-8-jre
         ojdk_8_RH: java-1.8.0-openjdk
