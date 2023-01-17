# Python_Workshop

## 교재(강의자료)_python_02_실습

- break
    
    ```python
    n=0
    while True:
        if n == 3:
            break
        print(n)
        n += 1
    '''
    0
    1
    2
    '''
    ```
    
    ```python
    for i in range(10):
        if i > 1:
            print('0과 1만 필요해!')
            break
        print(i)
    '''
    0
    1
    0과 1만 필요해!
    '''
    ```
    
- continue
    
    ```python
    for i in range(6):
        if i % 2 == 0:
            continue
        print(i)
    '''
    1
    3
    5
    '''
    ```
    

## Python 02. 데이터 타입 및 형 변환

1. 숫자의 입력과 출력
    
    ```python
    print(int(input()) + int(input()))
    '''
    6374            // 입력
    8729            // 입력
    15103           // 출력
    '''
    ```
    
2. Dictionary를 활용하여 평균 구하기
    
    ```python
    dc = {}
    cnt = 0
    while True:
        menu = input("Type Menu : ")
        price = int(input("Type Price(Type 0 to exit) : "))
        if price == 0:
            break
        dc[menu] = price
    print(f"평균 가격은 {sum(dc.values())/len(dc)}원 입니다")
    ```
    

ㄴ> toggle

- 
    
    ```markdown
    ## 교재(강의자료)_python_02_실습
    
    - break
        
        ```python
        n=0
        while True:
            if n == 3:
                break
            print(n)
            n += 1
        '''
        0
        1
        2
        '''
        ```
        
        ```python
        for i in range(10):
            if i > 1:
                print('0과 1만 필요해!')
                break
            print(i)
        '''
        0
        1
        0과 1만 필요해!
        '''
        ```
        
    - continue
        
        ```python
        for i in range(6):
            if i % 2 == 0:
                continue
            print(i)
        '''
        1
        3
        5
        '''
        ```
        
    
    ## Python 02. 데이터 타입 및 형 변환
    
    1. 숫자의 입력과 출력
        
        ```python
        print(int(input()) + int(input()))
        '''
        6374            // 입력
        8729            // 입력
        15103           // 출력
        '''
        ```
        
    2. Dictionary를 활용하여 평균 구하기
        
        ```python
        dc = {}
        cnt = 0
        while True:
            menu = input("Type Menu : ")
            price = int(input("Type Price(Type 0 to exit) : "))
            if price == 0:
                break
            dc[menu] = price
        print(f"평균 가격은 {sum(dc.values())/len(dc)}원 입니다")
        ```
    ```