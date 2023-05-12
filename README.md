# Connect to the actuated-ssh-gateway

This GitHub Action sets up the actuated SSH gateway.

```yaml
  - name: Connect to the actuated SSH gateway
    uses: self-actuated/connect-ssh-gateway@master
    with:
      sshGatewayAddr: ${{ secrets.SSH_GATEWAY }}
      secure: true
```
