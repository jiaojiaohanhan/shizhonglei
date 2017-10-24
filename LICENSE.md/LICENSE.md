import java.util.*;
import java.io.*;
class Clock {
	private int Hour,Minute,Second;
	Scanner o=new Scanner(System.in);
    int NewH=o.nextInt();
    int NewM=o.nextInt();
int NewS=o.nextInt();

	public void SetTime() // 设置时、分、秒
	{
		this.Hour=NewH;
		this.Minute=NewM;
		this.Second=NewS;
	}
	
	public void ShowTime()  // 显示时、分、秒
	{	
		System.out.println(this.Hour+":"+this.Minute+":"+this.Second);
	}
}
public class Main{
	//程序入口
	public static void main(String[] args) {
    Clock myClock=new Clock();
    myClock.SetTime();
	myClock.ShowTime();
	}
}
