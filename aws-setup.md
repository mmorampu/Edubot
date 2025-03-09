# AWS Setup

## Steps to Create an AWS Account and Deploy a Python Script

1. Go to [AWS Console](https://aws.amazon.com/console/) and create an account.
2. Launch an EC2 instance.
3. SSH into the instance.
4. Install Python if not already available.
5. Create a Python script (e.g., `add_numbers.py`):
```python
    def add_numbers(a, b):
        return a + b

    if __name__ == "__main__":
        print(add_numbers(3, 4))