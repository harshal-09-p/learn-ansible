# learn-ansible

In YAML

key: value      ( Normal ) 

key:        ( List ) 
    - value1 
    - value2 
    
key:        ( Map ) 
    key1: value1 
    key2: value2


-   Keys are provided by Ansible
-   Values are provided by us
-   Some values are even provided by Ansible

# Now the variable precedence will come into picture
# 1. Command line level
# 2. Task level
# 3. Roles Level
# 4. Play Level
# 5. Inventory level
# 6. Error saying variable does not declared