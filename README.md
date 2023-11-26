#Exercici 1
int main(){
  int i,j;
  i = 1;
  j = 2;
  i++;
  j += i;
  return0;
}

#Exercici 2
int main() {
    short i, j;
    i = 1;
    j = 2;
    i++;
    j += i;
    return 0;
}

#Exercici 3
int main(){
  int a,b,c,d;
  a = 1;
  b = 2;
  c = 3;
  d = 4;
  a = b+c*d;
  a = (b+c)*d;
  d = a;
  return 0;
}

#Exercici 4.1
int main(){
  int prod;
  int n = 3;
  char cad = 'a';
  prod = cad*n;
}

#Exercici 4.2
int main(){
  char prod;
  int n = 3;
  char cad = 'a';
  prod = cad*n;
}

#Exercici 5
int main(){
  char a[3];
  a[0] = 1;
  b[1] = 2;
  c[2] = 3;
  return 0;
}

#Exercici 6
int main(){
  int a[] = {1, 2, 3, 4};
  int b[] = {5, 6, 7, 8};
  int c[4];
  int i;
  for (i = 0; i<4; ++i){
    c[i] = a[i] * b[i];
  }
}

#Exercici 7
int main(){
  int i,a[20];
  for (i = 0; i<20; i++){
    a[i] = i*4;
  }
  returnt 0;
}
