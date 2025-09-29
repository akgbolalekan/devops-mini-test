create a vpn Tunnel to in aws and connect with the following configurations

- region: us-east-1
- aws ec2 create-vpn-connection 
- --t 
- --transit-gateway-id tgw-12312312312312312 
- --customer-gateway-id cgw-001122334455aabbc
-  --options OutsideIPAddressType=IPv6,TunnelInsideIpVersion=ipv6,TunnelOptions=[{StartupAction=start},{StartupAction=start}]
