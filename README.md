# ALGO-9.TUGAS-7

## CODINGAN LENGKAP

    #include <stdio.h>

    void cetak_mundur(char S[]){
    int i,n;
    for(n=0;n<S[n];n++);
    printf("panjang array = %d\n",n);
    for(i=n-1;i>=0;i--){
        printf("%c",S[i]);
    }

    }
    int main(){
    char str[50]="anton";
    cetak_mundur(str);

    }
## HASIL PROGRAM
![img](https://github.com/dindapuspitadewi/ALGO-9.TUGAS-7/blob/master/tugas%207.png?raw=true)
