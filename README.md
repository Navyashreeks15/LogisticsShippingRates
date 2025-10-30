# Simple Interest Formula: SI = (P × R × T) / 100

def calculate_simple_interest(principal, rate, time):

    interest = (principal * rate * time) / 100
    return interest
    
P = 1000  
R = 5    
T = 2     

SI = calculate_simple_interest(P, R, T)

print(f"Simple Interest = {SI}")
