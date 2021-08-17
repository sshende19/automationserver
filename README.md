# automationserver
1) Run Docker-compose up -d
# login to ansible containter
2) docker exec it ansible /bin/bash
# Need to create inventory to run ansible playbook 
3) vi inventory
      [All]
      server1
      server2
# need to check whether servers are pinging from ansible server.
4) ansible -i inventory -m ping

