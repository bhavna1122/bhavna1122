 bhavna kawd
 #include<iostream>
using namespace std;
class cube
{
	private:
		int side;
		public:
			cube(int c)
			{
				side=c;	
			}
			void display()
			{
				cout<<"\ncube="<<side*side*side;
			}
};
main()
{
	int c;
	cout<<"Enter Side=";
	cin>>c;
	cube c1(c);
	c1.display();
	 
}
