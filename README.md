# Find-how-many-1-s-in-an-binary-of-integer-bit-manipualtion



       int a = 9;
       int count=0;
       for(int i=0; i<32; i++)
       {
         if(   ((a>>i) &1) ==1)
         {
           count++;
         }
       }
    
       System.out.println(count);
       
