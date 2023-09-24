#Introduction To Subnet

        region: us-east-1
        #count: 1
        exact_count: 2
        count_tag: {type: http}
        filters:
        
          "tag:type": http
        vpc_subnet_id: subnet-75cb9912
        network:
          assign_public_ip: true
