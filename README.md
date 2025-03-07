# myprojects
A simple Docker Compose to install WordPress, mySQL, phpMyadmin

 networks:   
  overlay2:
  name: myproject 


The overlay network driver is primarily used in Docker Swarm mode to enable communication between containers running on different Docker hosts. It allows you to create a multi-host network, which is useful for scaling applications across multiple machines.