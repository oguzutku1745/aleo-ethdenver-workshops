## Compliance with Private Installments:
- Record Installment holds the amount to pay each mont
- Transition init_installment takes the owner, the total payment amount and the months to pay and calculates the amount to pay each mont. Returns this record
- Async/await pay_installment transition:
    1. Updates the installment record for the user by updating the month
    2. Sends the amount_to_pay parameter to receiver privately
    3. Returns the updated installment record
    4. Awaits for the transfer

Deployment ID: at19d2zyk474pwrqpyt36tfn6gsc3yv2q26lqt7uys9jr3twemmfygqgkct0q
