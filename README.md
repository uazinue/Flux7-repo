# Flux7-repo
-  

   - name: paly 1
     host: localhost
     tasks:
        - name: Install hhtp service
          yum:
            name: httpd
            state: present


   - name: start web server
     service:
         name: httpd
         state: started  
