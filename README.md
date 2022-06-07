# snail
https://code.im.ncnu.edu.tw/problem/1101practise1
```python
def main():
	h=int(input())
    d=int(input())
    n=int(input())
    while True:
        day=0#紀錄目前到第幾天
        high=0 #紀錄目前
        while True:
            day+=1
            high+=d
            if high>=h or high<=0:
                break
            high-=n
        if high>=h:
            print(day)
            break
main()
    
    
    
