### Subscription Workflow:
1. **Invoke `register_service`**: Merchant defines the plan (e.g., 1 Pi / 30 days).
2. **Invoke `subscribe`**: 
    - Contract calls `transfer_from` to move the first period's payment.
    - Contract sets a `token_allowance` for the next 12 periods.
3. **Data Storage**: Subscription details (ID, expiry, auto-renew status) are saved on-chain.
