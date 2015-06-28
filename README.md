# Even-Fibonacci-Numbers

    int num = 1, temp=1, sum = 0, esum=0, max = 4000000;
    
    while (sum <= max)
    {
        sum = num + temp;
        
        if (sum%2==0)
            esum += sum; // total of all even numbers below total
        
        num = temp;
        temp= sum;
    }
    
    cout<< esum;
    
    system ("PAUSE");
    return 0;
}
