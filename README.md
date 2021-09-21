# vazifalar_

//ikki sonning kattasini topish
#include<iostream>

using namespace std ;

int main(){
	
	int a , b ;
	cout <<"a=";
	cin >> a ;
	cout <<" b =";
	cin >> b ;
	cout <<(a*(a>b) + b*(a<b));
	return 0;
}
                              
                              
                              
// vaqt , tezlik , yo'l masalasi
    
 #include<iostream>

using namespace std ;

int main (){
	float s , t , v ;
	cout << "s = " ;
	cin>> s ;
	cout << "t = ";
	cin>> t ;
	v = s / t ;
	cout << " v = " << v ;
	return 0;
}
    
    
    // 4 xonali sonning raqamlar yig'indisini topish
                   
      #include<iostream>

using namespace std ;

int main(){
	int a , b , s , d , e ,f ;
	cout << " a = ";
	cin >>  a ;
	b = a / 1000 ;
	s = (a / 100) - b*10;
	d = (a / 10) - (s*10 + b*100);
	e = (a % 10) ;
	f = b + s + d + e ;
	cout << " f = "<< f ;
	return 0 ;
}
  
  
  

                              
                              
                              
