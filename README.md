# -Contiguous-Alphabets-Curly-Braces
 Contiguous Alphabets &amp; Curly Braces
 //Algorithm for applying braces for continuous alphabets in a string
 #include<stdio.h>
 int main(){
     char str[100];
     scanf("%d",s);
     int start=end=0;
       for(int i=1;i<strlen(str);i++){
            if(toLower(str[i])==toLower(str[i-1])+1){
              end++;
            }
            else{
               printf("{");
               for(int j=start;j<=end;j++)
                  printf("%c",str[j]);
               printf("}");
               start=end=i;
            
            }
       
       
       }
 
 
 
 }
