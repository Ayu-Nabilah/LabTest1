# total bit in given number 
def countBits(number): 
    if (number==0):
        return 0
    else:
        return (number&1) + countBits(number>>1); 
  
# num given 
num = 1; 
print(countBits(num));
