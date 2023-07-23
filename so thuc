#include<iostream>
using namespace std;
class SoThuc {
	private: 
	   int TuSo , MauSo ;
	public: 
	   SoThuc();
	   void Nhap();
	   void Xuat();
};
SoThuc::SoThuc(){
	cout<<"\n ham khoi tao so thuc duoc goi !";
}
void SoThuc::Nhap(){
	cout<<"\n nhap tu so : ";
	cin>>TuSo;
	cout<<"\n nhap mau so : ";
	cin>>MauSo;
	while(MauSo<=0){
		cout<<"\n moi ban nhap lai mau so : ";
		cin>>MauSo;
	}
}
void SoThuc::Xuat(){
    cout<<"\n so thuc duoc xay dung la : "<<(float)TuSo/MauSo<<endl;
}
int main(){
	SoThuc x;
	x.Nhap();
	x.Xuat();
	return 0 ;
}
