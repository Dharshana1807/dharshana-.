OTP GENERATOR
import random

def generate_otp(length=6):
    digits = "0123456789"
    otp = "".join(random.choices(digits, k=length))
    return otp

# Example usage
otp = generate_otp()
print("Your OTP is:", otp)
