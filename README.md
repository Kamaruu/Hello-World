# Hello-World
Tips to make the loop work


#include <iostream>
#include <stdlib.h>




using namespace std;

string Nombre, Direccion, conf;

int Telefono, Pasillo, lacteos, bebidas, vegetales, snacks, limpieza, reposteria;
	



int main() {
	 
	
	cout<<"\t\t\tBienvenido al Almacen"<<endl<<endl;
	cout<<"Nombre: ";
	cin>>Nombre;
	cout<<"Telefono: ";
	cin>>Telefono;
	cout<<"Direccion: ";
	cin>>Direccion;
	system("cls");
	

	do{
		cout<<"Elija el pasillo donde desea comprar. "<<endl<<endl;
		cout<<"1)Lacteos"<<endl<<"2)Bebidas"<<endl<<"3)Vegetales"<<endl<<"4)Snacks"<<endl<<"5)Limpieza"<<endl<<"6)Reposteria"<<endl<<endl;
		cin>>Pasillo;
		system("cls");
		
	
			if (Pasillo=1){
			cout<<" Lacteos\n\n ";
			cout<<"Elija el producto que desee."<<endl<<endl;
			cout<<"1)Leche\n""2)Queso\n""3)Yogurt\n\n";
			cin>>lacteos;
			cout<<"\n";
			
			if(lacteos>=1 or lacteos<=3){
				cout<<"Desea seguir comprando o desea facturar?\n";
				cin>>conf;
				system ("cls");
				
				if (Pasillo==2){
					cout<<" Bebidas\n\n";
					cout<<"Elija el producto que desee\n\n";
					cout<<"1)Jugo\n""2)Refresco\n""3)Whisky\n\n";
					cin>>bebidas;
					cout<<"\n";
				
					
					
					if(bebidas>=1 or bebidas<=3){
						cout<<"Desea seguir comprando o desea facturar?";
						cin>>conf;
						system ("cls");
						
							if (Pasillo=3){
							cout<<" Vegetales\n\n ";
							cout<<"Elija el producto que desee\n\n";
							cout<<"1)Lechuga\n""2)Tomate\n""3)Zanahoria\n\n";
							cin>>vegetales	;
							cout<<"\n";
							
							
							if(vegetales>=1 or vegetales<=3){
								cout<<"Desea seguir comprando o desea facturar?\n\n";
								cin>>conf;
								system ("cls");
								
								if (Pasillo=4){
									cout<<" Snacks\n\n ";
									cout<<"Elija el producto que desee\n\n";
									cout<<"1)Galleta\n""2)Papitas\n""3)Tostitos";
									cin>>snacks;
									cout<<"\n";
									
									
									if(snacks>=1 or snacks<=3){
										cout<<"Desea seguir comprando o desea facturar?\n\n";
										cin>>conf;
										system ("cls");
										
										if (Pasillo=5){
											cout<<" Limpieza\n\n ";
											cout<<"Elija el producto que desee\n\n";
											cout<<"1)Cloro\n""2)Escoba\n""3)Recogedor\n\n";
											cin>>limpieza;
											cout<<"\n";
											
											
											if(limpieza>=1 or limpieza<=3){	
												cout<<"Desea seguir comprando o desea facturar?\n\n";
												cin>>conf;
												system ("cls");
												
												if (Pasillo=6){
													cout<<" Reposteria\n\n";
													cout<<"Elija el producto que desee\n\n";
													cout<<"1)Harina\n""2)Vainilla\n""3)Crema Batida\n\n";
													cin>>reposteria;
													cout<<"\n";
													
													
													if(reposteria>=1 or reposteria<=3){
														cout<<"Desea seguir comprando o desea facturar?\n\n";
														cin>>conf;
														system ("cls");
		
		
													}
												}
											}
										}
									}
								}
							}
						}
					}
				}
			}
		}
		}while(conf!="no");
		system("cls");
		
							cout<<"Facturacion\n\n";
								
					cout<<Nombre<<endl;
					cout<<Telefono<<endl;
					cout<<Direccion<<endl;
