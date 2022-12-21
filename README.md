
# Ujian Akhir Semester 
Mata Kuliah 	: Dasar Pemrograman
<br>Nama		: Rizkco Fauzan Adhim
<br>NIM		:	1227050117
<br>Jurusan		: [Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum
<br>

## Source Code
    #include <iostream>
    #include <conio.h>
    #include <iomanip>
    #include <stdlib.h>
    using namespace std;
    int main()
    {
      int Mat[100][100];
        int i,j,k, baris, kolom;

            system("cls");
            cout<<"========================="<<endl;
          cout<<"Nama: Rizkco Fauzan Adhim"<<endl;
          cout<<"========================="<<endl;
          cout<<"No 1, Transpose Nilai Matriks"<<endl;
            cout << "Masukkan banyak baris matriks : ";
            cin >> baris;
            cout << "Masukkan banyak kolom matriks : ";
            cin >> kolom;

        //membaca elemen-elemen matriks 
           for (i=0;i<baris;i++){
            for (j=0;j<kolom;j++){
                cout << "Baris "<<i+1<<", Kolom "<<j+1<< " = ";
                cin >> Mat[i][j];
            }
        }cout <<endl;

        //Mencetak elemen 
        cout<<"Bilangan Normal"<<endl;
      cout<< "\nMatriks ("<<baris<<"x"<<kolom<<")\n";
        for (i=0;i<baris;i++){
            for (j=0;j<kolom;j++){
                cout <<Mat[i][j]<<" ";
            }
            cout <<endl;
        }
        cout<<endl<<"Hasil yang ditukar"<<endl;
        cout << "\nMatriks ("<<baris<<"x"<<kolom<<")\n";
          for (i=0;i<kolom;i++){
            for (j=0;j<baris;j++){
                cout <<Mat[j][i]<<" ";
            }
            cout <<endl<<endl;
        }

        cout << "2. Bilangan yang habis di bagi 3,5,7: "<<endl<<endl;
      for (int i = 0; i < kolom; i++){
      for (int j = 0; j < baris; j++){
      if (Mat[i][j] % 3 == 0|| Mat [i][j] % 5 ==0||Mat [i][j] %7 ==0) cout << Mat[i][j] << ", "; // Mencetak bilangan yang habis di bagi 3
      }
    }

        return 0;
    }

    ## Output
