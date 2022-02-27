int main()
{
system("cls");
int w;
while(1)
{
//system("cls"); cout&lt;&lt;"\n\n"; cout&lt;&lt;"\t\t***SIMPLE BUS RESERVATION SYSTEM***";
cout&lt;&lt;"\n\n";
cout&lt;&lt;"\t\t\t1.Install\n\t\t\t"
&lt;&lt;"2.Reservation\n\t\t\t"
&lt;&lt;"3.Show Reservation\n\t\t\t"
&lt;&lt;"4.Buses Available \n\t\t\t"
&lt;&lt;"5.Exit";
cout&lt;&lt;"\n\t\t\tEnter your Choice:- ";
cin&gt;&gt;w;
switch(w)
{
case 1: bus[t].add_new_number_of_bus(); break; case 2: bus[t].reservation(); break; case 3: bus[0].view(); break; case 4: bus[0].avail(); break; case 5: exit(0);
}
}
return 0;
}
