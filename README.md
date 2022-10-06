# Connect to the actuated-ssh-gateway

This GitHub Action sets up the actuated SSH gateway.

```yaml
  - name: Connect to the actuated SSH gateway
    uses: alexellis/actuated-ssh-gateway-action@master
    with:
      sshGatewayAddr: ${{ secrets.SSH_GATEWAY_IP }}
      secure: true
```
