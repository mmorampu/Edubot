# GCP Setup

## Steps to Create a GCP Account and Deploy a Python Script

1. Go to [Google Cloud Console](https://console.cloud.google.com/).
2. Create a Google Compute Engine instance.
3. SSH into the instance.
4. Install Python if needed.
5. Create a Python script (e.g., `add_numbers.py`):
```python
    def add_numbers(a, b):
        return a + b

    if __name__ == "__main__":
        print(add_numbers(7, 8))