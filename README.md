# Connect to the actuated-ssh-gateway

This GitHub Action sets up the actuated SSH gateway.

```yaml
  - name: Setup SSH server for Actor
    uses: alexellis/actuated-ssh-gateway-action@master
    with:
      sshGatewayAddr: ${{ secrets.SSH_GATEWAY_IP }}
      secure: true
```
