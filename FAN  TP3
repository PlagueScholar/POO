public class Fan {
	
	int speed; 
    boolean energy; 
    boolean rotation; 
	
	
    public Fan()
    {
      this.speed = 0;
      this.energy = false;
      this.rotation = false;
    }
    
    void switchenergy()
    {
    	this.energy = !this.energy;
    }
    void switchrotation() 
    {
    	this.rotation = !this.rotation;
	if(this.rotation==true)
    	{
    		this.speed = 1;
    	}
    }
	void increasespeed()
	{
		if(this.rotation==false)
		{
			this.speed = 0;
		}
		else
		{
			if(this.speed<5) 
			{
			this.speed+=1;
			}
			else 
			{
			this.speed=5;	
			}
		}
	}
	
	void decreasespeed()
	{
		if(this.rotation==false)
		{
			this.speed = 0;
		}
		else
		{
			if(this.speed>1) 
			{
			this.speed-=1;
			}
			else 
			{
			this.speed=1;	
			}
		}
	}
	
	void situation()
	{
	if(this.energy=false)
	 {
			System.out.print("The Fan is Off");
	 }
	else 
	 {
		if(this.rotation==false)
		{
	        System.out.print("The Fan is On \n" );
	        System.out.print("The Fan isn't rotating \n");
	    }
		else 
		{
			System.out.print("The Fan is On \n");
		    System.out.print("The Fan is rotating \n");
		    System.out.print("The fan is in speed " + speed);
		}
	 }
}
