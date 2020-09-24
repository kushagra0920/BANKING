#include<iostream.h>                      //Header file declared here
#include<ctype.h>
#include<process.h>
#include<time.h>
#include<stdio.h>
#include<string.h>
#include<math.h>
#include<stdlib.h>
#include<iomanip.h>
#include<conio.h>
#include<dos.h>
#include<fstream.h>
#define bn "ARTHA CONSOLIDATE"
#define fl "dfile.dat"
#define f1 "tra_file.txt"


typedef  double var;                            //Double defined as var here
void rancob();                                  //Function declartion
void normal();

void cprintfc(char a[])
{
	rancob();
	cprintf("%s",a);
	normal();
}

void animation()                          //Function to ontrol animation
{
	const int n=10;
	for(int i=0;i<n/2;i++)
	{
		textcolor(i);
		textbackground(1);
		gotoxy(27,9);cprintf("TRANSACTION \n OF \n MONEY");
		textbackground(0);
		textcolor(15);
		for(int j=0;j<n-i;j++)
			{
			gotoxy(20,12+(n/2)-j);
			textbackground(2);
			cprintf("1000 INR");
			textbackground(0);
			}
		for(j=0;j<=i;j++)
		{
			gotoxy(50,12+(n/2)-j);
			textbackground(2);
			cprintf("1000 INR");
			textbackground(0);
		}
		for(j=0;j<26;j++)
		{
			textcolor(0+BLINK);
			gotoxy(24+j,13-(n/2)+i);
			textbackground(2);
			cprintf("1000 INR");
			textbackground(0);
			delay(30);
			gotoxy(1,13-(n/2)+i);clreol();
			textcolor(2);
		}
		delay(60);
		clrscr();
		textbackground(0);
	}


}


void welcome()                                //Function displaying welcome message in the beggining of program
{
	for(int i=0;!kbhit();i++) //kbhit() for haulting till key stroke;
	{
	textcolor(i);
	gotoxy(15,8);cprintf("ÛÛ       ÛÛ");
	gotoxy(15,9);cprintf("ÛÛ       ÛÛ");
	gotoxy(15,10);cprintf("ÛÛ       ÛÛ  ÛßßßÛ Û     ÛßßßÛ  ÛßßßßÛ  ÛÛ   ÛÛ  ÛßßßÛ");
	gotoxy(15,11);cprintf("ÛÛ       ÛÛ  Û     Û     Û      Û    Û  Û Û Û Û  Û");
	gotoxy(15,12);cprintf("ÛÛ   Û   ÛÛ  ÛÜÜÜ  Û     Û      Û  Û Û  Û  Û  Û  ÛÜÜÜ");
	gotoxy(15,13);cprintf("ÛÛ  Û Û  ÛÛ  Û     Û     Û      Û  Û Û  Û     Û  Û");
	gotoxy(15,14);cprintf("ÛÛ Û   Û ÛÛ  Û     Û     Û      Û    Û  Û     Û  Û");
	gotoxy(15,15);cprintf("ÛÛÜÜ   ÜÜÛÛ  ÛÜÜÜÛ ÛÜÜÜÛ ÛÜÜÜÛ  ÛÜÜÜÜÛ  Û     Û  ÛÜÜÜÛ");
	gotoxy(16,18);cprintf("                   PRESS A KEY TO CONTINUE                  ");
	if(i==15)
		i=0;
	}
}
void pro_name()                       //Function displaying name of topic,and submitted to nd submitted by
{
	for(int i=0;!kbhit();i++) //kbhit() for haulting till keystroke
	{
		textcolor(i);
		gotoxy(10, 4);cprintf("ÛÛÛÛÛÛÛ                                       ");
		gotoxy(10, 5);cprintf("ÛÛ     ÛÛ                                     ");
		gotoxy(10, 6);cprintf("ÛÛ     ÛÛ  ÛßßßÛ ÛÛ    Û  Û   Û              ");
		gotoxy(10, 7);cprintf("ÛÛÛÛÛÛÛÛ   Û   Û Û Û   Û  Û  Û               ");
		gotoxy(10, 8);cprintf("ÛÛ     ÛÛ  Û ßßÛ Û  Û  Û  Û Û                ");
		gotoxy(10, 9);cprintf("ÛÛ     ÛÛ  Û   Û Û   Û Û  Û  Û               ");
		gotoxy(10,10);cprintf("ÛÛÛÛÛÛÛ    Û   Û Û    ÛÛ  Û   Û              ");

		gotoxy(10,12);cprintf("ÛÛÛ    ÛÛÛ                                                         ");
		gotoxy(10,13);cprintf("ÛÛ Û  Û ÛÛ                                                         ");
		gotoxy(10,14);cprintf("ÛÛ  ÛÛ  ÛÛ ÛßßßÛ ÛÛ    Û ÛßßßÛ ÛßßßÛ ÛÛÛ ÛÛ   ÛÛ ÛÛÛ ÛÛ    Û ÛÛÛÛÛ");
		gotoxy(10,15);cprintf("ÛÛ      ÛÛ Û   Û Û Û   Û Û   Û Û     Û   Û Û Û Û Û   Û Û   Û   Û");
		gotoxy(10,16);cprintf("ÛÛ      ÛÛ Û ßßÛ Û  Û  Û Û ßßÛ Û  ÛÛ ÛÛÛ Û  Û  Û ÛÛ  Û  Û  Û   Û  ");
		gotoxy(10,17);cprintf("ÛÛ      ÛÛ Û   Û Û   Û Û Û   Û Û   Û Û   Û     Û Û   Û   Û Û   Û  ");
		gotoxy(10,18);cprintf("ÛÛ      ÛÛ Û   Û Û    ÛÛ Û   Û ÛÜÜÜÛ ÛÛÛ Û     Û ÛÛÛ Û    ÛÛ   Û");
		gotoxy(10,21);cprintf("    SUBMITTED BY : KUSHAGRA AMAN, RITIK GANGWAR, TUMUL SAXENA     ");
		gotoxy(10,23);cprintf("              SUBMITTED TO : MR SHAKTIRISHKUMAR AGARWAL           ");


		if(i==15)
			i=0;
	}
}

void building()                     //Functioo display the building
{
	_setcursortype(_NOCURSOR);
	for(int i=0;!kbhit();i++) //kbhit() for keystroke;
	{
		textcolor(i);
		int x=14,y=3;
		gotoxy(x ,y   );cprintf("                 ÜßßßßßßßßßßßßßßßßßßßÜ                    \n");
		gotoxy(x ,y+ 1);cprintf("               Üß                     ßÜ                  \n");
		gotoxy(x ,y+ 2);cprintf("             Üß                         ßÜ                \n");
		gotoxy(x ,y+ 3);cprintf(" ÛßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßÛ   \n");
		gotoxy(x ,y+ 4);cprintf(" Û                  ARTHA CONSOLIDATE                 Û   \n");
		gotoxy(x ,y+ 5);cprintf(" ÛßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßÛ   \n");
		gotoxy(x ,y+ 6);cprintf(" Û  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  Û	 \n");
		gotoxy(x ,y+ 7);cprintf(" Û  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  Û   \n");
		gotoxy(x ,y+ 8);cprintf(" Û  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  Û   \n");
		gotoxy(x ,y+ 9);cprintf(" Û  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  Û   \n");
		gotoxy(x ,y+10);cprintf(" Û  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  Û   \n");
		gotoxy(x ,y+11);cprintf(" Û  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  Û   \n");
		gotoxy(x ,y+12);cprintf(" Û  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  Û   \n");
		gotoxy(x ,y+13);cprintf(" Û  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  Û   \n");
		gotoxy(x ,y+14);cprintf(" Û  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ» ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»  ÉÍ»   Û     \n");
		gotoxy(x ,y+15);cprintf(" Û  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼ ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼  ÈÍ¼   Û   \n");
		gotoxy(x ,y+16);cprintf(" Û                     WELCOME                        Û    ");
		gotoxy(x ,y+17);cprintf(" Û               ÛÛÛÛÛÛÛÛ    ÛÛÛÛÛÛÛÛ                 Û   \n");
		gotoxy(x ,y+18);cprintf(" Û               ÛÛÛ  ÛÛÛ    ÛÛÛ  ÛÛÛ                 Û   \n");
		gotoxy(x ,y+19);cprintf(" Û               ÛÛÛ  ÛÛÛ    ÛÛÛ  ÛÛÛ                 Û   \n");
		gotoxy(x ,y+20);cprintf(" Û               ÛÛÛ  ÛÛÛ    ÛÛÛ  ÛÛÛ                 Û   \n");
		gotoxy(x ,y+21);cprintf(" ßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßßß   \n");
		if(i==15)
			i=0;
	}
	_setcursortype(_SOLIDCURSOR);

}

void box(int n=10,int xa=2,int xb=79,int ya=2,int yb=24)//Function to create box in the output window
{
	int i;
	rancob();                           //Calling of function rancob
	for(i=xa;i<xb;i+=2)
	{
		gotoxy(i,ya);cprintf(" ");
		delay(n);
	}
	for( i=ya;i<=yb;i++)
	{
		gotoxy(xb,i);cprintf("");
		delay(n);
	}
	for(i=xb-2;i>=xa;i-=2)
	{
		gotoxy(i,yb);cprintf(" ");
		delay(n);
	}
	for( i=yb;i>=ya;i--)
	{
		gotoxy(xa,i);cprintf("");
		delay(n);
	}
	normal();

}

menu (char opt[][15],int r,int x=1,int ya=1)   //Function to display the menu
{
	int a,dy=1,y=ya;r--;
	do
	{
		textcolor(7);textbackground(0);
		textcolor(2);
		for(int i=0;i<r+1;i++)
		{
			if(y==i+ya)
				continue;
			gotoxy(x,ya+i);cprintf("%s",opt[i]);
		}
		textcolor(1+BLINK);textbackground(2);
		gotoxy(x,y);cprintf("%s",opt[y-ya]);
		textcolor(7);textbackground(0);
		gotoxy(x,y);
		_setcursortype(_NOCURSOR);
		a=getch();
		textcolor(7);textbackground(0);
		if(a==13)
			break;
		else if(a!=00)
			continue;
		a=getch();
		if(a==72||a==75)
		{
			if(y<=ya)
				y=ya+r;
			else
				y-=dy;
		}
		if(a==80||a==77)
		{
			if(y>=ya+r)
				y=ya;
			else
				y+=dy;
		}

	}while(a!=13);
	return y-ya;
}


var gem()                              //Function to control comma placement
{
	var n=0;
	int i,j;
	char a[15];
	for(i=0;;++i)
	{
		a[i]=getch();
		if(a[i]==13)                    //13 is ascii valu of enter
			break;
		else if(a[i]==8)             //8 is ascii value of backspace
			{
				if(i==0)
				{
					i--;
					continue;
				}
				for(j=0;j<i;j++)
					{
					if((i-j)>3&&((i-j)%2==0))
						cout<<char(8)<<' '<<char(8);              //To control commas
					cout<<char(8)<<' '<<char(8);                      //To control digit
					}
				i-=2;
				for(j=0;j<=i;j++)
					{
					if((i-j)>1&&((i-j)%2==0)&&(i-j)!=i)
						cout<<',';
					cout<<a[j];
					}
				continue;
			}
		else if(!isdigit(a[i]))
			{
				i--;
				continue;
			}
		cout<<a[i];
		if(i>2)
			{
			for(j=0;j<=i;j++)
				{
				if((i-j)>3&&((i-j)%2==0))
					cout<<char(8)<<' '<<char(8);
				cout<<char(8)<<' '<<char(8);
				}
			for(j=0;j<=i;j++)
				{
				if((i-j)>1&&((i-j)%2==0)&&(i-j)!=i)
					cout<<',';
				cout<<a[j];
				}
			}
	}
	a[i]='\0';
	cprintf(" INR ");
	cout<<endl;
	j=strlen(a)-1;
	for(i=0;a[i]!='\0';++i)
		n+=((a[i]-48)*pow(10,j-i));
	return n;
}



void putm(var num)                        //Function to display commas while displaying
{
	if(num<0)
	{
		num=-num;                              //used for loan money
		cprintf("Loan Of ");
	}
	for(int i=0;long(num/pow(10,i))>0;i++);
	for(i--;i>0;i--)
	{
		cout<<long(num/pow(10,i))%10;
		if(i%2==1&&i>2)
			cout<<",";
	}

	cout.setf(ios::fixed);
	cout<<setprecision(4)<<(long(num)%10)+num-long(num);
	cprintf(" INR ");
}

void getp(char nam[])                //Used to enter the password
{
	for(int i=0;;i++)
	{
		nam[i]=getch();
		if(nam[i]==13)
			break;
		if(nam[i]==8)
		{
			if(i==0)
			{
				i--;
				continue;
			}
			cout<<char(8)<<' '<<char(8);
			i-=2;
			continue;
		}
		cout<<"*";
	}
	nam[i]='\0';
}



class tran                                  //Class created for transaction
{
	var mon ,trans;
	char date[10],acc[10];
	int ch;
	public:
	tran(char account[],var transf,int chf)
	{
		_strdate(date);
		strcpy(acc,account);
		ch=chf;
		trans=transf;
	}
	tran(char account[])
	{
		_strdate(date);
		strcpy(acc,account);
	}
	tran()
	{
		_strdate(date);
	}
	void display()                     //Function to display transactions
	{
		clrscr();
		fstream f;
		tran s;
		int r=5;
		char cho[5][15],ch;
		rancob();
		gotoxy(25,2);cprintf(" List Of Transactions");
		normal();
		gotoxy(2, 3);cout<<"Widrawn";
		gotoxy(16,3);cout<<"Depsited";
		gotoxy(30,3);cout<<"Date";
		gotoxy(40,3);cout<<"Balance";
		gotoxy(1,4);
		for (int j=1; j<80; j++)
			cout<<"~";
		f.open(f1,ios::in|ios::binary);
		f.seekg(0);
		while(f.read((char*)&s,sizeof(s)))
		{
			if(strcmpi(acc,s.acc)==0)
			{
				if(s.ch==0)
				{
					gotoxy(2,r);putm(s.trans);
				}
				if(s.ch==1)
				{
					gotoxy(16,r);putm(s.trans);
				}
				gotoxy(30,r);cout<<s.date;
				gotoxy(40,r);putm(s.mon);
				r++;
				if (r>22)
				{
					gotoxy(4, 24);
					cout<<"Press any key to continue";
					getch();
					for(int r=6;r<23;r++)
					{
						gotoxy(1,r);clreol();
					}
					r=5;
				}
			}
		}
		f.close();
		getch();
	}

	int input()
	{
		fstream f;
		detail s;
		int n=1,ti=0;
		int found=0;
		f.open(fl,ios::in|ios::out|ios::binary);
		while(!f.eof())
		{
			n=f.tellg();
			f.read((char*)&s,sizeof(s));
			if(strcmpi(acc,s.acc)==0)
			{
				mon=s.mon;
				ti=exch();
				s.mon=mon;
				f.seekg(n);
				f.write((char*)&s,sizeof(s));
				found=1;
				break;
			}
		}
		normal();
		f.close();
		if(found==0||ti==0)
		{
			gotoxy(5,24);  textcolor(5+BLINK);cprintf("Account Not Verified");
			getch();
			return 0;
		}
		return 1;
	}


	int exch()
	{
		int t=0;
		if(acc[2]=='2')
			return 0;
		if(ch==0)
		{
			if(acc[2]=='3')
				return 0;
			if(acc[2]=='0'&&(mon-trans)>-100000)
				t=1;
			if(acc[2]=='1'&&(mon-trans)>0)
				t=1;
			if(t==1)
				mon-=trans;
			return t;
		}
		if(ch==1)
			mon+=trans;
		return 1;
	}
	friend var find(char a[],var m);
	friend void delete_account(char t_acc[]);
};

var find(char ac[],var m)               //Function used to find minimum money to give loan
{
	char dat[9];
	var min=m;
	_strdate(dat);
	fstream f;
	tran s;
	f.open(f1,ios::in|ios::binary);
	f.seekg(0);
	while(f.read((char*)&s,sizeof(s)))
	{
		if(strcmpi(s.acc,ac)==0)
		{
			if(dat[6]==s.date[6]&&dat[7]==s.date[7]&&dat[8]==s.date[8]&&dat[9]==s.date[9])
			{
				if(min>s.mon)
					min=s.mon;
			}
		}
	}
	f.close();
	return min;
}





class detail                             //Main class to enter the details
{
	public:
	char gua[30],nam[30],add[50],dat[9],acc[6],cri[30],rel[30],nom[30],job[30];
	var mon;
	int input();
	void show();
	void modify();
	void trans();
	void list();
	void report();
	char *ret_acc();
	char *ret_dat();


};
	char* detail::ret_acc()                  //Function to return account number
	{
		return acc;
	}
fstream f,g;

void rules()                              //Function to display policies
{
	fstream f;
	char opt[][15]={"CURRENT","SAVING","FIXED ACCOUNT","LOAN","EXIT"},a;
	for(;;)
	{
		clrscr();
		int n=-1;
		box(0,4,76,2,24);
		int j=menu(opt,5,25,7);
		clrscr();
		if(j==4)
			return;
		box(0,4,76,2,24);
		f.open("Rules.txt",ios::in);
		f.seekg(0);
		gotoxy(2,5);
		while(!f.eof())
		{
			f.get(a);
			if(a=='*')
				n++;
			else if(n==j)
				cout<<a;
		}
		f.close();
		getch();
	}
}


void detail::modify()                     //Function to make changes in the account
{
	char acc[7], newname[30],newadd[40],cho[5][15],ch;
	int n=1,found=0;
	detail s;
	box(0,8,65,3,19);
	gotoxy(30,3);  cprintfc("MODIFTY YOUR ACCOUNT");
	gotoxy(10,7);   cprintf("Enter the account no.=");
	gotoxy(10,9);  cprintf("Enter your name=");
	gotoxy(10,11);  cprintf("Enter your address=");
	gotoxy(10,15);  cprintfc("Press enter to make  no changes");
	gotoxy(35,7);   getp(acc);
	gotoxy(27,9);   gets(newname);
	gotoxy(32,11);  gets(newadd);
	gotoxy(5,15);  clreol();
	gotoxy(10,15); cprintf("Do You Want To Save Changes : ");
		strcpy(cho[0],"NO");
		strcpy(cho[1],"YES");
		ch=menu(cho,2,10,16);
			if(ch==0)
			{
				clrscr();
				return;
			}
	f.open(fl,ios::in|ios::out|ios::binary);
	while(!f.eof())
	{
		n=f.tellg();
		f.read((char*)&s,sizeof(s));
		if(strcmpi(acc,s.acc)==0)
		{
			if(newname[0]!='\0')
				strcpy(s.nam,newname);
			if(newadd[0]!='\0')
				strcpy(s.add,newadd);
			f.seekg(n);
			f.write((char*)&s,sizeof(s));
			found=1;
			break;
		}
	 }
	 if(found==0)                     //Runs when invalid account nmber
	 {
		gotoxy(5,24);  clreol();
		gotoxy(5,24);  textcolor(7+BLINK);cprintf("Account Not Found");
		getch();
	 }
	 normal();
	 f.close();
}

int detail::input()                      //Function used to enter the details of user
{

	detail s;
	char cho [6][15];
	var t_mon=0;
	int ch,ti=0;
	box(0,8,75,2,24);
	gotoxy(30,2);  cprintfc("Enter your details");
	gotoxy(10,4);  cprintf("Account no= ");
	gotoxy(10,5);  cprintf("Enter your name=");
	gotoxy(10,6);  cprintf("Enter your address=");
	_strdate(dat);
	gotoxy(10,7);  cprintf("Current date= %s",dat);
	gotoxy(10,8);  cprintf("Enter the name of your guaranteer=");
	gotoxy(10,9);  cprintf("Enter the amount of money=");
	gotoxy(10,10);  cprintf("Enter your relationship status=");
	gotoxy(10,11);  cprintf("Enter your occupation=");
	gotoxy(10,12);  cprintf("Enter the name of your Nominee=");
	gotoxy(10,13);  cprintf("Enter the your criminal record=");


	gotoxy(27,5);   gets(nam);
	do
	{
	gotoxy(30,6);  gets(add);
	ch=0;
	for(int i=0;i<strlen(add);++i)
		if(ispunct(add[i])&&(i+1)<strlen(add))  //punctuation function
		{
			ch++;
			i++;
		}
	if(ch<2)
	{
		gotoxy(1,6);clreol();
		gotoxy(10,6);cprintf("Enter Address with proper PUNCTUATION");
		delay(1500);
		gotoxy(10,6);clreol();
		gotoxy(10,6);cprintf("Enter your address = ");
		box(0,8,75,2,24);
	}
       }
       while(ch<2);
       gotoxy(45,8);  gets(gua);
       gotoxy(37,9);  mon=gem();
       gotoxy(42,10);   gets(rel);
       gotoxy(33,11);  gets(job);
       gotoxy(43,12);   gets(nom);
       gotoxy(43,13);  gets(cri);
       gotoxy(10,14); cprintf("REQUIRED TYPE OF ACCOUNT : ");
			strcpy(cho[0],"CURENT");
			strcpy(cho[1],"SAVING");
			strcpy(cho[2],"FIXED DEPOSIT");
			strcpy(cho[3],"LOAN");
			ch=menu(cho,4,15,15);
			if(ch==3)
			{
				f.open(fl,ios::in,ios::binary);
				f.seekg(0);
				while(f.read((char*)&s,sizeof(s)))
					if(strcmpi(gua,s.nam)==0)
						if(s.mon>mon)
							ti=1;
				f.close();
				f.open(fl,ios::in,ios::binary);
				f.seekg(0);
				if(ti==1)
				{
					while(f.read((char*)&s,sizeof(s)))
						t_mon+=s.mon;
					if((0.85*t_mon)<mon)
						ti=0;
				}
				f.close();
				if(ti==0)
				{
					gotoxy(10,20);
					cprintf("LOAN NOT CERTIFIED");
					getch();
					return 0;
				}
				mon=(-mon);
			}
       strcpy(acc,"AC");
       acc[2]=48+ch;
       pqr:
       {
       for(int i=0;i<3;i++)
		acc[i+3]=48+random(10);
       acc[i+3]='\0';
       g.open(fl,ios::in|ios::binary);
			g.seekg(0);
			while(g.read((char*)&s,sizeof(s)))
			{
				if(strcmpi(s.ret_acc(),acc)==0)
					goto pqr;
					g.close();
			}
       g.close();
       }
       gotoxy(22,4); textcolor(3+BLINK);   cprintf("%s",acc);
       normal();
       acc[8]=0;
       return 1;
}


void detail::show()               //Function used to display the details of user
{
	box(0,18,65,3,17);
       gotoxy(30,3);  cprintfc("The  details are");
       gotoxy(20,7);  cprintf("Account no= %s",acc);
       gotoxy(20,9);  cprintf(" name=");
       gotoxy(20,11);  cprintf("address=");
       gotoxy(20,13);  cprintf("Account date= %s",dat);
       gotoxy(20,15);  cprintf("Amount of money= ");

       gotoxy(27,9);   puts(nam);
       gotoxy(29,11);  puts(add);
       gotoxy(39,15);  putm(mon);

}

void delete_account(char t_acc[])               //Function to display details
{
	fstream f, t;
	detail abc;
	f.open(fl, ios::in|ios::binary);
	t.open("TEMP.txt", ios::out|ios::binary);
	f.seekg(0);
	while (f.read((char *)&abc, sizeof(abc)))
		if (strcmpi(abc.ret_acc(),t_acc))
			t.write((char *)&abc,sizeof(abc));
	f.close();t.close();
	remove(fl);
	rename("TEMP.txt",fl);


	tran ab;
	f.open(f1, ios::in|ios::binary);
	t.open("TEMP.txt", ios::out|ios::binary);
	f.seekg(0);
	while (f.read((char *)&ab, sizeof(ab)))
		if (strcmpi(abc.ret_acc(),t_acc))
			t.write((char *)&ab,sizeof(ab));
	f.close();t.close();
	remove(f1);
	rename("TEMP.txt",f1);
}

void detail::list()                        //function to display list of user accounts
{
	clrscr();
	detail s;
	float t_bal=0.0;
	fstream f;
	rancob();
	gotoxy(25,2);cprintfc(" List Of Account");
	normal();
	gotoxy(3, 5);cout<<"Acc no";
	gotoxy(15,5);cout<<"Name";
	gotoxy(45,5);cout<<"Balance";
	gotoxy(1, 6);
	for (int j=1; j<80; j++)
		cout<<"~";
	f.open(fl, ios::in|ios::binary);
	f.seekg(0);
	int r=7;
	while (f.read((char *)&s, sizeof(s)))
	{
		gotoxy(3,r);cout <<s.acc;
		gotoxy(15, r);puts(s.nam);
		gotoxy(45, r);putm(s.mon);
		t_bal=t_bal + s.mon;
		r++;
		if (r>22)
		{
			gotoxy(4, 24);
			cout<<"Press any key to continue";
			getch();
			for(int r=6;r<23;r++)
				{
				gotoxy(1,r);clreol();
				}
			r=7;
		}
	}
	r++;
	gotoxy(12, r);cout<<"Total Balance in Bank is : ";
	gotoxy(39, r);putm(t_bal);
	f.close();
}



void detail::trans()               //Function to perform transaction
{
	int ch,tru;
	char cho[5][15];
	fstream f;
	var temp;
	box(0,8,40,3,18);
	gotoxy(20,3);  cprintfc(" TRANSACTION ");
	gotoxy(10,7);  cprintf("Account no= ");

	gotoxy(10,13); cprintf("Enter amount= ");
	gotoxy(24,7);   getp(acc);
	strcpy(cho[0],"Withdraw");
			strcpy(cho[1],"Deposit");
			tru=menu(cho,2,20,9);
	_setcursortype(_SOLIDCURSOR);
	gotoxy(25,13);   (temp)=gem();
	gotoxy(10,15); cprintf("Do You Want To Save Changes : ");
			strcpy(cho[0],"NO");
			strcpy(cho[1],"YES");
			ch=menu(cho,2,10,16);
			if(ch==0)
			{
				clrscr();
				return;
			}
       tran t(acc,temp,tru);
       int ti=t.input();
       if(ti==1)
       {
	       f.open(f1,ios::app|ios::binary);
	       f.write((char *)&t,sizeof(t));
	       f.close();
	       clrscr();
	       animation();
       }
}


void rancob()                     //Function to control display of background and text
{
	p:
	int i=random(14)+1,j=random(14)+1;
	if(i==j||i==8||j==8)
		goto p;
	if((random(2))%2==0)
		textcolor(j + BLINK);
	else
		textcolor(j);
	if((random(2))%2==0)
		textbackground(i);
	else
		textbackground(i+ BLINK);
}

void normal()                                 //Function to normalise the text color and background color
{
	textcolor(7);
	textbackground(0);
}


void interest()
{
	int n=0,t=0;
	var min=0;
	detail s;
	char tod[10];
	_strdate(tod);
	f.open(fl,ios::out|ios::in|ios::binary);
	f.seekg(0);
	while (!f.eof())
	{
		n=f.tellg();
		f.read((char*)&s,sizeof(s));
		{
			if(s.dat[6]>=tod[6])
				if(s.dat[7]>=tod[7])
					if(s.dat[8]>=tod[8])
						if(s.dat[9]>tod[9])
							t++;
			if(s.dat[3]<=tod[3])
				if(s.dat[4]<tod[4])
					t--;
		}
		if(t!=s.acc[8])
		{
			int b=t-s.acc[8];
			min=find(s.acc,s.mon);
			if(s.acc[2]=='1')
				s.mon=s.mon+b*(0.1*min);
			if(s.acc[2]=='3')
				s.mon=s.mon+b*(0.12*min);
			if(s.acc[2]=='2')
				if(s.acc[8]%5==0&&t>1)
					s.mon=2*(b/5)*s.mon;
			s.acc[8]=t;
		}
		f.seekg(n);
		f.write((char*)&s,sizeof(s));
	}
	f.close();
}

void main()
{
	randomize();
	normal();
	detail s,n;
	int c,ch;
	char mat[10];
	clrscr();
	char cho[5][15];
	char opt[10][15]={
				"NEW ACCOUNT",
				"SHOW ACCOUNT",
				"MODIFY ACCOUNT",
				"DELETE ACCOUNT",
				"TRANSACTION",
				"LIST OF DEALS",
				"BANK REPORT",
				"POLICY",
				"EXIT"
			};
	_setcursortype(_NOCURSOR);
	box(50,2,78,2,24);
		welcome();
	clrscr();
	getch();
	box(50,2,78,2,24);
		pro_name();
	clrscr();
	getch();
	for( ; ; )
	{
		for(int i=0;i<4;i++)
		{
			rancob();
			box(0,28-(2*i),48+(2*i),8-(2*i),19+(2*i));
			delay(60);
		}
		normal();
		gotoxy(36,8);cprintfc("MENU");
		c=menu(opt,9,32,10);
		_setcursortype(_SOLIDCURSOR);
		if(c==0)                      //choise made of input
		{
			clrscr();
			normal();
			box(4,2,78,1,25);
			building();
			getch();
			clrscr();
			ch=s.input();
			if(ch==0)
			{
				clrscr();
				continue;
			}
			gotoxy(10,20); cprintf("Do You Want To Save Changes : ");
			strcpy(cho[0],"NO");
			strcpy(cho[1],"YES");
			int cp=0;
			cp=menu(cho,2,10,21);
			if(cp==0)
			{
				clrscr();
				continue;
			}
			f.open(fl,ios::app|ios::binary);
			f.write((char*)&s,sizeof(s));
			f.close();
			clrscr();
			animation();
		}
		if(c==1)                     //function to display the account
		{
			clrscr();
			normal();
			box(1,2,78,1,25);
			building();
			getch();
			clrscr();
			gotoxy(30,13);cprintf("Your Account Number=");
			getp(mat);
			g.open(fl,ios::in|ios::binary);
			g.seekg(0);
			clrscr();
			while(g.read((char*)&s,sizeof(s)))
			{
				if(strcmpi(s.ret_acc(),mat)==0)
					s.show();
			}
			g.close();
		}
		if(c==2)                                    // Function to modify the account
		{
			clrscr();
			normal();
			box(1,2,78,1,25);
			building();
			getch();
			clrscr();
			s.modify();
		}
		if(c==3)                                    //Function to delete the account
		{
			clrscr();
			normal();
			box(1,2,78,1,25);
			building();
			getch();
			clrscr();
			gotoxy(30,13);cprintf("Your Account Number To be Deleted =");
			getp(mat);
			gotoxy(3,20); cprintf("Do You Want To Save Changes : ");
			strcpy(cho[0],"NO");
			strcpy(cho[1],"YES");
			ch=menu(cho,2,3,21);
			if(ch==0)
			{
				clrscr();
				continue;
			}
			delete_account(mat);
			clrscr();
			animation();
		}
		if(c==4)                      //Function to display the transactions
		{
			clrscr();
			normal();
			box(1,2,78,1,25);
			building();
			getch();
			clrscr();
			s.trans();
		}
		if(c==5)                                  //Function to display the  list
		{
			clrscr();
			normal();
			box(1,2,78,1,25);
			building();
			getch();
			clrscr();
			gotoxy(30,13);cprintf("Your Account Number=");
			getp(mat);
			clrscr();
			tran t(mat);
			t.display();
		}
		if(c==6)                                      //function to display bank report
		{
			clrscr();
			normal();
			box(1,2,78,1,25);
			building();
			getch();
			clrscr();
			s.list();
		}
		if(c==7)                                          //Function to display the policy
		{
			clrscr();
			normal();
			box(1,2,78,1,25);
			building();
			getch();
			clrscr();
			rules();
		}

		if(c==8)                            // function to exit
		{
			exit(0);
		}
		getch();
		clrscr();
	}
}
