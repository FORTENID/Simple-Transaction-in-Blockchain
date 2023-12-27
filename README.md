# Simple-Transaction-in-Blockchain
Adding a basic transaction to a block.
class Transaction:
    def __init__(self, sender, recipient, amount):
        self.sender = sender
        self.recipient = recipient
        self.amount = amount

def create_transaction(sender, recipient, amount):
    return Transaction(sender, recipient, amount)

# Example usage
transaction = create_transaction("Alice", "Bob", 5)
